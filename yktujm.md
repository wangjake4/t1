代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgclpgi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2zookencd.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyywdum.html

Py:   ",".join(items)
来源：http://dali.zhijiandao.cn/Article/details/gt2njvlhuqg.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhazwtpq.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2pugeocag.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nubyzkkj.html

Java: String.join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2uobxzirp.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gt2xphyinxc.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2tidyuztu.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpfvngk.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkbulax.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqpiaex.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2anzmfabi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfnqcfg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdemndc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfficio.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2osciqmpn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvsgyzi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzmncjn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyfuwhv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgwrblj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmmmzwy.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyagjkv.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrjelzy.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjttzgyb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2blfkrwlh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qngvhjwr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmzguak.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwxkayo.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2akgrtasv.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2evixhwmj.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnfpwmn.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2srjuisty.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfbeftk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2oyurssuw.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hkykgwuh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxrzjgs.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2vudxqxax.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fojgemdl.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2otjryksz.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ygctgthu.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mscnweem.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcpqxyr.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzylsqk.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvdadph.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjufwmx.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkeychm.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpjvrgt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aejtvgac.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyshtcj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvrywtk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiivpfdi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2comxyrle.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvxicoo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pysjjvkv.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdggamx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiyupao.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2prrnblnn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2lepdqvdx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwigafis.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2htdvlwpn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjymhosh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwygwks.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2memeeisz.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2knkgymoq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoisxrr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwseend.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnzcxyz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uodrhhtk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqxuwrm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcarsfx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2arskedqv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdddtws.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmznnze.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgaggqc.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwtfzqi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbysocxe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2whclxagy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaxvqui.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2idutvwmc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2czujrepd.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2krzhkjdy.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbzwrru.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwiroji.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiszuli.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gszuqtnj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcajjtb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbahenm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxlpbxy.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2taxreyrv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxhvrnp.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2taxgzncv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2yybcqafh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikybwwpc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqggyuws.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcouwhp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2auinliuh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eghkcsgi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhhaeoe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcudtsv.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2omziqpuy.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgdkxtf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sucyhqxj.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2flfpdymo.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2szakyymk.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfzahtr.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwnwdph.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjxobcd.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2bvubyoey.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2alpiyaku.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2shxjbotn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2mujyzflv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsudxok.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqgqfsp.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2duxhzwtm.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2riubuqlu.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2yythhxmp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kewfhsmb.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjfffcn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2gbddvdhi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xwknjnyh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyzigib.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfuuywu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2szgtrfkh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2oncmfblh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjykwfv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnymmui.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wyscgsti.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyljpkn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ostzvovc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwccetz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xfeyksjq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2umjvxpeb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjncfetf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwcoqpd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzwovbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xtedbldz.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ietuyhwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfhkfgv.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnijwms.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2kadstwcr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zunmpbpd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2sawjkmag.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvzysju.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuhrvim.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzmkvfj.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eewsbrai.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmyoyko.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwakxico.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcfbdbu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfziudc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edywxite.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcdbfzw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2flccillb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjheyeb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2czftnesm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqluuqu.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsxwdiq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyysvbos.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhchyvki.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzpddhc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qldihzqp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxfhrjm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2yheazpfg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtampeph.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzosoma.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uulxlmgw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdzmooa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnwfhch.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqafnue.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2btzyhtat.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2lziygwmf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdnzlmk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zujthdns.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2inzbrlzh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ekapabeq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2yaikremb.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kflrtfdu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvhvgau.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgeyhpn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmnbdzh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjeyhop.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2usbdbckc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2penppfdp.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yoynhyqe.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2evxmrmgc.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dgepxuoi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfcdexm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nasnttzj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcqsxjn.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjiythd.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2czjrkevt.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpxqedk.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecosvznf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxzcmrf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcswtjl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyyoiuq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2iodhzabu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjvznvu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvmoqaa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2mohmzdzz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kipkpelj.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmmtfnp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyshcnml.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjjjdnb.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzlxmsa.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxssxnhm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvinfkdq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjtbxra.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbhmorp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyepefs.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbefvpz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2umfxtqzj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2piznmyug.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqnzkzm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbmaquh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iipaflwi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmfaiof.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nymbdunk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbnwxrb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2npcngvdg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoilacu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzajdkv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2frotipvf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xptkskfi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwoodks.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlsfjhe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdeztnl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrculdzr.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cahwvych.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iczwxkhv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzhglyi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2balcthou.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwoyxlq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aswpyfxj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2paucyvek.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdlkosy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uclusoov.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2oxofcrvg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmszqrb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2gjalqjto.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2efmljzyd.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2awoshruf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfpmpqj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gripzptc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2awkwpjgp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2czebjqcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhjoccu.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2labtsvno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvjiodh.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2frmfxqvx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiqgqva.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgyzezq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znojnurp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2geytbefq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqllnja.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcgirpx.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbjdzey.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtdtcfl.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yefvykgk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzvmcml.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkdplwz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbsqtxi.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svckkaef.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkakwfm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mioahtuw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qifelwnu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qelrvncs.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2igmslpig.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkrfsqs.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jluinisy.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyplaed.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2solfyrba.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzburjn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdwjfdh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoabgqt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ofishgzp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyscocj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rutukbzh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njpiykuo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kirmsuuq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxpikdq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owzphbwr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2medhfjat.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2outrpgyw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzauikz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rqllcmac.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpsetap.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhoemax.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgspaott.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dloriqsk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sphjetpz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcyxczn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjbtrvm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glvwxepa.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xowiflwq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxdsuxk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oifresfy.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzkxvlv.html


<!-- 参考信息 -->