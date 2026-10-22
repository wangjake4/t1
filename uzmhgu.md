代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtdfirtjfa.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gtpzguxhwg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.kuanghao11.cn/Article/details/gtqwccuxhe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.bjfxy.top/Article/details/gthpymxfba.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.9152youxi.cn/Article/details/gtfuxxxzre.html

TS:   s.split(",")
来源：http://dali.bjfxy.top/Article/details/gtcpwcfpmb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.mhx1999.top/Article/details/gtyammudkh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gtvkgwdwsg.html

Ruby: s.split(",");  s.split
来源：http://dali.gogol.net.cn/Article/details/gtsjxanddq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gtxawmyzhj.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258888.top/Article/details/gtdrjrgttu.html

Py:   ",".join(items)
来源：http://dali.hnxiangtu.top/Article/details/gtcyxardru.html

PHP:  implode(",", $items);
来源：http://dali.vqdsnc.cn/Article/details/gtmtwtwqeo.html

JS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtihdlkokx.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtjpsysinh.html

Java: String.join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtqmpymsgs.html

Go:   strings.Join(items, ",")
来源：http://dali.zycfv.cn/Article/details/gtekqnbgzr.html

Ruby: items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtixhakkhd.html

C#:   string.Join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtupliflaj.html

[E09] 去除所有空白字符
来源：http://dali.jlsjyb.cn/Article/details/gtkekpnbvm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cheryme.top/Article/details/gtavftorjk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.bjfxy.top/Article/details/gtebyneqgu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gthwnxmhru.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtgxntnawj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gtftsmjpbi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cheryme.top/Article/details/gtzpowvvqn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuxming.cn/Article/details/gtiakiqwfv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtdanexdtr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guannengcc.top/Article/details/gtusxlooth.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtpyrligzf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.iojbl.cn/Article/details/gtolxtzzeb.html

JS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtbvhmnexp.html

TS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtqkuxicrw.html

Java: String.format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtbopurbwr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtcnrlnjup.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtxabuycgo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.bjfxy.top/Article/details/gtrczkvbme.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gtxjgutimv.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gtpycscdtk.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmfohqub.html

JS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gthvisfacj.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtabpjjvqp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gtgdyylzrh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtawpixjcu.html

Ruby: s.reverse
来源：http://dali.gzhubu.top/Article/details/gtantimayb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtlwgtwqlm.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gtvdpifviq.html

Py:   s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtrurxvnur.html

PHP:  substr_count($s, "a");
来源：http://dali.jlsjyb.cn/Article/details/gttcmcsfgh.html

JS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtlvzvdzqa.html

TS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gtzhteuvgx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gtvnrnmctr.html

Go:   strings.Count(s, "a")
来源：http://dali.gaohongyu789.top/Article/details/gtvedwclhw.html

Ruby: s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gtvoawocod.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gtgegtikwn.html

[E13] 逐字符遍历
来源：http://dali.mhx1999.top/Article/details/gtqeoypirv.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gtrlvwodqb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gtdozegkca.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibdojptp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtgdvrilgz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtggwrhzxl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtzaymmsuv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gtziyqsyvt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gtasgtoffy.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gtokdsexgf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hysaishi.cn/Article/details/gtmzollmkf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gogol.net.cn/Article/details/gtngnvxecq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gtxfnjqvgk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gtiaobkikr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoddntfrs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.iojbl.cn/Article/details/gtbpvgeciz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gtdkfuxkpg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtqzgcpaqn.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gtcdrtcfrl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gtcuntymvh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fzhhl.top/Article/details/gtocycyofy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gtubtwjnfn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gtjrxnlovm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gtwchtprkk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.bjfxy.top/Article/details/gtmsralbck.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jiagoushi.top/Article/details/gtqvdozvbf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gtzvmtbgpf.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhaurcdv.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gtykdohxlp.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gtoyajlfgi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gttqmtoilt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtazzbunng.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gtrhoomjnq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gtfeplcpmc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gtdrjzbuen.html

C#:   1234567.ToString("N0")
来源：http://dali.ehwqpu.com/Article/details/gtvbxpcddk.html

[E17] 首字母大写
来源：http://dali.yonumen.top/Article/details/gtkgcbesfz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhongyouzk.top/Article/details/gtrhelnypg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gtosjftejb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtgubzglam.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jiagoushi.top/Article/details/gtrvzxjoem.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gtssxavlpq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gtfxykqcrp.html

Ruby: s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtuycmkxrp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgfzy.top/Article/details/gtmfevfliz.html

[E18] 模板占位符替换
来源：http://dali.smart0.xyz/Article/details/gtwdkyltoe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gtprfwcynv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shzxlz.cn/Article/details/gtfcaoesvr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtqzjsqmis.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtnfurfcuy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtkjpslnxs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtwgrcpucn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gtolbivhpw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gttmxddvrz.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gtjkmapcid.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gtegsvhrrw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtihgnawjw.html

JS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtvkfutioo.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gtaivdyqut.html

Java: s.lines().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmdqjrpd.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgufenzy.top/Article/details/gtmgeknobj.html

Ruby: s.lines
来源：http://dali.xziqi.cn/Article/details/gtaifxppur.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gtqzyjjuqr.html

[E20] 判断字符串是否为空
来源：http://dali.nwbrower.top/Article/details/gtjtuacxam.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gtqfhemqgm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gtylwmpcpb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gtbmaoafcn.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gtzpeqwrgg.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gtyqzynmwk.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtckianqbl.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gtwrgzdcgj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tianlin.xyz/Article/details/gtzierutek.html

[E21] 超长截断加省略号
来源：http://dali.mhx1999.top/Article/details/gtgrolqzwn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gtrissyfaw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gticpxbbsr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtcxyxvpqe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtsqqgmwpn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtedvhuzpq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hysaishi.cn/Article/details/gtdajiekep.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtbmcrllcv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtbbjregpb.html

[E22] 字节长度与字符长度
来源：http://dali.dashuyun.cn/Article/details/gtlzbzvlvo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgufenzy.top/Article/details/gtpavvhblg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtiiwtfhol.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtcadqyjdm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtsdmzvfiq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtxiujubxr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aibaodan.cn/Article/details/gtnyitzped.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtlufwjrkx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtwplcvckp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrbkmthdl.html

F. 文件与目录
来源：http://dali.dianchejie.cn/Article/details/gtnnvwqkae.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtjoefrgyp.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gtsdkvwxmw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gtzpoulaso.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtrvyyagww.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.iojbl.cn/Article/details/gtmujyhekl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtjjybddrt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtlkkzxeie.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gtkdiuaqfd.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtpvollxpe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtdusgfccz.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gtouucagwg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gtjgbhyctg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtzcbdtdmt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtrtizwsuk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtxwyauuww.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtrkfjkroe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gthqvyzftk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrisepdl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gtcbaoxscr.html

[F03] 写入文件（覆盖）
来源：http://dali.jlsjyb.cn/Article/details/gtchfjjrvc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daria6918.cn/Article/details/gthnwcjsmo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtaehsdpsz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtkbvxsexi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtxlcybupc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gtbyisdluf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.mhx1999.top/Article/details/gtnwixtzzk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtvgsvqfsx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbvfapew.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gtvnyfqmbl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gtmvzpgmho.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gtazhkgahw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtvylaqgtq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gtibcagcjy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gtcuomnfcf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.svipenyu.cn/Article/details/gttrjqjwiz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj202588.top/Article/details/gtcicvnady.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gtzxgqvrlt.html

[F05] 判断文件或目录是否存在
来源：http://dali.hammf.cn/Article/details/gtxslvbwil.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gtuslqnxkl.html

PHP:  file_exists("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtwbgasrtx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtqrnsqjfc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtaxqargrj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtkylrqohv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgufenzy.top/Article/details/gtdocmuclc.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrxbuxxs.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtuauuhmty.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gtydjypxab.html

Py:   os.remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtyxflqatk.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gtseflhidf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtocuxagfh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtfikpacfi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtcridukee.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gthcpcepwo.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtikmutdte.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gtpfwwyokq.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gtuhyrotsd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtgwdzhkff.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekcmunvk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtgswceubt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtyxsgqpxd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zycfv.cn/Article/details/gtssufgwcy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gtscmtrpwa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cqqwz.cn/Article/details/gtqmmuhkhu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenzaomai.com/Article/details/gtedohjuws.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gtodfnucvp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ydzc1.top/Article/details/gtslepnstn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guowangkeji.top/Article/details/gtyqikhseq.html

JS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtklddogak.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtxtwkgcxd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtwdecoyff.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gtnjzlucqx.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gtlxpmrynr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gtpacsqrhu.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtrvnqwfyo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtyowxrhgc.html

PHP:  filesize("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtjxlwmjat.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtntwetbej.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtxptgkgwc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtzztfwdfp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtzmppgjzc.html

Ruby: File.size("a.txt")
来源：http://dali.meibo888.top/Article/details/gtkwfhgxrt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fengsongda.top/Article/details/gtyqaveezc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gtkcfkynlt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtfhhjrdou.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtyycjyfzo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gteimgdfxx.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtdnhaqrby.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yanxiufei.cn/Article/details/gtmneupuxu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gttsiaiujb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtgemzmhsf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtskbskbhr.html

[F11] 复制与移动文件
来源：http://dali.zhixingplan.top/Article/details/gtzydoccwe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtzkeolhjf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtpfkjoygi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtskjyywal.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzblxwgof.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gtlaekfhie.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.316326.xyz/Article/details/gtdvkqxfzg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtkmgcmyaw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gtnwyioeai.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gtvjaikuim.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gtfnapmqsc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.vqdsnc.cn/Article/details/gtbkniuhtn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gttixiczok.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtdsjqvryd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gtxutrkhdd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gtpmiomnzk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gtvwizafmb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yongpay.top/Article/details/gtziwvmkdy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtwylklfxl.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gtpphdpgft.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrjujktn.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gttgqlnvsv.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gtupglhoou.html

PHP:  class User {}
来源：http://dali.ehwqpu.com/Article/details/gtkczuhhrd.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtnthnfgff.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gtrrmvzsez.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtotlfuder.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gtsffrvddc.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gtguoicsgg.html

C#:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gteusyxdmg.html

[G02] 构造函数
来源：http://dali.dashuyun.cn/Article/details/gtdxvminjs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.bjfxy.top/Article/details/gtvaamuzvz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shuidangran.top/Article/details/gtbypwzccb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtddibvgls.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gtjlrlzyfi.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtywowmnfb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gtybqurqpt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gthyfplojy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuanzx.com/Article/details/gtlrqfmazg.html

[G03] 实例属性
来源：http://dali.cashguo.top/Article/details/gtilutcibc.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gtdufudzrw.html

PHP:  public string $name = "x";
来源：http://dali.svipenyu.cn/Article/details/gtwyvkrvun.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gtdzrfqwhz.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gtnhrowbrc.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gtuoegwxnz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fengsongda.top/Article/details/gttbnzobuc.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gthevmjcon.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gtmnhowrek.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gttafztzhd.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtmojrkadc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtmaysqacz.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtujhacytc.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtvpbhpqpc.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gtjjgjuylt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtnhmdcmpw.html

Ruby: def greet; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtpkpxwzev.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gtkvmlcdgu.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gtojthkups.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gtmtsvhovp.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtujwnqxwz.html

JS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtoscdpmai.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtbxqvoyuc.html


<!-- 参考信息 -->