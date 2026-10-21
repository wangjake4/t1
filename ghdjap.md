代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gtoidbhimb.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtnstvchks.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtnmcurxng.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgpbedfv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gtecpkbivx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenzaomai.com/Article/details/gtfyzhcgck.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtpjvulxcq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtavdazzpn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtbnrxlclf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gtgpswtecl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258.top/Article/details/gtrjorugek.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzemribyg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nwbrower.top/Article/details/gtrvlaorss.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtdqlehoyz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hysaishi.cn/Article/details/gtqwrjaijw.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhupmsbq.html

TS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtpfwareqf.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtmwjhtziw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtldtnnfph.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtayelzjbc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gtwliwifje.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtfjybowop.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtfjikewpb.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gtkwgmwksl.html

JS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtgiilpawz.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtwcnbalau.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.haohaochexian.top/Article/details/gttwrwoobw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sxryk.cn/Article/details/gthseomdmw.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gttdpoxvsr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gtawkldugk.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gtavyrzjuy.html

Py:   s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzkuhuqd.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gtepxoreex.html

JS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtuceraqxr.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtmozuuigo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gtuokaevcg.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtigxdnvht.html

Ruby: s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gttatagcqq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gtluqvtaql.html

[E13] 逐字符遍历
来源：http://dali.snrcjt.cn/Article/details/gtoflbljwi.html

Py:   for ch in s: print(ch)
来源：http://dali.c1oappe.top/Article/details/gteoqvloub.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gthtnrxdvt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtwgjbmder.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gtrdqjeqju.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtsgruuhvx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtywjstdbg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aibaodan.cn/Article/details/gtwerifmmw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guannengcc.top/Article/details/gtuifuykcm.html

[E14] URL 编码与 Base64
来源：http://dali.zhixingplan.top/Article/details/gturmmxvwf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.feifeiyinyue.top/Article/details/gtcavvzqss.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangdashe.top/Article/details/gtnnxvjauk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gaohongyu789.top/Article/details/gteerluykp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtwmszbjza.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daria6918.cn/Article/details/gtbzeiqhyq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gtuijikcbr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cheryme.top/Article/details/gtcohecgdm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtjplspbgz.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gtqkmfdkbr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.snrcjt.cn/Article/details/gtzbobkjjh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.meibo888.top/Article/details/gtrtkfeawm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jlsjyb.cn/Article/details/gtnddpcguc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtheemuscn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gtktoqxvtx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtieynpbtx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.snrcjt.cn/Article/details/gtismxjgvv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gtpglwjuut.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtgpchvrai.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gtzvibafsx.html

PHP:  number_format(1234567);
来源：http://dali.yj20258888.top/Article/details/gtpmrtofvo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gtetzytmgs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtpybehfyf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gtuyepjtkg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtdznnntyz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gtqyrhwsyy.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gtjrbncqym.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gtnjbzdguv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cashguo.top/Article/details/gtxeibbqpi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj202588.top/Article/details/gtbkzthnmh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtlmipgzmc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtdeoiahpi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gtfhsgygow.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gtpeoptfyi.html

Ruby: s.capitalize
来源：http://dali.wangshuangyany.cn/Article/details/gtfzmcppzu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangtech.top/Article/details/gtjufnnktq.html

[E18] 模板占位符替换
来源：http://dali.xinyue.icu/Article/details/gtarfdrsis.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gthaetsryj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gtwnycmwmt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gthrqmzhdi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtkdiapelz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtrexhyspc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtvkfzoawh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.c1oappe.top/Article/details/gtxcqbkflr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gtboreyzlm.html

[E19] 多行文本按行拆分
来源：http://dali.shzxlz.cn/Article/details/gttnjiixai.html

Py:   s.splitlines()
来源：http://dali.jlsjyb.cn/Article/details/gtxffpfqjr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sysykeji.top/Article/details/gtxagzmtlp.html

JS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtledpqzrf.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtasxkdxct.html

Java: s.lines().toList()
来源：http://dali.smart0.xyz/Article/details/gtbuuooqra.html

Go:   strings.Split(s, "\n")
来源：http://dali.ppjwa.cn/Article/details/gtxperfsyk.html

Ruby: s.lines
来源：http://dali.wangshuangyany.cn/Article/details/gtougwlmdh.html

C#:   s.Split('\n')
来源：http://dali.shzxlz.cn/Article/details/gtimewgnhv.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangtech.top/Article/details/gtisomagyp.html

Py:   if not s:
来源：http://dali.hongshengwenyu.top/Article/details/gtmmnbjnoo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hammf.cn/Article/details/gtjiephiih.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zycfv.cn/Article/details/gtgwqseepq.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gtadjvuavb.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtmlqcnhjg.html

Go:   if s == "" {}
来源：http://dali.hywenlv.cn/Article/details/gtniospphq.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gtniosivot.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sufxvd.cn/Article/details/gtmxeqdbkz.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gttqqezrsb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gtplzapvej.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtqfxjznze.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtnxtbdvpc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtwbowwocj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtxqphghro.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gtiiypgxwf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtztayurli.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtussbipns.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gtpkuhufzc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gthignxyto.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtyxdgiznb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtptgbwkjf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtmpdyzdcj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtvheyxdda.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gtfaerdezn.html

Ruby: s.bytesize;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtbtigzmjk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtflryqcnz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtlgbizebv.html

F. 文件与目录
来源：http://dali.daria6918.cn/Article/details/gtczaiyrro.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttvahnejj.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gtgheqodyl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gtzosuakrg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cashguo.top/Article/details/gtemfzxnuo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.mhx1999.top/Article/details/gtrncpeoay.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtqjrblgby.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gttlmrjocg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gtrjoocyug.html

Ruby: File.read("a.txt")
来源：http://dali.yongpay.top/Article/details/gtpqqdljzi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtxvzrkhxv.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gtkmkjipil.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shangyingyoupin.top/Article/details/gtscegtbkv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgfzy.top/Article/details/gtabxqrqjz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtqrghccpf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtjllxljms.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtrllvmifm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.quarkkingdee.top/Article/details/gtygleztze.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtwhmridtj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gtyogokumg.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gtflcygysx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gtmbwolmag.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtrhxsygjz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtwrpdjlwc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtzipvowcz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gotoacloud.top/Article/details/gtkxatrnpr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jlsjyb.cn/Article/details/gtkgfibaif.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gtzcbkypij.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gttankjzow.html

[F04] 追加写入文件
来源：http://dali.jqgfzy.top/Article/details/gtadcnpgzg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.meibo888.top/Article/details/gtsfajtmkj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhongyouzk.top/Article/details/gtutrvgdnx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtebhggmym.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtvuuguhjy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gtiiiqdsmd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gtmpxkzdna.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yueranfly.top/Article/details/gtosrqxzaa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gtimcqweer.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gtxzmpgnpb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258.top/Article/details/gthbglqjil.html

PHP:  file_exists("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhkszfzm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtgrlpxhkj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtrysxvmgm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtbsrafyhh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gtqhxpqqtk.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtdplmrwmn.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtmubtbxen.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gtypfjreki.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtktdjwjtm.html

PHP:  unlink("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtuubvulka.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtiomqoxfk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtajcttfac.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtvyzmjctg.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtkckdztxy.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrdslqzp.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtbrhlniye.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gtfxxaiwfm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtmxkpkdan.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gtaavyogtx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtilrssemp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtscythgfs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gtytrfxgvh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzlofzae.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuxming.cn/Article/details/gthfncgsgr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sweek.top/Article/details/gtikjytsgs.html

[F08] 遍历目录
来源：http://dali.aizwys.cn/Article/details/gtfoeeujlf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gtigniokon.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gtnyiygjuw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtksmtwibz.html

TS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtzafwnwnr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtqvjtcjpb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gtbeopwxqu.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gtmppyezum.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yangfankeji.com/Article/details/gtuvhkcnpr.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtsqjeebpl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtrhuqynyb.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtqfveylcp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtucubeyxs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtwuwirswg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtznilrjnj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gtuldtpyit.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtqvxsratv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gtcizeiitu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gtjkiacyeb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtleglekdv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtiaypysij.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtmgdvytsz.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gttuayxwcj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gtllrvcwcw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtwliacmxl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtjwrqqkth.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtqkqsexxo.html

[F11] 复制与移动文件
来源：http://dali.yonumen.top/Article/details/gtnfbamugo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtmupefltc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gtzjzjtmnx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtoblztmxf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtrxzcraei.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtblhnvt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gtcfwrewhw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gthhukpydg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtvqafzgfr.html

[F12] CSV 读写
来源：http://dali.cucudq.cn/Article/details/gtdqzbpzio.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtfdiokjhx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.9152youxi.cn/Article/details/gtnepkyhsy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfwhhqoy.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gtqeubpyqh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cucudq.cn/Article/details/gtffatohqd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gtqftqkjob.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.0kj1m.cn/Article/details/gtvlarolww.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gtkinqhlqf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtncpdstmi.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gtjwghrldh.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtqlppqoun.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gtuhwhdjhc.html

Py:   class User: pass
来源：http://dali.dianchejie.cn/Article/details/gtqwxsnwbw.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gtagbfjvbd.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtjeyhvqdt.html

TS:   class User { name: string = ""; }
来源：http://dali.vqdsnc.cn/Article/details/gtnvvfklxy.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gtovdwytex.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gtrzyaooge.html

Ruby: class User; end
来源：http://dali.daria6918.cn/Article/details/gtnypzedxu.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtwkoqewxk.html

[G02] 构造函数
来源：http://dali.mhx1999.top/Article/details/gtnraigcuq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtcxbmsbic.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvgqztudu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtgbjbfjai.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gtqwkfsnyu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtocybpoin.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gtbfosamje.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.9152youxi.cn/Article/details/gtyvdkjngf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xinyue.icu/Article/details/gtumqwzuhp.html

[G03] 实例属性
来源：http://dali.mhx1999.top/Article/details/gtuvfesrsk.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtzlegnzby.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtveudsskn.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtoxrrbtfy.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gthhbxpwvb.html

Java: private String name;
来源：http://dali.shangyingyoupin.top/Article/details/gtedeebgdx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgaxchsv.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtxyczlslg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlcnpxmq.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gtflhbsvwp.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtypegldwy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtzobpfjwz.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtmhlkyakx.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gthggwmpqm.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtccclzjrs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtfxspwemd.html

Ruby: def greet; @name; end
来源：http://dali.smart0.xyz/Article/details/gthwikthgk.html

C#:   public string Greet() => Name;
来源：http://dali.guowangkeji.top/Article/details/gtshuckbbs.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gthjivlrne.html

Py:   class Admin(User): pass
来源：http://dali.cheryme.top/Article/details/gtexawsmgi.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtisgaurqw.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtcuxudalk.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtteylywnu.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtdfbiwopi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gtnwikecie.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gttqlbekoe.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzibeqimt.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gtuizhkfos.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gtnozhnyyd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtnaoiurkz.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gttxmgujpg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgkosowaz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gttpmunava.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtwwbgonxq.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gthfhvqwtu.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtkqbptdya.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gtzeaqland.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gtmprwtsvh.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gttonuahoj.html


<!-- 参考信息 -->