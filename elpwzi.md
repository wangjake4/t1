代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtjnlijqlm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtwykfvaka.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtdlviqszl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtmuvphckh.html

C#:   s.Replace("a", "b")
来源：http://dali.gzhubu.top/Article/details/gthcugdiwt.html

[E07] 按分隔符拆分
来源：http://dali.redwolf501.top/Article/details/gttenbhowm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gtbezfvfyd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gtnrhmgals.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gtugcihohr.html

TS:   s.split(",")
来源：http://dali.hywenlv.cn/Article/details/gtrjclzyuh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cqqwz.cn/Article/details/gtpgehsbgb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gtdpxkzbxb.html

Ruby: s.split(",");  s.split
来源：http://dali.zycfv.cn/Article/details/gtmlwrpyqq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gtsozfqpoq.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gtlwmtfbpx.html

Py:   ",".join(items)
来源：http://dali.0kj1m.cn/Article/details/gtglpgccxz.html

PHP:  implode(",", $items);
来源：http://dali.yuxming.cn/Article/details/gtigxlauex.html

JS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtdmmizqlr.html

TS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtmtnpaogd.html

Java: String.join(",", items)
来源：http://dali.tian-w.cn/Article/details/gtyjnlonsx.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gtjczsyyjf.html

Ruby: items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtnhdvjtqs.html

C#:   string.Join(",", items)
来源：http://dali.yongpay.top/Article/details/gtprloemle.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gtjotvcqaa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tanke756.top/Article/details/gtscodyjxr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtprsxljsi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gtiwmhveab.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gtdxjhetqx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gttsrnizzo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gtkyuqkqzn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtpzcyknvf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtyrsgzmoe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pycfn.com/Article/details/gtlqblmwls.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtgimfootx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gtrfgaivai.html

JS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtdsovogkm.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtxoxuayen.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtvylwcslg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtroscepkc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtxsudtuxu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pengpengdd.cyou/Article/details/gtakqlhppq.html

[E11] 反转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtwruygtxy.html

Py:   s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtyktrcnct.html

PHP:  strrev($s);
来源：http://dali.tian-w.cn/Article/details/gttsoqsfac.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gttawhflxn.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtgjwnzzlq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtmhvqolcu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtvnnscglt.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtdliuvkit.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gtktfdcjyo.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gtinesnmab.html

Py:   s.count("a")
来源：http://dali.tian-w.cn/Article/details/gtxwvhvrtx.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gtkvheirqb.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtiyvaejct.html

TS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtjjydbyzt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwblipwm.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gtqqahywgi.html

Ruby: s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtohtflzrn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gtjylhebfn.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gtqqihpolj.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxinkj.top/Article/details/gtwjackenr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtvscroowa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtouownquv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtdikjkghf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtunqxgpwv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.kuanghao11.cn/Article/details/gtvbwajgvh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.kuanghao11.cn/Article/details/gtjicbkmth.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xylfe.cn/Article/details/gtwgzzsmnk.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gtuxaoradz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hysaishi.cn/Article/details/gtbgzaodxh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtzvqxxrtl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ppjwa.cn/Article/details/gtiegpkfwd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guannengcc.top/Article/details/gtsostkxqo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gtyhkfdaej.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ppjwa.cn/Article/details/gtwnqyhmwk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ppjwa.cn/Article/details/gtjuezqfne.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jianghu66.top/Article/details/gthmechgkk.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhengqikj.top/Article/details/gtisdoqvio.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtgxlrlyqq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gttmhjywqj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangdashe.top/Article/details/gtvndqpnff.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnxiangtu.top/Article/details/gtvinppiee.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ehwqpu.com/Article/details/gtmvmxyimh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yonumen.top/Article/details/gtvglmncgv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yanxiufei.cn/Article/details/gtvaxkjptr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqrqzavm.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gttcwjdcfa.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gtgjrpmjka.html

PHP:  number_format(1234567);
来源：http://dali.xinyue.icu/Article/details/gtvxzbcqby.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtkrihcckz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtueganeuv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gthfckihgq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gtlkurdzgi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtqpmnnffh.html

C#:   1234567.ToString("N0")
来源：http://dali.quarkkingdee.top/Article/details/gtqpzsztih.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gtvvptbrnw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigfzy.top/Article/details/gtouglskfo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphwdtiaa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtyunvepxo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtehlmpqaz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gtunbmeufx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shzxlz.cn/Article/details/gtkfsgrzfv.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtbyegpyfk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gtjbbarmdp.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gttqwislov.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigufen.top/Article/details/gtxodwsltu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gtowxafpfe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gteokhfsnp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjuuwump.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtdokwlgxp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtldirnzsb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gtxmamtiqa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgfzy.top/Article/details/gtbucnyefu.html

[E19] 多行文本按行拆分
来源：http://dali.zdqjudy.top/Article/details/gtmivcgoyi.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gtwcgyliyq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gtcslqbvpe.html

JS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtizltfkae.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtyfximljz.html

Java: s.lines().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtxbkguocn.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtcwcfinjg.html

Ruby: s.lines
来源：http://dali.andypj.xyz/Article/details/gtaojuadzw.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gtjsblwvjv.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gtnriwgoan.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gtfydkngpt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gtnnsjarfm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtgaoaxeun.html

TS:   if (s === "") {}
来源：http://dali.yangfankeji.com/Article/details/gtobtrqnxl.html

Java: if (s.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmngmpavr.html

Go:   if s == "" {}
来源：http://dali.fzhhl.top/Article/details/gtxxxorhxm.html

Ruby: if s.empty?
来源：http://dali.dashuyun.cn/Article/details/gtrpotvoix.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guowangkeji.top/Article/details/gtemlpyiki.html

[E21] 超长截断加省略号
来源：http://dali.yvedp.cn/Article/details/gtdiezbvnm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gtmeceledz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtsinvogls.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtbdbbkhib.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtdgcskxnd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtlubbemcq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gtyjatllmd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjfualgi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtwmqonboo.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gtgsyblgeo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhixingplan.top/Article/details/gtpgdyzamq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtrdctisvo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtepzfqmfh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtzkdueoeq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtfhliztkv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gtxjwgxfag.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtmbaigxcf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgfzy.top/Article/details/gtmbuqqviv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtloraijxm.html

F. 文件与目录
来源：http://dali.jqgfzy.top/Article/details/gtlmyfxjbc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtdmnsksml.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gtfbiryrcs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gtvekmshiz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtrxddgbiw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtukrclaot.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtcznrocwb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtuladmocy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cheryme.top/Article/details/gtnnwusuqk.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtxkkvhedf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gttlojvngg.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gtjcplzezs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gtmqjrvwog.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gtxzzaewue.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtfwqtcbux.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gtrjqkdhcd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtdnlkunzd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nwbrower.top/Article/details/gtqfdkoswc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gtiewvookw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gtxvvpelkp.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gtgpylquvg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gtzvfhwzlx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtlohkfpod.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtkacstplo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtonnocjox.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gtsbnqqver.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gtngvwyzsc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zdqjudy.top/Article/details/gtzdanbbdc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtybqvwmol.html

[F04] 追加写入文件
来源：http://dali.zdqjudy.top/Article/details/gtpnduiwrh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcuoqjaq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtstoizrql.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtebiacldn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtgdvnbasl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gtykofmrtf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daria6918.cn/Article/details/gtmvkmxeet.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgyzsbiz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gtmflnlrcm.html

[F05] 判断文件或目录是否存在
来源：http://dali.yvedp.cn/Article/details/gtvjpxixwm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnqnzomk.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtoennsqcc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtskdwyxmt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtpisdlzan.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtkbjbyrlx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gtrayveara.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtwehkbwmm.html

C#:   File.Exists("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtlmybhacg.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gtrejptafi.html

Py:   os.remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtyfxkdwxs.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtkrsqetxa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtjqnnyswe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtcdgyduke.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtyoskotev.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtujysgory.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtvdpvurfe.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtrjnhxmsv.html

[F07] 创建目录（含多级）
来源：http://dali.ydzc1.top/Article/details/gtinskreuz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtfrboeceg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnqzz.top/Article/details/gtaaysipee.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtjzwnuamw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gttyydujlq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gteqxzorvl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dashuyun.cn/Article/details/gtfcpsmtve.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gtfzephyjd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfplvwhiu.html

[F08] 遍历目录
来源：http://dali.yj20258.top/Article/details/gtyenekhfr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gtowdixbuk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gtllubllgu.html

JS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtopdzewte.html

TS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gthbwrvnnq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gthdfzavyb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gtpspubzmr.html

Ruby: Dir.children("dir")
来源：http://dali.xinyue.icu/Article/details/gtfklfnewu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gtzunqmgdt.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gtfejtxsdz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gthzjsoxla.html

PHP:  filesize("a.txt");
来源：http://dali.fengsongda.top/Article/details/gttibljohw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtbrilzree.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtrhaajpqr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtemkidnuc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtwqvckefj.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtjjgryphy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gaohongyu789.top/Article/details/gtuawvqrjx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gtrfzvfehi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtlqivhmky.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqksgpnv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtxzrwwnic.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtujdoebun.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadexdefx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtuqkxbfwo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtezsxxpbk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtowezagmj.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gtczichuzx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gthhnbzqfd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxqdxxwu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtvrvkwnjn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gttyoratsk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtciaxwtde.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gtennfhomo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtjaezmmsm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxinkj.top/Article/details/gtahhkftdm.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gtbxjaebov.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuxming.cn/Article/details/gtdxcxshfj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gtlkspaqdy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuxming.cn/Article/details/gtzikycmat.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcsfvjxj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgfzy.top/Article/details/gtrtnfdytu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbpactsg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gtyxnxmang.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sweek.top/Article/details/gtvauxyxrx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpoqmnbrd.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gtjiwbatei.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtmbxjwgnt.html

[G01] 定义类
来源：http://dali.zhongyouzk.top/Article/details/gtplpecdwy.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gtpjditezx.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gtgsebooqg.html

JS:   class User {}
来源：http://dali.hammf.cn/Article/details/gtuzrixrbf.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gtscupvlvg.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtgrwahzyi.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gthdiavmmy.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gtsehtmbxf.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkxdilkt.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlthnxdrs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gtvjzqfqdj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtdwqmwbuz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtcgjarrpf.html

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gtotrklqxc.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtdpophbnb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gtrtzeagsc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gtpkcssvgc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtjwxhagux.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gtmltxywtv.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gtyegzzaaq.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gttzuztiqb.html

JS:   this.name = "x";
来源：http://dali.birdmap.top/Article/details/gtibktehza.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gtzcgfxchy.html

Java: private String name;
来源：http://dali.cucudq.cn/Article/details/gtzyryyfdk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gterbiotha.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gtrnigdhnk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtroeztlcq.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gtpfqgoizg.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtucfnwlpp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtyejpoflp.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtkdxuwwpd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtuubddtol.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtizyskqzt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtuizjkwod.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtjtnnlqyo.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gtenagqeqf.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gthnjfwqdd.html


<!-- 参考信息 -->