代发 wailian999

[E06] 替换子串
来源：http://dali.kuanghao11.cn/Article/details/gtfkkhaanx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gtsuczpdhp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtrsfygcef.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtixfyahrl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtqhownacz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gthfkfmxpx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gtbregqdme.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtrylxjmll.html

C#:   s.Replace("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtrwnvzgoo.html

[E07] 按分隔符拆分
来源：http://dali.sxryk.cn/Article/details/gtrmtdpxzz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.316326.xyz/Article/details/gtqzwdetbb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtfmzkyphr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.kuanghao11.cn/Article/details/gtdzjwvkfq.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gtoeymphpa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xylfe.cn/Article/details/gturjnftxj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gtiorxpbnj.html

Ruby: s.split(",");  s.split
来源：http://dali.redwolf501.top/Article/details/gtdgvqraxt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shzxlz.cn/Article/details/gtxvcjxzst.html

[E08] 数组按分隔符合并
来源：http://dali.dianchejie.cn/Article/details/gtaposhjzh.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gtscjpmzhq.html

PHP:  implode(",", $items);
来源：http://dali.jiagoushi.top/Article/details/gtzfvrlrgk.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtynabjpsg.html

TS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtaomggfpo.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtttscumov.html

Go:   strings.Join(items, ",")
来源：http://dali.havefunace.top/Article/details/gtiykzqurj.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtjxbqmzuh.html

C#:   string.Join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtlsbqceqq.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtoywomgvg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gtdsatnczn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ybcxt.top/Article/details/gtmraaskvi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtzcrvrxxf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtbgoaexen.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xziqi.cn/Article/details/gthppvcbil.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tianlin.xyz/Article/details/gteywxcvye.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqwarcfa.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcaugnwcl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gtmivhlibv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtubasiwsy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxqwcgrf.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtqcebyqch.html

TS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqjmeryb.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gthpyrqfgs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtqoajetkf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtkzfpfxod.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gtvsbotlkr.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtdxsfnvqo.html

Py:   s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtxglfviwj.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gteddmefwc.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtutzwkize.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtsigrxjcd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyoxkwsl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtwpuztsxb.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtusiibegn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnvwodye.html

[E12] 统计某字符出现次数
来源：http://dali.xziqi.cn/Article/details/gtygpjxdxb.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gtgljfalvi.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gtkqsiieku.html

JS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtciabffhv.html

TS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gtocybztcy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsscpprnt.html

Go:   strings.Count(s, "a")
来源：http://dali.sweek.top/Article/details/gtnztasfvs.html

Ruby: s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtkokbwrjb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangshuangyany.cn/Article/details/gtxicedwdb.html

[E13] 逐字符遍历
来源：http://dali.sxryk.cn/Article/details/gtvbigquvk.html

Py:   for ch in s: print(ch)
来源：http://dali.gzhubu.top/Article/details/gthogcujff.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gtsssznpau.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtplzqzqyo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtgflgmxiy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtasskulyf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gtvnmoafec.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gtmhdrnkms.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtxmxodswb.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gtynttxahe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hywenlv.cn/Article/details/gtsqfvxqti.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gtpaviaxqz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxinkj.top/Article/details/gtplvjtlhu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gtakoxmlzl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtwugpbzws.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shuidangran.top/Article/details/gtyekzgkls.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gtrrttnowf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlrlasqd.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gtwdloukkj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtlplovaeg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gtjhjthdoq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.havefunace.top/Article/details/gtvgtbbwen.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gtgdalqfwi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ivvv.top/Article/details/gtbcmroiud.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhixingplan.top/Article/details/gtuboikiff.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ivvv.top/Article/details/gtalnxzuqr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daxiang520.top/Article/details/gtfwavtdgl.html

[E16] 数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtvmiqghil.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gthklvkoui.html

PHP:  number_format(1234567);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdzvjzfc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gtircfvhby.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtykotlcwo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gtcvchtsac.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shangyingyoupin.top/Article/details/gtdpoauwoc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hammf.cn/Article/details/gtdmpvithu.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgufenzy.top/Article/details/gturapfrjs.html

[E17] 首字母大写
来源：http://dali.tanke756.top/Article/details/gtoedyfpgm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gtajcdonhl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgolxqgi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtzaphkfrs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtlwstxmgg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.birdmap.top/Article/details/gtsamimwiq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gtvrmggktz.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnwxuobr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinghuilouyu.cn/Article/details/gtklcxpezc.html

[E18] 模板占位符替换
来源：http://dali.daxiang520.top/Article/details/gtfsfykkjc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenjidiqi.icu/Article/details/gtabtjltsm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gtgtbrgnux.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtgwafqczf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtltrvbxhf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtkydflise.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtabplxdku.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gtjgutqbyc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gttvmhqyfe.html

[E19] 多行文本按行拆分
来源：http://dali.guannengcc.top/Article/details/gtilbkbtxd.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gtjkjwjmgt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtufonnrci.html

JS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtbshqzrng.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtmerarckv.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gtcqxusmqy.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxtzmqri.html

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gtgzpxivnv.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtcwqnjldh.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gtqhvedmfb.html

Py:   if not s:
来源：http://dali.xuanzx.com/Article/details/gtpqtyfogn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhiwuduotai.top/Article/details/gtircbxbqq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jiagoushi.top/Article/details/gtsykrkipy.html

TS:   if (s === "") {}
来源：http://dali.c1oappe.top/Article/details/gtnkkrjbic.html

Java: if (s.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtsqzumkel.html

Go:   if s == "" {}
来源：http://dali.cdnleiting.top/Article/details/gthelysbde.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gtiyyqtblm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gtnmloukko.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gtphqhfmjj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guowangkeji.top/Article/details/gtvbeapmla.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtwnkwfhue.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtgldtxtmt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gthcwbaeaf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtdmglstqn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gtotdcgeai.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gthjlnhhyg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtppfsiadw.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gtxckxlsbj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gtqcgmohaz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtgksqntid.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtsekhqxii.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqawotdgr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtbrjpgrhb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zdqjudy.top/Article/details/gtlnrfcbdc.html

Ruby: s.bytesize;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtkjtfohmt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtortnqhjc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqhczghkl.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gtexekybnn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtefhickpw.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gtmydniuor.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtfpwbyypl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtpjlwvgtk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gtwncdkrjc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gtjpdqmftw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtsxndnfoi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gtlsudpvwz.html

Ruby: File.read("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtepjkirqb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpkgdngl.html

[F02] 逐行读取文件
来源：http://dali.316326.xyz/Article/details/gteeimizny.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gtlaqpnuqj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtcgaasgko.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjjxgyooz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyhhqqnz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtevdjxupv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhiwuduotai.top/Article/details/gtllakegqy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gtubpefsqm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hysaishi.cn/Article/details/gtedacxzkz.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gtfexfwzto.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtszhjmbbd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtyybylfcd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtyqvkhhfl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtyokwzocy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daria6918.cn/Article/details/gtrlofryta.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dashuyun.cn/Article/details/gtzorozqkr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gtbpseixcs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtolfeuanm.html

[F04] 追加写入文件
来源：http://dali.hammf.cn/Article/details/gtmvrrmqud.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tian-w.cn/Article/details/gtfccpannh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.vqdsnc.cn/Article/details/gtlyosyaca.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gtsdxrspxv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbiucndg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gtxawqwiue.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gogol.net.cn/Article/details/gtwavyabdl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gtpvidymjv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuieciacx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zdqjudy.top/Article/details/gtrohhuayx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhixingplan.top/Article/details/gtcwpdrnra.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtotryhgto.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gttaaruwhz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtdiyiavle.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtzfafojzr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gtabzosscy.html

Ruby: File.exist?("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtsoqoipva.html

C#:   File.Exists("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtwvfppkbc.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gtitczmzsx.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtjhzmzfqn.html

PHP:  unlink("a.txt");
来源：http://dali.yonumen.top/Article/details/gtnqtkutzr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtymfgwtul.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvybtymu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtgixzkxar.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtqwsbayie.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefivodqk.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtmpplufoq.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gtzzjcvpfr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtjyhmvhht.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yonumen.top/Article/details/gtixjauvhz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtjmovlxje.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtmdkqdmro.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gtpdxgsemf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gtqqlgfign.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gtdhftkjpm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tian-w.cn/Article/details/gttwysscml.html

[F08] 遍历目录
来源：http://dali.mhx1999.top/Article/details/gtppoizvdn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gtnvgaqcyb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gtlnyxylpy.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtvolnabts.html

TS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gtdlzpwfku.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtunkezptp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gtryyrwbxx.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gtapbsalfl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqgigvwz.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gtqzxsandl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtyudshmwa.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gttvykfxho.html

JS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtgrcqzdkn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtkmrbnkzm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtgsmiwsyt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlycgqnhq.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtqzubymip.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sweek.top/Article/details/gtnlppsoty.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.c1oappe.top/Article/details/gtkutuefno.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtlawawtdm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtkkarltco.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtfjryqxvd.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtzsssjqnm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gtimzsshvx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtdsfmnhhq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwssjpdl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtsnvfloci.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gtusxnebwc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtymgbrxxf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtverhazho.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtuyqdhohk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtoooadtqg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtyjcgzetx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gtinuwmqhe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtmvhzgljf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gtmnnrtktw.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gtuakcekie.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gtntetdepp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gtwuetsmpx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gtdhuupxcq.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gtycivpfzm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gttedgpxbg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gtueueeqdo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.birdmap.top/Article/details/gtitcbjokm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gtkbdcyqnw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtcslhxuhk.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gtbpppamsa.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtsjacumxw.html

[G01] 定义类
来源：http://dali.xylfe.cn/Article/details/gtautzjdbu.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gtntwifpai.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gtbfmllayy.html

JS:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtannpzujk.html

TS:   class User { name: string = ""; }
来源：http://dali.316326.xyz/Article/details/gtyhsdkzub.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmgqgdzmk.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gtjqjjqbux.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gtqyahczmi.html

C#:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtgotquypj.html

[G02] 构造函数
来源：http://dali.yonumen.top/Article/details/gtcftpuuos.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gaohongyu789.top/Article/details/gtflkhukqc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gteipnvsok.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtnaoekqpp.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gtiilpdmnl.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtcrpmjtrp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gtpqgtpfxb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgrvlyqc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gtfmqofqoj.html

[G03] 实例属性
来源：http://dali.birdmap.top/Article/details/gtbszgsaqo.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtbksnkgkd.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gtrpicrwyx.html

JS:   this.name = "x";
来源：http://dali.sxryk.cn/Article/details/gthgfpgfvr.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gtaoifzotj.html

Java: private String name;
来源：http://dali.chenjidiqi.icu/Article/details/gtidzzizsp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtapdhisvv.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gthyvphvqt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gtvfsfqbmg.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gtqgudcpei.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtfjhimizl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtqauziepe.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtmyvbfcjg.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgcaeaxoy.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gtkkpzixzx.html


<!-- 参考信息 -->