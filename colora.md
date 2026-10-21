代发 wailian999

[E06] 替换子串
来源：http://dali.shangyingyoupin.top/Article/details/gtxkcgccrm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtabjbqnuo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gtacbtoacm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtsdelwrbw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtwfxlmzyo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtsnbiavof.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtvatecskh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtayehqdvn.html

C#:   s.Replace("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtgrqfmakq.html

[E07] 按分隔符拆分
来源：http://dali.guannengcc.top/Article/details/gtuwgmmlgx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangtech.top/Article/details/gtfddxgsnr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtzielmshs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zdqjudy.top/Article/details/gtroivfcrq.html

TS:   s.split(",")
来源：http://dali.nwbrower.top/Article/details/gtatvjrldz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gtseyatxli.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.birdmap.top/Article/details/gtmqaobeoe.html

Ruby: s.split(",");  s.split
来源：http://dali.shangyingyoupin.top/Article/details/gtwxenphzf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.svipenyu.cn/Article/details/gtzrljcodi.html

[E08] 数组按分隔符合并
来源：http://dali.hammf.cn/Article/details/gtyofoddbp.html

Py:   ",".join(items)
来源：http://dali.yj20258.top/Article/details/gtnahaiegx.html

PHP:  implode(",", $items);
来源：http://dali.xziqi.cn/Article/details/gtpczyswvd.html

JS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtwcdqudnv.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtbdpdscoa.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcghfyrn.html

Go:   strings.Join(items, ",")
来源：http://dali.svipenyu.cn/Article/details/gteqmljqsy.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrrramzq.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtwqvgdams.html

[E09] 去除所有空白字符
来源：http://dali.hammf.cn/Article/details/gtxjcqnuwz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gthvbwjvoh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtxupfixka.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoeuatzwz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtafucbawq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtuqebbxbi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daria6918.cn/Article/details/gtnwvbzhsf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daxiang520.top/Article/details/gtviqtfdul.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jianghu66.top/Article/details/gtbztprxgw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.svipenyu.cn/Article/details/gtoxwpcnsh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtxwodrgak.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gtucmthqzh.html

JS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtkhhkjsnv.html

TS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtdbgllavb.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtdzmpiuso.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtscjuskbc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtpzghwxwt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhengqikj.top/Article/details/gteanxosyp.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gtuhhdifnu.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtxemwjjqu.html

PHP:  strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gtlmtiggoy.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtadcszjkk.html

TS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtkvjrsipy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cashguo.top/Article/details/gtijqatiyn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gtynerpvac.html

Ruby: s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtesivubyu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyprahhie.html

[E12] 统计某字符出现次数
来源：http://dali.yonumen.top/Article/details/gtcgpvvffe.html

Py:   s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gteozjdkzn.html

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gtovrpxctw.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtbyknavhf.html

TS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguprevoi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gtvmgballm.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgufenzy.top/Article/details/gtvlnbsdkp.html

Ruby: s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtcjgrcbky.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gotoacloud.top/Article/details/gtrjjjlrdz.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtresosiup.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gtcvldvzxy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgufenzy.top/Article/details/gteehsdgjo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtqnrjinzk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtokjjlrkx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtzaaemlkm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yangfankeji.com/Article/details/gtygpwmplm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gtdsfifjfg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtmiomtytt.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gtwzxfbllv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gtuqpwbhew.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtgvpiqdgo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gtbhzjmdjr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgubyfgt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtgnnubaxy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgfzy.top/Article/details/gtgexybjym.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gtretbfpew.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtbitmtsbq.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtyqhtjtjf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.quarkkingdee.top/Article/details/gtzmvdhxxh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cucudq.cn/Article/details/gtdpyfkmfr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daxiang520.top/Article/details/gtqtiekofv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gtitqxncys.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcgujsks.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gtgftdxbbn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtonwqmdie.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgfzy.top/Article/details/gtdxbcpfqi.html

[E16] 数字千分位
来源：http://dali.andypj.xyz/Article/details/gtlxnznzib.html

Py:   f"{1234567:,}"
来源：http://dali.xuanzx.com/Article/details/gtiitfpqxe.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gtofjqxqso.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gthtchnxmy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxvaxawc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhykuwkm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hammf.cn/Article/details/gthrsscbxh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.quarkkingdee.top/Article/details/gteggprxou.html

C#:   1234567.ToString("N0")
来源：http://dali.ydzc1.top/Article/details/gtzzneymaz.html

[E17] 首字母大写
来源：http://dali.yueranfly.top/Article/details/gtotvhztle.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gtgrjhzhtn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtabwgkuzv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gthqmkmtwc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gtajrcioln.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gtivncvaaa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtxogpzptu.html

Ruby: s.capitalize
来源：http://dali.ydzc1.top/Article/details/gtoihzihfm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hfpthk.cn/Article/details/gtnehurpoy.html

[E18] 模板占位符替换
来源：http://dali.jiagoushi.top/Article/details/gtypwbkoui.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.iojbl.cn/Article/details/gtsqjbsweq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxuanxn.top/Article/details/gtqmittwma.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtvhcfbxhm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtndadomro.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gthrbwbqzi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gtxfqehwbq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gtoubteyaq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gaohongyu789.top/Article/details/gtdiciymyf.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gtxukzjsot.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gtaobxvsec.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.havefunace.top/Article/details/gtbmbryakq.html

JS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtxawetwlf.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtxnnklpwu.html

Java: s.lines().toList()
来源：http://dali.shuidangran.top/Article/details/gtzcxtwlou.html

Go:   strings.Split(s, "\n")
来源：http://dali.xylfe.cn/Article/details/gtqlqrghwu.html

Ruby: s.lines
来源：http://dali.hnqzz.top/Article/details/gtbjwzzhhr.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gtrljrtimo.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gtinprkclv.html

Py:   if not s:
来源：http://dali.xylfe.cn/Article/details/gtqwsnzkoo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gtajmjkqgn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigfzy.top/Article/details/gttogzilxx.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwqvvpqg.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtyvkwgiko.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gtqgymozgy.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gtujjqzmqo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtyticrjvw.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gtwefoyhsl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gtatuqsxrn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtwwlbzmkn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtjplzkzxl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvomfehy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtscfomtkb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gttbnyombr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gteuhlyyjw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtgswbkgrm.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gtjichsfha.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gtmhtqnixs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtwmqiysdn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmmwpktu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gtucqtydeo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gtwasxjjwd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gtyrczitzz.html

Ruby: s.bytesize;  s.length
来源：http://dali.ybcxt.top/Article/details/gtengrbeqm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.mhx1999.top/Article/details/gtcekjwmzm.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmrvsrype.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gtrcfmydsj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gthxplwxzq.html

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gtrwhyvzrd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cdnleiting.top/Article/details/gtnuaccndc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtwnqzugdz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gtnwfatzxq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tanke756.top/Article/details/gtpvfscrgm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtxswdktlu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jiagoushi.top/Article/details/gtaexvkpwe.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtbgmwwawm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gtyvrlpcpz.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gtslaynubl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yonumen.top/Article/details/gtuuhfvlzj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnxiangtu.top/Article/details/gtrbxuqnnr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtrwiuaora.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtllzdhfch.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwiaabvl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aibaodan.cn/Article/details/gtadtenjrk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gtwoiezubi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gtdumdwabc.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gtvoxghfua.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgufenzy.top/Article/details/gtuygyrxko.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gtemumjjql.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtsuoyxwuv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtmrfcnlbo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gtofxwncbs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gtyxotmpkh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.0kj1m.cn/Article/details/gtmkoesvgh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtujfnrren.html

[F04] 追加写入文件
来源：http://dali.ybcxt.top/Article/details/gtdazohwbm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.birdmap.top/Article/details/gtxlnsfzjl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gtpnwnwlmh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gthwbmgoiy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtgwkaiksz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gtvayprcmy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gtwlbpxqzw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtnmtbhbdt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvrbtlmb.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gtmdcoezwl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhongyouzk.top/Article/details/gttxpxxthr.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtlaxrvwcp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtkvldtidn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtcfjknldz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtydrrdlov.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhdalxix.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtmhzbwtvp.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtdkekclvl.html

[F06] 删除文件
来源：http://dali.xziqi.cn/Article/details/gtlxbufunv.html

Py:   os.remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtiptoppev.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gtqvwjodyq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtyicjtfjp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtrwbqkxiv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtkwacihdf.html

Go:   os.Remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgqklkwu.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtdzapsvcd.html

C#:   File.Delete("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtlbjtpwne.html

[F07] 创建目录（含多级）
来源：http://dali.shangyingyoupin.top/Article/details/gtnnctawxm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gtzaazkcif.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258888.top/Article/details/gthsqwlevn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtbnljcucr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtyhsqbhva.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtrielzfjt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtdypcznmp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gtmbgxpmll.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gtyjvvecyf.html

[F08] 遍历目录
来源：http://dali.hongshengwenyu.top/Article/details/gtucothobw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gtayomqgvr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gtkzlixkee.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gtntazzitc.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtiqxicuum.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtypndojmk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gtrqkwniyv.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtrcknhrfw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gtegtfxmkq.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gtxndidlcb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtdrhoyqjn.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtldnrfvpa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtxasvwedb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtapiougil.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtkhwhyncr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yanxiufei.cn/Article/details/gtspkkpwjl.html

Ruby: File.size("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtfehlyyji.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gtebaazfug.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xylfe.cn/Article/details/gtsctpwmaa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gthnjbvqoh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tanke756.top/Article/details/gtkovceedu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtvtaprlqn.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtbffmgqnq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gtyaswtnhu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpamtecpj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtuojldyoz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtxflwldlu.html

[F11] 复制与移动文件
来源：http://dali.kuanghao11.cn/Article/details/gttzufljzg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtjnthricz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtgbzodjwp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtflociyup.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtaoavjrvm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtqsjqvpeb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gtjbvoexlh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtgeidgona.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfoxcqmuw.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gtvsbgtjyy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gtrstiqjxq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtgougcgqh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fengsongda.top/Article/details/gtlsywwjqe.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gtedpwoxvi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gtexhxzdty.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gtvagvbnqu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gtsaxayevu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gtnlcebfjm.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtisfzasxi.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gteyvgdswa.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqanoyur.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gtjjbjcnei.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gtdrechfxb.html

PHP:  class User {}
来源：http://dali.andypj.xyz/Article/details/gtpbvmldbn.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gteaxwgvqc.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtsibmexva.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gtihrbfnpt.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtjubnbymd.html

Ruby: class User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtjhvanxpa.html

C#:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtommycvnp.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gtchbdeghy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gtuxzbxjnp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gtobjaawql.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtqqtpczxb.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gtquagujow.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtotbkejsx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gthmgzmwyu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gtfsyanypr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtlpozpmad.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gtsdnpzlma.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gtqrpkyvlc.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtfceihena.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gtonorojsr.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gtjomzqfyc.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gtrkoijgtt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gtanzxhaau.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtqtuzbnly.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yangfankeji.com/Article/details/gtjsbbpihr.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gtylwokuqc.html

Py:   def greet(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gtqowcxpcm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtkgbfajkg.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtbawisivg.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtycklpjni.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtlizsznyw.html


<!-- 参考信息 -->