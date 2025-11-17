graph BT;
    subgraph School Assessment BU
        subgraph Product Team
            
            D(Instructional Designers<br><i>LMS Content Management</i>) --> C(Megan Koebbe<br><b>Manager</b>);
            E(Jonathan<br><b>Front-End Engineer</b><br><i>LMS Admin & Setup</i>) --> C;
            F(Jeremy<br><b>Graphic Designer</b><br><i>LMS Visuals</i>) --> C;
            
            C --> B(Miranda Pasturczak<br><b>Head of Technology Implementation</b>);
            B --> A(Amy Riley<br><b>Head of Product</b>);

            %% This line forces the vertical layout
            { rank = same; D; E; F }

        end
    end

style A fill:#f9f,stroke:#333,stroke-width:2px
style B fill:#f9f,stroke:#333,stroke-width:2px
style C fill:#f9f,stroke:#333,stroke-width:2px
style D fill:#ccf,stroke:#333,stroke-width:2px
style E fill:#ccf,stroke:#333,stroke-width:2px
style F fill:#ccf,stroke:#333,stroke-width:2px
