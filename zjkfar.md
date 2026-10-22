代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.xylfe.cn/Article/details/gtlwixcbth.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtmrtpfmqw.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtprnavncy.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtboyobuja.html

Go:   strings.Join(items, ",")
来源：http://dali.kuanghao11.cn/Article/details/gtwkobfbqy.html

Ruby: items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtliibmful.html

C#:   string.Join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtjoajuvqb.html

[E09] 去除所有空白字符
来源：http://dali.gzhubu.top/Article/details/gtihupdokc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtgvxbfexp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aizwys.cn/Article/details/gtrfgdlszd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtblfmalbe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtausqocmw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gtyggqrvov.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nwbrower.top/Article/details/gtbhplifgo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gtbxhrdprw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtioxvzucs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gtvbovhmwk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbhmxbxr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yongpay.top/Article/details/gtigtyfcme.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gttkmzzwsh.html

TS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtpcbgxqwv.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtfszhnloy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gtewvwptxq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtouxraxsm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gtobndizdm.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gtqjlemxxs.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gtfljkezbq.html

PHP:  strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtjqnisqou.html

JS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtfwvermpv.html

TS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtjdlprkfp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangdashe.top/Article/details/gtoncsnatv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtbwmxebia.html

Ruby: s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtrpcjrnqb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtbotptfho.html

[E12] 统计某字符出现次数
来源：http://dali.ybcxt.top/Article/details/gtqjiwhica.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gthjtlopos.html

PHP:  substr_count($s, "a");
来源：http://dali.chenlongwang.top/Article/details/gtscxzhuif.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gtbmrfjrpz.html

TS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gtvzftjhbe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gtjdlkfkmv.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvtecruq.html

Ruby: s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxafdgszw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gtqkkeonmw.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gtjijiszyc.html

Py:   for ch in s: print(ch)
来源：http://dali.zhoulong.xyz/Article/details/gtoyxzghhn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gtghhfsemy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtvxcvvqaf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gttqpqyicd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gttrizonny.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhengqikj.top/Article/details/gthjpcntkj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gtqvvmigcx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gtglzfdktb.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gtdbmffmrl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gttcizwnzp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gtujndtbgf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaofxxrvw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gtkyfkvdmh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gttklpvtqi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuxming.cn/Article/details/gtujibpcdi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigfzy.top/Article/details/gthalwsars.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuxming.cn/Article/details/gtzbvvqmwb.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gtijkduwzg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gtqqvsbyii.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtzjhcaehe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.kuanghao11.cn/Article/details/gtztjrvtit.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.smart0.xyz/Article/details/gtwxzcuxtd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gtqeppfvpo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tian-w.cn/Article/details/gtchtixdgn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gtxjowztvx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.mhx1999.top/Article/details/gtkwysdtqg.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtxdaornfr.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gtcakunsbn.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gttptoukkj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtqtsayknk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtcjdfcuky.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gtyksodxnk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gtuspcaqxv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuosdnhd.html

C#:   1234567.ToString("N0")
来源：http://dali.quarkkingdee.top/Article/details/gtlzlawttd.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gtagowraev.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gtmusyzcrt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sysykeji.top/Article/details/gtlkmcsyai.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gthnwhnuyd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gthhuzdeck.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gthfmgmexw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cqqwz.cn/Article/details/gtxebmfwsp.html

Ruby: s.capitalize
来源：http://dali.wangdashe.top/Article/details/gtgiaobeyx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gtnfpsqzfu.html

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gtdfzigvgi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gtgfztdhnw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gtfgqzecdn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstyjbyaz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtcvuhlccf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gttlrejmrt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gtrakmobhn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gtputiemni.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppynlaru.html

[E19] 多行文本按行拆分
来源：http://dali.ivvv.top/Article/details/gtzgvryjvg.html

Py:   s.splitlines()
来源：http://dali.yvedp.cn/Article/details/gtoqgeaygk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtcutastiw.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gtfhgfukpd.html

TS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcykzrceu.html

Java: s.lines().toList()
来源：http://dali.zhengqikj.top/Article/details/gttbikwfeh.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gtsrfkasfb.html

Ruby: s.lines
来源：http://dali.andypj.xyz/Article/details/gtadoajgde.html

C#:   s.Split('\n')
来源：http://dali.pycfn.com/Article/details/gtxurcifna.html

[E20] 判断字符串是否为空
来源：http://dali.cucudq.cn/Article/details/gtslxadlse.html

Py:   if not s:
来源：http://dali.aizwys.cn/Article/details/gtuclkqggt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gtromixums.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gtkulxusqn.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gtqtefcqyh.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtwnbxpffr.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtkpwevsll.html

Ruby: if s.empty?
来源：http://dali.hysaishi.cn/Article/details/gtbwftvhuz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gtzvdanmys.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gtzgytgeng.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yongpay.top/Article/details/gtjxjpaayk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtzcunrpeq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtqdseudhb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtnnirbjph.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtvhsjimrm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.svipenyu.cn/Article/details/gtwcuauvgr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gthwnwkzho.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtavcotvwk.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gtyyqnkurw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnxiangtu.top/Article/details/gtedoqodjh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtspyxrgtz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtbqucfeaw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtrjdxowia.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtkhnggtwn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cucudq.cn/Article/details/gtcgilaebn.html

Ruby: s.bytesize;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtlwumpazo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqbwcfad.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjdnkvox.html

F. 文件与目录
来源：http://dali.zhixingplan.top/Article/details/gtwksznjga.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtxjnpmmnl.html

[F01] 读取整个文件
来源：http://dali.tianlin.xyz/Article/details/gtsxmgxqzn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gtyxbtcqwe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkgobgkk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xinyue.icu/Article/details/gtyjwpgatd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtijrdkyfx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtipdohfgz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fengsongda.top/Article/details/gtdngkwcym.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtiqatapao.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtdxjnyrjt.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gtqiqpuvgz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jlsjyb.cn/Article/details/gtgaguwzdk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jlsjyb.cn/Article/details/gtrbnmbbeh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtshrhyzra.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gtizozxcld.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtusmqsqfn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aizwys.cn/Article/details/gttwqzfjch.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dianchejie.cn/Article/details/gtjytwmtaq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gtaxpdvxrk.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gtikpnmfwr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtakgdgimq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtgzqssxpj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtpoyrmrfm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtvpcaecai.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gttdyduetb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yueranfly.top/Article/details/gtackipxvf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtmvhesvmd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtozbkyuzy.html

[F04] 追加写入文件
来源：http://dali.xinyue.icu/Article/details/gtwdybavkq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gtolngcyus.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dianchejie.cn/Article/details/gtbzgrekrb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtjhapvjij.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhmbtcxt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gtebmfcoql.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gtvdngupou.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gtspyydngl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuxming.cn/Article/details/gtxtsrbnib.html

[F05] 判断文件或目录是否存在
来源：http://dali.yangfankeji.com/Article/details/gtbepsfxmx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gtcheqnrdt.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtpyrzmuwz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtvekebqlw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtljftidzv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtrxcfjnsb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gtpfkhtzxg.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gttlbnapne.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtdrotnijc.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gttnlmncaz.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhkmkevv.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtrfdotslj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxfidaks.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtzjasaogp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtpuwkxrpf.html

Go:   os.Remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtbaxzudjk.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtobrsdvgi.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtdrjozmss.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gtthurhtbt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gticabidjb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtfazglvmz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gthpnezwhl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtsgzfebkc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gtvqwmnhoq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gtzctwbplb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktjufrwn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gtpsrrufon.html

[F08] 遍历目录
来源：http://dali.birdmap.top/Article/details/gtdsespopu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxuanxn.top/Article/details/gtmhqfdgti.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqdpjeml.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtsumkgclr.html

TS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtdgfmeupi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtiiwekpoh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gtzuzanovc.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtqfxqirth.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gtclvzozfe.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gtuqwgdrlf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtvllfshql.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtcsbjlxdt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gtskihtgde.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtguvcdvew.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtckqmyiwa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gtynsjwydp.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtuisbhrno.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtmzejfgkn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gtysoohwky.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtgrapeocw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yongpay.top/Article/details/gtlpbvbshu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtdibosdtx.html

TS:   path.extname("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtccatvgcz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gtzarithol.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtvyegymmy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtkdvaqdct.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtuopqqwlv.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gtqtcruyna.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtmitqkjjx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.smart0.xyz/Article/details/gthwieqhvk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxrvsalah.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gteoneynot.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yonumen.top/Article/details/gtiftrwcua.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtfnpoklam.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtnrshwgnd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ppjwa.cn/Article/details/gtsparnwae.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gtycpdipwu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pycfn.com/Article/details/gtblkpnzhw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sysykeji.top/Article/details/gtdyyokwyj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gtfghtiqow.html

TS:   // 同上
来源：http://dali.jlsjyb.cn/Article/details/gtfodwovqy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj202588.top/Article/details/gtanrocrra.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gtjykwtmgn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gtvjgmslzm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hfpthk.cn/Article/details/gtcpopjpwn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtutasdsob.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gtktndvjfh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtrrccwfbu.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdiqsvxhw.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gtaayfszgl.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gtirzgmoiq.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxviutvcq.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gtadsfqmpu.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gtlmoldsri.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gtzdceyikt.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtmjqfalnm.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtveapueec.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gticacjmzw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gtwwttvpik.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtqvtwucfe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtiefwjkvn.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gtqmrfmhje.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtiuelgqwh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gtkqwaexgf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gtescpzvvl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gtjkammbah.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gtssagesnc.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtaaznzeip.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtoyysxqtl.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gtolgznuge.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gtiskbdmbl.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gtvijbbtkl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtudpiusob.html

Ruby: @name = "x"
来源：http://dali.pycfn.com/Article/details/gtwvneuhrm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtlvsyydvk.html

[G04] 定义方法
来源：http://dali.9152youxi.cn/Article/details/gtisemmhfy.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtefdvelrv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtgmvclkxv.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtghknbnet.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgccroemh.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtguuokolu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtehoblqtb.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtljobwxzy.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtcdlxosnm.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gtwatueemk.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtdbvrhhem.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtjjqevbuf.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtmwcdwfhb.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzshistey.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gttdapyhdu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gtgprviwry.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrztxgvnu.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gtrfcrhfpw.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gtaycerhqg.html

Py:   def greet(self): return "admin"
来源：http://dali.cheryme.top/Article/details/gtxnrhhyvy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtmkmibdjk.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtqmgcfzfx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtdfrklumj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtbqcllfic.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jlsjyb.cn/Article/details/gtornyqlns.html

Ruby: def greet; "admin"; end
来源：http://dali.chenlongwang.top/Article/details/gtczcgadfw.html


<!-- 参考信息 -->