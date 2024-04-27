# Cracking Frontend System Design

## Things to Consider in Frontend System Design Interviews

    1. Requirements (HLD)
        a. Functional
            i. Demand/Supply - Do you want B2B or B2C application?
            ii. Module level thinking
                1) User management
                2) Help & Support
                3) Payment Gateway
                4) Pricing & subscription
                5) Cart Page
                6) Product Listing
                7) Account Management
            iii. Feature level thinking

        b. Non-Functional
            i. Mobile/Desktop based application
            ii. Responsive/Adaptive
            iii. Internet/Location/Devices
            iv. Accessibility
            v. Asset optimization (CSS, JS, Images)
            vi. Performance (FCP, LCP, TTI, Web Vitals)
            vii. CSR/SSR
            viii. Authentication/Authorization
            ix. Security
            x. Caching
            xi. Offline Support
            xii. Logging & Monitoring
            xiii. A/B Testing
            xiv. Testing
            xv. Internationalization
            xvi. Localization
            xvii. Versioning
            xviii. PWA
            xix. CI/CD

    2. Scoping (Prioritization) (HLD) - Scope needs to be discussed with interviewer so that you discuss certain things in deep rather than everything you have in mind.

        a. Functional
            i. Demand
            ii. Module
                1) Product Listing
                2) Cart page
            iii. Features
                3) Search
                4) Listing
                5) Product Details
                6) Reviews
                7) Add item to cart/Wishlist
                8) Price breakups
                9) Add/remove products

        b. Non-Functional
            i. Desktop
            ii. Responsive
            iii. Accessibility
            iv. Asset optimization
            v. Performance
            vi. Caching

    3. Tech Choices (HLD)
        a. Library/Framework - Discuss about which library or framework you would choose and why?
        b. State management
        c. Folder structure
        d. Packages - Monorepos
        e. Dependencies (Canvas/SVG, WebRTC)
        f. Design System (Do you want to build your own design system or want to use existing ones such as Material UI, Fluent UI, Ant Design, etc.)
        g. Built tools (Webpack, Rollup, Parcel)

    4. Component Architecture (LLD)
        a. Component Hierarchy
        b. Routing
        c. Data Sharing

    5. Data API & protocols & Implementation (LLD)
        a. Protocols
            i. Rest/GraphQL/SSE/rPF
            ii. JSON/Protocol Buffers
        b. Implementation
            i. Pagination/Infinite Scrolls
            ii. Debouncing/Throttling
        c. APIS
            i. getProductList()
            ii. getProductDetails()
            iii. addProductToList()
            iv. removeProductFromLCart()
        d. Data Modelling
            i. URL
            ii. Method
            iii. Request (query, body)
            iv. Response (Data, Error)
            v. Status code
        e. Component
            i. State/Props
            ii. Event handling
            iii. Customization (Theming)
            iv. Reusability
            v. Data Source

### Notes for System Design Interviews

- Discuss either the HLD or LLD depending upon what's asked specifically.
- HLD is mostly asked to Senior Devs(5+ YOE) but can be asked to Junior Devs sometimes.
- Try to showcase the knowledge you have in that short span of time, you might have to speak a lot for this.
- Keep on checking requirement/expectations from the interviewer.
- Don't rush into implementation.
- Pick one problem at a time.
- Get familiar with the tools which will help you to explain.
- Practice 2-3 System design using different tools.
