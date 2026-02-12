# NextJS Tutorial Notes

## Chapter 1. Getting Started

I installed the pnpm packet manager.
![alt text](/screenshots/1.png)

I create nextjs app with the started example.
![alt text](/screenshots/2.png)

## Chapter 2. Styling

In this chapter, I added styles for my app using tailwind and css modules.

## Chapter 3. Optimizing Fonts and Images

In this chapter, I imported 2 fonts (Inter, Lusitana) and added responsive images for the hero section for mobile and desktop screens.
Also I added back background styles for AcmeLogo component container.

## Chapter 4. Creating Layouts and Pages

In this chapter, I create dashboard page with two children pages and layout for them.
![alt text](/screenshots/3.png)

## Chapter 5. Navigating Between Pages

I used the usePathname hook to get the path name and dynamically update styles when the page changed.
![alt text](/screenshots/4.png)

## Chapter 6. Setting Up Your Database

Before, I have registered with my github on vercel and deploy this project
![alt text](/screenshots/5.png)
Then I created database using Neon provider and seed with data.
![alt text](/screenshots/6.png)

## Chapter 7. Fetching Data

In this chapter, I added data fetching from database.

## Chapter 8. Static and Dynamic Rendering

![alt text](/screenshots/7.png)

## Chapter 9. Streaming

![alt text](/screenshots/8.png)
![alt text](/screenshots/9.png)

In this chapter, I implemented streaming data loading with React Suspense and loading.tsx.

## Chapter 10. Adding Search and Pagination

![alt text](/screenshots/10.png)
![alt text](/screenshots/11.png)

In this capter, I implemented search and pagination functionality using useSearchParams, usePathname and useRouter hooks for invoices.

## Chapter 11. Mutating Data

![alt text](/screenshots/12.png)
![alt text](/screenshots/13.png)
![alt text](/screenshots/14.png)

I implemented CRUD operations for invoices usign nextjs actions with zod validation and cache revalidation.

## Chapter 12. Handling Errors

![alt text](/screenshots/15.png)
![alt text](/screenshots/16.png)

In this chapter, I added error.tsx and not-found.tsx to handle unexpected errors and unexisted data (invoices).

## Chapter 13. Improving Accessibility

![alt text](/screenshots/17.png)
![alt text](/screenshots/18.png)

I set up linter and server side form validate using useActionStete hook to improve accessibility in my forms.
