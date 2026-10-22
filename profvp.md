代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gtrdbanpcy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gtourfmvjd.html

[E08] 数组按分隔符合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfuhvlyz.html

Py:   ",".join(items)
来源：http://dali.daria6918.cn/Article/details/gtgywkljzi.html

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gttmhjpcpc.html

JS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtpklaxqsq.html

TS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gttanpqkgp.html

Java: String.join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gtqiffduey.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gtzaraslkq.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtincidbvr.html

C#:   string.Join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gtolslckvg.html

[E09] 去除所有空白字符
来源：http://dali.fengsongda.top/Article/details/gtzdiubssn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtupyzknch.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gttkkltqco.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtfjjeuwfz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtlepfhsdy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gtqxuzrxyf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cashguo.top/Article/details/gtwfrorvus.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sxryk.cn/Article/details/gtgnxvjefo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtpdxbpmmz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gtqyoajzsv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtgnrukxvr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gtvrfianzv.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmixciuyh.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtlhqvuxgo.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtngjjgrad.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtikngbcwk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtnrcteeqt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shuidangran.top/Article/details/gtsqbvweuz.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gtpkmuxwuo.html

Py:   s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gtpcfbimeg.html

PHP:  strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtlwbaedso.html

JS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gthtjjthli.html

TS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtelbtldoz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ivvv.top/Article/details/gteojtgpur.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtwzwtvkrp.html

Ruby: s.reverse
来源：http://dali.tanke756.top/Article/details/gtwkmxzuvy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtpdnwsidm.html

[E12] 统计某字符出现次数
来源：http://dali.dashuyun.cn/Article/details/gtuxlpzxjo.html

Py:   s.count("a")
来源：http://dali.gzhubu.top/Article/details/gtmlupovxb.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtsbmthjmt.html

JS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtmzprvryu.html

TS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtdskvvfji.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guowangkeji.top/Article/details/gtdermmqoj.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gtuxzbkkgx.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtlaczbptc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxinkj.top/Article/details/gtfxlyswhy.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gtipzbbxix.html

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgnjqbbg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxinkj.top/Article/details/gtzsmtavdi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtwxbdvhxx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtncdyinix.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.mhx1999.top/Article/details/gtcknougys.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258.top/Article/details/gtdeuuqhun.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jlsjyb.cn/Article/details/gtefwlaoxc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xylfe.cn/Article/details/gthttucbkr.html

[E14] URL 编码与 Base64
来源：http://dali.yonumen.top/Article/details/gtzifggtrt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gtkwauudpq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtkzufxspi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gtegxazddr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gtyikombtn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtzpzjcvxq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gtfinapbhr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gtnjlhmwnf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xinyue.icu/Article/details/gtwiatvgzg.html

[E15] HTML 转义 / 反转义
来源：http://dali.tian-w.cn/Article/details/gtipfsrlli.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.iojbl.cn/Article/details/gtqdrwnaev.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigfzy.top/Article/details/gtqfslcqec.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gtdjkftjhq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gtrjgndmah.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gtmmltxioo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guowangkeji.top/Article/details/gtqgfdpkdu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gtgfftbytb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gtwnhbhayc.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gtgfrtcbyv.html

Py:   f"{1234567:,}"
来源：http://dali.aibaodan.cn/Article/details/gtkmswzxdl.html

PHP:  number_format(1234567);
来源：http://dali.sysykeji.top/Article/details/gtkoekbnog.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtrgbdeixf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gtduxxeofh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gtifcdrpet.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gtpsszapwe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gtkqeaolmu.html

C#:   1234567.ToString("N0")
来源：http://dali.gzhubu.top/Article/details/gtkmdhopau.html

[E17] 首字母大写
来源：http://dali.zycfv.cn/Article/details/gttjzynybu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gtrjlkctcr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtiqgcwzoo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gttjltpgzi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtmaewkjje.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtdwswgzek.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhixingplan.top/Article/details/gtmdtztafm.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gtebcxgdsf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gtzbifkzuu.html

[E18] 模板占位符替换
来源：http://dali.hnxiangtu.top/Article/details/gtkrecrhcs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusxjlklm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gttopowmxj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtciewvidh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtjvnzanvl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtncpkdnrf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtwkczeglv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gtihajokmk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gtxonplnwz.html

[E19] 多行文本按行拆分
来源：http://dali.haohaochexian.top/Article/details/gthyczankf.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gtbomnojst.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxavlocmk.html

JS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gtfoseopqq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtqkgxlxuq.html

Java: s.lines().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtsgxmtvmq.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258888.top/Article/details/gtahxbzmzx.html

Ruby: s.lines
来源：http://dali.birdmap.top/Article/details/gtncgrmxeo.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gtheseuknw.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtbuxoxifa.html

Py:   if not s:
来源：http://dali.hfpthk.cn/Article/details/gtqxxduoxh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenjidiqi.icu/Article/details/gtwvoksftm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.haohaochexian.top/Article/details/gtrrtqmaxg.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gtrozluqoe.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtqhalmaxx.html

Go:   if s == "" {}
来源：http://dali.0kj1m.cn/Article/details/gtngvbpqur.html

Ruby: if s.empty?
来源：http://dali.wangshuangyany.cn/Article/details/gtnmetmfcg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqdtgecpo.html

[E21] 超长截断加省略号
来源：http://dali.jqgufenzy.top/Article/details/gtncbbbkym.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.snrcjt.cn/Article/details/gthjsfuupk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtdhcodfqw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkusefic.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gttkbewzyu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gthedsjojw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shangyingyoupin.top/Article/details/gtcoxjhdtv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtitabaoxy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtjxjtmaxb.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gtmvzufyae.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gthjfxpuad.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtodsmmjza.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtiudicdwz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtoiyuqkbh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtsnlfxkfe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbryhxndb.html

Ruby: s.bytesize;  s.length
来源：http://dali.c1oappe.top/Article/details/gtyumkwjbi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlwqcpjx.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtgtqbyyfo.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gtgnqovpbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtzefczblr.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gtzvhygqhv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gtvjphrpgy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtuhkydbsm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gtinqbhcba.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtzdjiaquy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtdmfgzvzi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yvedp.cn/Article/details/gtsuvusdul.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtrcwoacrw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtwocnaodl.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gtvpmimfys.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gtxbqrmoyx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jyoumei.cn/Article/details/gtvsyxjygm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtqdkzxpar.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtdreytbxc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtawnwqvfc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gtplrqvpaw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gtigtarbdj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gtyzmcvsut.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gtehuzagyc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gttzdndqez.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtrpizqqpe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtiaaqisob.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtlivqjxmw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tianlin.xyz/Article/details/gtwxgmcyhw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gtbjsbvpks.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gtotayeudu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gthmtbjwve.html

[F04] 追加写入文件
来源：http://dali.tian-w.cn/Article/details/gtxonyfnam.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hammf.cn/Article/details/gtrryxbpme.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gtiaaptqmg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtxpvuthrv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtrbmhjiic.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.c1oappe.top/Article/details/gtmzsdfqgp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtouzmdgrt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhiwuduotai.top/Article/details/gtiiiirdev.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zdqjudy.top/Article/details/gtwbjkqzjn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zycfv.cn/Article/details/gtvyovgvow.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gtyngtuexq.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtxxhahpgd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbwjcwls.html

TS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtbpcmqsta.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtsgldzpvw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gtzixeokal.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtbupuatft.html

C#:   File.Exists("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtcyjqxqap.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtlhqmhwaa.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gthgqzxfjv.html

PHP:  unlink("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtdoohdtsv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gteogorydr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtvqyzngjf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtoxpgozxv.html

Go:   os.Remove("a.txt")
来源：http://dali.sweek.top/Article/details/gttbjumjdu.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtmhibqonk.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtrevzprdp.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gtwverohsr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gtpuyjolmz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gtcgzlhmmo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gthvylvflf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtminauzgv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxfougqr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gtyatraljp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gtttgnuaeb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.mhx1999.top/Article/details/gttclmawrf.html

[F08] 遍历目录
来源：http://dali.wangdashe.top/Article/details/gtshymjxru.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aizwys.cn/Article/details/gtghxhzjtd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gtxcevchsx.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtyivsbkrj.html

TS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtdleesmhl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtcvigguvl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gtbpvnioro.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtqhfiuzmj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtktssxbbo.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gtowdlwkim.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtpnlmplya.html

PHP:  filesize("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtplfjnltm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtlyrplvlj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtaeqgvnsr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtloquyiac.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gtmshqmopu.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtidhnpmrn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258888.top/Article/details/gtpetysxiv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gtntpiluwn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtkgaminhs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtnmfiimxx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtsmrirepk.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtofybtvnh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gtiqcdogvc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtbqnevesc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtuhijqsxf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtgjclnncx.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gtzuoesjzi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtluvtzeru.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gtomyooqub.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gteeuhpffr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtdcyttjsj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtlmdzyykt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gtejxtagws.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtswzqaowi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jlsjyb.cn/Article/details/gttienvjjj.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gtlltyovhj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gtxybqeswt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gtyiuddeqb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gtjstnfimx.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrltbqop.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.andypj.xyz/Article/details/gtxbezpimp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gtvetpmlzu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtlyrlsfax.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tian-w.cn/Article/details/gtackvdbyp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtidtxknkm.html

G. 面向对象
来源：http://dali.zhiwuduotai.top/Article/details/gtoradvotx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlpktpowf.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gtetlcjsfs.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gtwuqtkpxm.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gtzjnlidse.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtdugmxzyw.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtnuezcbxt.html

Java: class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtgvnpacyx.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gtuyjciktc.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gtwocixkun.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtzefsyxpe.html

[G02] 构造函数
来源：http://dali.dashuyun.cn/Article/details/gtrdptdhwm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ybcxt.top/Article/details/gtutnuqktc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtjbbsetew.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtxwhbimhl.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gtxztinxrw.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcahduvm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtibgykoan.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gtvtfuxikh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuppuztf.html

[G03] 实例属性
来源：http://dali.shangyingyoupin.top/Article/details/gtvuwxwbld.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gtfnttczwo.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gtqvfaboxk.html

JS:   this.name = "x";
来源：http://dali.chenzaomai.com/Article/details/gtezqmkeyj.html

TS:   name: string = "x";
来源：http://dali.daria6918.cn/Article/details/gtfkvrquzm.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtxhjjznml.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gtibcfvzht.html

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gtllwgwfbu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgufenzy.top/Article/details/gttbzepups.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gtmasuiqnm.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtyceskuyc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtttczlfop.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtadqacekx.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtwbjyppbr.html

Java: String greet() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtgknanyjp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtiuvdrsnc.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gtuorscvqz.html

C#:   public string Greet() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtfsyqsrke.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gtrwdygktn.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gtxcgddoic.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gthzfvalrf.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtjiijfiny.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtqvybpvqv.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtszmcbcky.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gtppqqiqwa.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gtxvcsjvlt.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gtsszryskd.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gtbkqryrnn.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gtsgnhhpsr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtbcteofsx.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtyptztzcp.html


<!-- 参考信息 -->