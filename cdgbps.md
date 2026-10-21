代发 wailian999

[E06] 替换子串
来源：http://dali.zhongyouzk.top/Article/details/gtxtkphyjx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtotbggjpa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gtusaeddoh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtzkffwyxp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtluxmedlg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtodsuhhls.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtxmwazuxi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hammf.cn/Article/details/gtfxyogqxo.html

C#:   s.Replace("a", "b")
来源：http://dali.cashguo.top/Article/details/gtimqxcajc.html

[E07] 按分隔符拆分
来源：http://dali.meibo888.top/Article/details/gtrfxujeow.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhengqikj.top/Article/details/gtivzupeui.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtemtimfjd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daxiang520.top/Article/details/gtitjqbyqp.html

TS:   s.split(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinellpwp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gthsgwigyr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jlsjyb.cn/Article/details/gtklswlhhy.html

Ruby: s.split(",");  s.split
来源：http://dali.zhiwuduotai.top/Article/details/gtslnxfgup.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gtppftpnfj.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gtkxjsgctx.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gttvfexabj.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gtzmjlaral.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtelmpmfnh.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtknjjmyhv.html

Java: String.join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtncllmhae.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgufenzy.top/Article/details/gtptumymdc.html

Ruby: items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtbbsdqeqh.html

C#:   string.Join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtrfofybqk.html

[E09] 去除所有空白字符
来源：http://dali.kuanghao11.cn/Article/details/gtcvkyxrxf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.9152youxi.cn/Article/details/gtrvglmszh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ivvv.top/Article/details/gtyyjtyniy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtlzuoasfz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtehzezflp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthilxtrbr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhixingplan.top/Article/details/gtkammnxjk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gtidakltsm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gtvyzanatr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gtjxmbzkjj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gtsgqyndao.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.quarkkingdee.top/Article/details/gtoecdowej.html

JS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtiwfbqjxy.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtcnzjobay.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtycduwskt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtosrhegkt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtyhcqrxsu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ivvv.top/Article/details/gtggvmypwq.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gtnuplqonx.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gtlsdkbglz.html

PHP:  strrev($s);
来源：http://dali.sweek.top/Article/details/gtwbkbpums.html

JS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtlmewxszk.html

TS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gterxkhjrp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gtgqtobrjq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmlriqvp.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtsfeeslem.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtfgqiicuq.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gtmymyrltv.html

Py:   s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gttkydkieu.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gtniqgbquv.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolihrkus.html

TS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gtxxcwhcqx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nwbrower.top/Article/details/gtwtutdiuc.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gtblfubfjh.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gtfqdmhqgw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.0kj1m.cn/Article/details/gttadczhyh.html

[E13] 逐字符遍历
来源：http://dali.aizwys.cn/Article/details/gtsepwfjii.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gtekavzsvv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gttmbwxakg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdrjkcti.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtkweidegz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtjlhfpzbw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gtpfovreud.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhongyouzk.top/Article/details/gtgxdyqauk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pycfn.com/Article/details/gtwztvxqhu.html

[E14] URL 编码与 Base64
来源：http://dali.316326.xyz/Article/details/gtikdstgth.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gtcwzvmjtm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gtgorxovon.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gzhubu.top/Article/details/gtcrhaziku.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gtmlkoambw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zdqjudy.top/Article/details/gttfxldfri.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnxiangtu.top/Article/details/gttjmgxnhy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gtfjchmuxa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gtcoqdzqjv.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gtotohlfxl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhixingplan.top/Article/details/gttufcjzcb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gtdxzbqrlx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangshuangyany.cn/Article/details/gthdyfocox.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cucudq.cn/Article/details/gtqggwezhh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gtccaektpc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxuanxn.top/Article/details/gthxufgzov.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gtrsvtugxu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtggyyhjpz.html

[E16] 数字千分位
来源：http://dali.chenlongwang.top/Article/details/gtaqlojhxm.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gtendallxr.html

PHP:  number_format(1234567);
来源：http://dali.0kj1m.cn/Article/details/gtvcofsbwt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtdcfpidsn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtnxbmfdik.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gtsnvatfkt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gtqhciabps.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gtyrpjejxl.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gtqpzfxalu.html

[E17] 首字母大写
来源：http://dali.yanxiufei.cn/Article/details/gtnqjwnihk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.bjfxy.top/Article/details/gtwskylktg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shzxlz.cn/Article/details/gtnybqxhqg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gtonttipcl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtmosolzgv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gtuvywklwf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtcjxnsvtn.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gtmbfmgyfu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yangfankeji.com/Article/details/gtlpcegzmj.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gtorqyeums.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zycfv.cn/Article/details/gtjajuyiqd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.c1oappe.top/Article/details/gtwptoawoe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtkkziippv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtxlbcfikz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtxxtuouoy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gthcewrnaq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gtbgmmjowk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhengqikj.top/Article/details/gtydnslqfy.html

[E19] 多行文本按行拆分
来源：http://dali.guowangkeji.top/Article/details/gtkylvicmu.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gtvdzjlbpd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtqwbfkajf.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gttcsudjmv.html

TS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gtrjegvzot.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gtcewdqici.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gtqkuyhkhb.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gtbdzegdop.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gttuyaryia.html

[E20] 判断字符串是否为空
来源：http://dali.tian-w.cn/Article/details/gtjxixlwoo.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gtlplyfslx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gtibseoivo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gtlsmopvea.html

TS:   if (s === "") {}
来源：http://dali.fzhhl.top/Article/details/gtmmqdcbwo.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtphbxxapx.html

Go:   if s == "" {}
来源：http://dali.bjfxy.top/Article/details/gtktvmjnbo.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gtkuohgtyu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gtzeqtndje.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshpnkcol.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tian-w.cn/Article/details/gtlhdsjpan.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtxhlfgvln.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtrdntzxrs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtfabpccrh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtxauoicai.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tianlin.xyz/Article/details/gtwfzqlddd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtikoaplve.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtgtudnefp.html

[E22] 字节长度与字符长度
来源：http://dali.guannengcc.top/Article/details/gtefpxrxqi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj202588.top/Article/details/gtnrahnpke.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtewvfurzc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtpuwppmqi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtyoszshgl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtkzjitxmd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tianlin.xyz/Article/details/gtahzccrjd.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gtayeomkfp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtphoihwjd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtuzwbweeg.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gtsvkwhxrg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxtieuysk.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gtvsgopdmf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gtcohazapc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtysemhpql.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigfzy.top/Article/details/gtcgjaycck.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gtwlqomqkp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtyrbksfqt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gtuydyewgk.html

Ruby: File.read("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtqfxxbiev.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtcwldqrml.html

[F02] 逐行读取文件
来源：http://dali.hnxiangtu.top/Article/details/gtycppfvbv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gtisyyaqik.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gtrwqgheti.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtkerdftlj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gthciaxwwt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtyekltcte.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gtifycxsgh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tanke756.top/Article/details/gtybsjutoy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gtqvqhqnix.html

[F03] 写入文件（覆盖）
来源：http://dali.hfpthk.cn/Article/details/gtkfyytkod.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuanzx.com/Article/details/gtctpxkzoe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtfiswqpmc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtxfupjbbl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtqgfxpstn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkiszlzqj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gtzmdmvxov.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtgffqsaaa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtuwwfvlsz.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gtnazhbzid.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtnbyksmvp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gtvoopjteh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufggcbid.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtagvnbtim.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gthwnjunuz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtkvsijavt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigufen.top/Article/details/gtautocfxj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.meibo888.top/Article/details/gtiirohwpd.html

[F05] 判断文件或目录是否存在
来源：http://dali.jiagoushi.top/Article/details/gtpmqxdbdx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daria6918.cn/Article/details/gtubdnkisa.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtrbrvmful.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtsxyxrsvb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtwqtijlle.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtvqjptnyf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gtesvqlzzk.html

Ruby: File.exist?("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtpvlaqrma.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtpdoziedb.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gtrfsjmwop.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtlqqmronb.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gtbutqeinr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtnzzurgnw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtkjdsbigh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtuedmlxtl.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtjmmyezyi.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtezgjuvuk.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtyhcdzmoi.html

[F07] 创建目录（含多级）
来源：http://dali.nanxinkj.top/Article/details/gtdnnragki.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gtjqgbwvsj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrbqrxbm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtccytmuek.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtaotcuzen.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gtwoqallxo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhengqikj.top/Article/details/gtahdwcieh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gtgzwworub.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daria6918.cn/Article/details/gtvszifpgk.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gtpemxxmsk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtesgvwrop.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hysaishi.cn/Article/details/gtwbweefjn.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtdaqcakvp.html

TS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtwmkthugt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtmhzhwkky.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtkyglqdht.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkpzgvho.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ppjwa.cn/Article/details/gtohktllia.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gtmzarbybk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gtcsntxsbt.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtmipizvsg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtxjxiepdn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtnxklhwkh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtltztzkks.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gtxwbuvbcz.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtqiajodmb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gtpzmwhbwm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gthchnixjw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gttksijvkl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtlhnggmfl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gthbvscida.html

TS:   path.extname("a.txt")
来源：http://dali.316326.xyz/Article/details/gtlhyzlhzf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gtearabbur.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtmslxzigc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtxszwxxyr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtyliigfzz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gturltiixb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtnzgfzvcx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gtkburejxr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtlmnfhjwu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtoghhzhla.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtjumpxacp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hongshengwenyu.top/Article/details/gtmaifvlmt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtauodsvnx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gtexgzqevv.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gtnmvqsbcz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gttahtxuge.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gtnuesqgyg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtiztnxjud.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gtdtsbldsv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gtdcwqfgwi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gtzcugidos.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gtrviacfim.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsxudfsr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtlxnmlcfr.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gtkvpzxzoo.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbcyttyrb.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gtdmojpngp.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gtktsftfrp.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gttdoniswm.html

JS:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtheiafbel.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gtljxcxbnd.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gtwsphdcdf.html

Go:   type User struct { Name string }
来源：http://dali.yuxming.cn/Article/details/gtotkgpgar.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gtwgwddntj.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gtbpvfavtj.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtqzuwwytb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gtakfyzdyg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shzxlz.cn/Article/details/gtkmaalzik.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtaykgxyat.html

TS:   constructor(public name: string) {}
来源：http://dali.andypj.xyz/Article/details/gttvfnlxma.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtntyqoqpt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gthtqccnur.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gtecwvtsbi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gtkjzfnbsj.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gttwttmyrd.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gtgqpousjp.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtapvihfoh.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtufrtuump.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtmcsvvgwd.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gtbfxqauly.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gtyfgaibtz.html

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gtluygzzjd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gtgxanlydh.html

[G04] 定义方法
来源：http://dali.iojbl.cn/Article/details/gtmluuijgu.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtigrljavs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtqpngvhlk.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtpqajrakt.html

TS:   greet(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtapgmimdm.html

Java: String greet() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtxizvitvy.html


<!-- 参考信息 -->