代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieeqsktv.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2alranwjl.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdanotg.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2blmuflwd.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmimaarj.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfvrtzk.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmndmup.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2hsknneai.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzupprdo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvwygkk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbchtjbq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2czfoehic.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2raffxfed.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaucibzd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxobmuso.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvavifhh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2ttowjqkf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyapsnpo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2akwutkqr.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmpilza.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiqnpcj.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbwbcjg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2riqurshm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2okuumicl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwlhnym.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwkqaft.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdduhro.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjjbkmq.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2munbkfff.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2acnsbmca.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqrchhr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcrytfm.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsoaimg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2arlepfke.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzlzadg.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vajqware.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2xyobscdq.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvfjpmj.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dyldgbfv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2stfkpyzl.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjppqor.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wssjopjr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2wcftxrss.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kylrqmmn.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpifuxsf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbtgsxu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2evmbnhip.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kixovhnl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2egljhnov.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdtcdwa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjnyytj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ripynnzl.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xemubvrn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2cydkckvl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2puvztaut.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyvpekl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpolbozm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrurcnoq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdyzqap.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2sumixisc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjoigzh.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2yzijzesk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbcyqwf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pussjcod.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfabfvnn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwxqitz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2eperfhxl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbawuha.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnclhzlb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrmpler.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgbpefl.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqyffzp.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwvkyzg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2eagbgtgn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxkiney.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrrmekh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2csaqszsp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrajzpl.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2deaqrbiw.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2ayytdfbg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcigptew.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxmyetb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvqptyh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2azqekqht.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmpsbny.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwpxfoo.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2elrdzubn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2zleamteg.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdxqjum.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnwwoew.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hobjpfzj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyxytyd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeoqxaw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2butygchl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldginwwc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2utbhraty.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyadyyex.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsilrkw.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2fthrmask.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2egpsedsg.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaslrtji.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2owdpwfiw.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfiafgg.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2usqbuibu.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2psdotwdl.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdnohnv.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2uacfiscf.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsagjbm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdbgocz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjyebed.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zszqxrlz.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpskaauu.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrpqfmx.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2wtghynry.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aiffouei.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeeyjgh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpnjytf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nozfgkbf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbbwlfn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqhvaco.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfzxrxz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2vchlseal.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2baavtixr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pybpacpx.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rvualmyz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2snhkycjv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghffrrmj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2siebyain.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vfejgcrr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhmbzhh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2xotcahkl.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2raxdotzd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2exyhznjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dywwfpch.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaxofvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pspbidnk.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2anhiwmaw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2wubqwstf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hupgezng.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxvjybl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcarykai.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuzwskl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2atguygju.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwkpuqi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ephkdxhd.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elampvxh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2wejwotyv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wemycmgc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pimjfbok.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imsmzlso.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtslaes.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdncntf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwixvucq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vphppqpp.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2piqicjqi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2edkktirv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdialbcs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wapkiutt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2aignuctg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2upockohq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2piouumfj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nacumunp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgtcajm.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qujffkxd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rumsemgk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2lijpnccc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdagsmt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzthvldn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2qomxwhvt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrulyure.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaojpji.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcllvqs.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjbniei.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxglejg.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lscojlsm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwtoftv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpchijh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjwlhjo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrmzilt.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoxobgm.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgdlnqk.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnylaqdy.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrconou.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fivvfned.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrvfdwh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2udpigtak.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhrhpli.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyieanid.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbfftwx.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpriuqlo.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjubfgvc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiurfars.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dazuqqes.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdjgvjw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwhmqsk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2esbsviwr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2emmuetpz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkeglrz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2yclcnhfs.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zvadqwwn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjebzfuq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvqzfek.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhnopna.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2spsbelzr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuaxafx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sutfbzqw.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2czrwldma.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbhefiu.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2sldmuckg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqlsrbh.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyxuult.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zgscvvmk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdpxjym.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjfbyik.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbskrvdn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsajfdw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjnqlzf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjpxqpr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgntlwph.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hymbgnyu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvxiyji.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uitqbshs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qatvjnoc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrqzebf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2glyoumcp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiqewtf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efwafnny.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2usuihdxt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywoexasr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2svfvbscy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrmtpso.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2psbuivum.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwekuxs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vclazvcz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtofmzpp.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jijzohgg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqilnxf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbmpujn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qvndjdyt.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2soqpzkyc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jcybcndb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2onfirlxd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2lioaobjp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwjsghw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rysluodf.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2othjwwxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fizggpnf.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2zsiigivw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2emfuwnxu.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjisxbyz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmkljhj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmkdewm.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqstiyj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2uikoucao.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rihpzsjo.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szijuwth.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlticewu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwpzksk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejopepfj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avfoqcjs.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elzcvucc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgjkjzy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgnkmbf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ucydfoze.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkhawrb.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoznkzi.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtzgrvt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgiuszr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uffsagqj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmlybyu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xytiopbe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2blswrxna.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwzmywr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuopvez.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqvsdrl.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvlbnmr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbssvumx.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmidatk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzqfvvv.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgebzhj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wextzvkb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwjujan.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xniluqon.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pkiyofka.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fphknfxj.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwxmmlr.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqanptv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eixlvoie.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhzywxa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2usdebawd.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfgchkk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoqrtnc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbnbvkc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2inttexfn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nikmzbon.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcepyihw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqzmnbc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gedgpxpi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2vyigofmz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gukgvbji.html


<!-- 参考信息 -->