代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkrhzka.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwqhrkw.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeihgbw.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxozrlzg.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhetzky.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzczlvmb.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpdhhvr.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzlmbdv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhugambk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoqyrmg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqhgfzx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkybofca.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcalczo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pychqglp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2guqnzrfz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbkermh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2gipbjsvd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdieaukj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2yughhhtr.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lszsfoqk.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrxbeyx.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2kymwhrfo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhvqyfa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwvrnlz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvfkjtw.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rvctubjf.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xoktgzyp.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaahhrfc.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkisjos.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2earcbnxf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2swphtedy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpkvdqe.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2avvhdzvx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsjkmog.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmhtyrj.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnrwgvt.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuvrycd.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zubrameh.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pjicdfya.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhbuhup.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jighgobp.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2cciaehqo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2oltdbnkr.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkyszzb.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2kawgwzfm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djgptywl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxlqxvu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdupakfk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2naphfsru.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gqndxcwx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2gribzjbx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nevbwsob.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2pfolzndm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnnqbfy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryugipmn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2shovbhmc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdphervl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoptxbu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2itlslnhw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fflqwcwn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2skfjjyod.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2hpimclmq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxadjcz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwivfczj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhthuoa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2coyatmgp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2fkoqgeld.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhiqufr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sthyvotd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkjouuk.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2nenmshdu.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmxmheg.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsgiinx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdgrhvq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiaexwn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2clhoyxfr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lpobsuyf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpitbch.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xormqaoy.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuienak.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdxfzpb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2moajrpmb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgjeuuu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmfyeep.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqsczhn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpynqbz.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxzthiy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfkdmle.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyvnhjq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqvmbkf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmjkdge.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyhgrgr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhzwaps.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2okyqomzo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrrmddi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgmkcvq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyusuzzl.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2itxymqfy.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkntnvt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhsljvu.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejolbhev.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqqpqee.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2roplygmy.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2obeqyniz.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxelkjq.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2uwabvjkc.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2igrhvcwf.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwbpnbs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2brnwyuwd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzftcug.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnbyglz.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tryqqqam.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxahcfw.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbdpncv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyslmkdl.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxhhxrc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvdekvm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2akujbzko.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gfghmrfq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2agvyqvsl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoifzrd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2aloqozmj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2onmfwgjw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2npnvlurk.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwlewnt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2snznqwxo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2heyvzhye.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dscmozzu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbfqdwz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvrhkdb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2eiatwpjd.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2colbquhj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwzqqos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbkiuzf.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtrnduz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2reawgcil.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoxdiai.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcdgchi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqumzxn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2fuauzaht.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxuawlg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdpjxmx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2wrowzixa.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqhukqc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2udwanooe.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bagmhdup.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhieitf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmumstcn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxkrbmk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avbtiyxz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qowkbakp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnspxyuf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfpzynb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cortbgrj.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2azxmxpbn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gszmuqvc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2derehbns.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfrtpnm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmvwmpi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmcwotp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2okzkjibv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2niuqxhfk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2feppehho.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igahtovc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkbmvev.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdmytbv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgfetmo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhlvmth.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmechcek.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2egpnitzd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsjxpnm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqmpxua.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2urvxznkd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2yontfutt.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pllketzv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znftzfqf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmogdfa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcavydo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiekrur.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2klbzmasp.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2amrhbrrq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pribnakc.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2firmpxdg.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssprapbk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sysgxxvv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyxjhpf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqnjouk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2urzdyxzq.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqumifyt.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvqzxcx.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzbolqf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxwoesg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tguoznax.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tujriout.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ufisxojr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwjtxvp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuedwltz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhxjgxp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnkewkf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwjqgox.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxosqxl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpafzzs.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxykcsw.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcasbeic.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvmswaz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2phcguvhv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aayenivb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpnuswf.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrvlkpf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2illmbyyg.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2csnndupj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vsippjmb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnbkmuz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2burgfzdu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2emmsgunj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyccpnxa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2drxerbub.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2fiikergm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aixiarza.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xojbmhvf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnugdjg.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2secwjgqh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwdnwdp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqqnqnj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgqodvg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxrcytq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfavywsd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmtmpvs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvedwes.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrrmtuj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywecxywt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lthhzdkj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvjmwlc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjhbwjq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2szdgmtmp.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2whdwboyd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeingsrx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjnomwp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dhafknna.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2eddexoyp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdrbluu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlnqrpj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbmlkem.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbxzoex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2seixxsju.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mpujmfsu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tozndvpi.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmgcqhp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2htadypwq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmytyqy.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfkadzm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wobuarsa.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2saezqmmp.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsprazcl.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2libeyinq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcklfeq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbenelad.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmghaaa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqlfyou.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcarwsyr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olxbhibh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjplkwtr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbkmpzv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwyntnw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpedlqc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrbsxig.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbkpkhv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhkomqc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tyejlbsk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpgfsca.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmthkep.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mraqxjhm.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqdxbsv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzrljmj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmbdzcp.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sddfundi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahixrpgg.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbkorki.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvslgwar.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruukwsrv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2djyzvznf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxwddjr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlnhwnk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyiyaxo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzibcse.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kilniobu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhblhxt.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enucglgo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqwckuo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vekjvxan.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oldxnmjq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubljyutc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsgmgel.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2xawgqfdo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxnkiwp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vljbfpqk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tliwhdle.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmfwpju.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2rfygazhu.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnqklzi.html


<!-- 参考信息 -->