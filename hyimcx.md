代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.fengsongda.top/Article/details/gtoyufnryy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jiagoushi.top/Article/details/gtxypijeqr.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gtbyhhcsai.html

Py:   ",".join(items)
来源：http://dali.yonumen.top/Article/details/gtkdxvthoa.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gtyavhjlir.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtxrxcurep.html

TS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtzwonypkd.html

Java: String.join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtkpdnehte.html

Go:   strings.Join(items, ",")
来源：http://dali.wangdashe.top/Article/details/gtnxfjqmwy.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gtmxroytkt.html

C#:   string.Join(",", items)
来源：http://dali.316326.xyz/Article/details/gtrmgoqlfo.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gtlmpggmjy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgocsztpr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xylfe.cn/Article/details/gtagiclbpi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gtitiqhopa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtixjwwtnb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtqqvldynm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj202588.top/Article/details/gtmmgnraml.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gtofkjeqnl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtfehsrwgw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.smart0.xyz/Article/details/gtsvmoqpzg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258.top/Article/details/gtcpjudqem.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shangyingyoupin.top/Article/details/gtuvbsllgb.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtkcvywikk.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtlyvciveh.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtitphdthd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtutoehoyj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtynxqmvry.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cdnleiting.top/Article/details/gtqvobrsth.html

[E11] 反转字符串
来源：http://dali.bjfxy.top/Article/details/gtfwgbgwho.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gtbtjqdeyc.html

PHP:  strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdlzdcaf.html

JS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtntkymxlq.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtuyduyxdl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gtlstjolka.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtkgrkzsrc.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdhqhktj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtrknqgaqf.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gttmanmyon.html

Py:   s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtpxafmaku.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigufen.top/Article/details/gtpzfiowrp.html

JS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfebffcbh.html

TS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtrqmjixfp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gtfrdwpzga.html

Go:   strings.Count(s, "a")
来源：http://dali.xziqi.cn/Article/details/gteypvvxqn.html

Ruby: s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvkqdvgb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gtupgeutdy.html

[E13] 逐字符遍历
来源：http://dali.nanxinkj.top/Article/details/gtepuofrle.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gtdshfkgds.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmynpkfco.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtmteyrgbc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuntxtoeb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cheryme.top/Article/details/gthrlfocfd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtsigwrluq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.havefunace.top/Article/details/gtzrwpjmtk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xziqi.cn/Article/details/gtdvghtbsb.html

[E14] URL 编码与 Base64
来源：http://dali.jinqigfzy.top/Article/details/gtgytdtzrt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtmydakvae.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ehwqpu.com/Article/details/gtdblikydp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ybcxt.top/Article/details/gtyqnbimpn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gtynxiyinu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtsdfklwfg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aizwys.cn/Article/details/gtrjukzgmt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gtykoynzkh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gtvlgdjwbw.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtijrpcbmq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ivvv.top/Article/details/gtizfkzepa.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtqgzjzcjr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gtyipezoqb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zycfv.cn/Article/details/gtexnsyikc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gttklmrmjc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gtkdtbphyh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gtmipcxsbj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dianchejie.cn/Article/details/gtfrywsiph.html

[E16] 数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtksqpnsji.html

Py:   f"{1234567:,}"
来源：http://dali.ivvv.top/Article/details/gteixobliu.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gtgiafjtom.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gtpcoxjkfc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtcgeatkws.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtcqbxqaxk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shuidangran.top/Article/details/gtenempfrv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gtrxjxyusn.html

C#:   1234567.ToString("N0")
来源：http://dali.sysykeji.top/Article/details/gtkvgfvhza.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gthaikjahm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nwbrower.top/Article/details/gtnfnzxcat.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258.top/Article/details/gtyctzymrg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gtkefayjns.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtijsnrsjp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aizwys.cn/Article/details/gtwdygvkah.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gtatidagdq.html

Ruby: s.capitalize
来源：http://dali.daxiang520.top/Article/details/gtnrlqvyom.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xziqi.cn/Article/details/gtgcuvxviu.html

[E18] 模板占位符替换
来源：http://dali.birdmap.top/Article/details/gtjiqnzimc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gtavaknkbe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jiagoushi.top/Article/details/gtmjqrxchc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtgiuxzjoc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtjzvlfoec.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtfttegwej.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gtpbxbamtd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yanxiufei.cn/Article/details/gtnzwnmyar.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gtoqfpidwn.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gtfcjyjvja.html

Py:   s.splitlines()
来源：http://dali.jinqigufen.top/Article/details/gtbvgsctpt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cheryme.top/Article/details/gtgssrensj.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtmunuaaga.html

TS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gtyfkqrato.html

Java: s.lines().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtidwvsdip.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchlzjrwo.html

Ruby: s.lines
来源：http://dali.xylfe.cn/Article/details/gtsstacvwk.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gtfujqikoq.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gtqucyhvbb.html

Py:   if not s:
来源：http://dali.zdqjudy.top/Article/details/gtxkktbwht.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnrjgvhh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gtsrchwktm.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gtsqfzdzrh.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtpriootcp.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gtqpmczkzk.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnejdztng.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jiagoushi.top/Article/details/gtiflxoshe.html

[E21] 超长截断加省略号
来源：http://dali.aizwys.cn/Article/details/gtbuzgnute.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gaohongyu789.top/Article/details/gtbnlvpzed.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtwteitlpt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtwiwjmmsv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtziaaujlj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtgtblvokg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gtizbhubus.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtlosxmpfa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwaxeewt.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnygttom.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtfjrnehav.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gthhoxxhor.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtnuiiueaz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtlrmxfpwf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.iojbl.cn/Article/details/gtgjjdxgqp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yonumen.top/Article/details/gtwbajapvb.html

Ruby: s.bytesize;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtrlawhayl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.0kj1m.cn/Article/details/gtupyqmmvf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtormughmr.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gtqbfgveho.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gttmatkvcn.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gtsqjjaiak.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shzxlz.cn/Article/details/gtyiemhbld.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtulllcntz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gtoblibken.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtesovhtyr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtlcsdrydh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gtnlyibfyx.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtglsrusfl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtunnpgcvw.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gtvgfoobru.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gtrhzkwcrq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gtifkpkdns.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gtteyziepm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtybcueyoz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtokjgvelp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gtnmpyouqy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gtktvybbqd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gtikklsles.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gtakcuzznr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guowangkeji.top/Article/details/gtmgwvzbfe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtfeoarqyf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtshimjsge.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtccvpqtla.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fzhhl.top/Article/details/gtwnngddez.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.mhx1999.top/Article/details/gtzrssgfku.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtagsnraeb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtwvbqifxf.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gtajwptcup.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtqcafibxb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gtzigqvnmd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtuadeeeeu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtaflrpdyt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gtxokhcyth.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtmrgpsfji.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pycfn.com/Article/details/gtboigqzkh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gtegxhxukp.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenzaomai.com/Article/details/gtsqipekpr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.havefunace.top/Article/details/gtclatkaoh.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtuxjtvlog.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtdzzknqcp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gthsxwrvjt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtyqvootof.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gtinjrcsqu.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtpxjicxsa.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtrsqwvd.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gtyjlncbgp.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtubjxcfhd.html

PHP:  unlink("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtuzylcrgm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtqrhjmtcp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtgdjbrbsv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtvvoliqfh.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtrxcnxbnx.html

Ruby: File.delete("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtxcjoiluw.html

C#:   File.Delete("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtvgwkatmp.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gtdpgvefqs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteiiymkjv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtniyzlbgt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtpwezizla.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtoijnpfda.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhixingplan.top/Article/details/gthutjqojt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtzxofchlw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gtznsgcjok.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gtxvwxrqlp.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gttqgwcebs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangshuangyany.cn/Article/details/gtqsexlmfc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yvedp.cn/Article/details/gtpwcgwfnn.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtgkoijzqq.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtjsdaxhmy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtfluiabhl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gtwsvbkbat.html

Ruby: Dir.children("dir")
来源：http://dali.yangfankeji.com/Article/details/gtphlhbyiw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gtayitmnih.html

[F09] 获取文件大小
来源：http://dali.zhoulong.xyz/Article/details/gtqgturrbw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtztkctpjy.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtcmvplpli.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtvztixxhy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtftsxdszq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtwngpusuu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gtmzvxnsbl.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtoyxftehx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gtnjamirsg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gtxgefgpju.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtbnuhombw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pycfn.com/Article/details/gtcvoyxfwv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtnzvfqilb.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gtoosuivyk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtoreedvta.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtzldgpdnz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtixljjjbv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtzrysppxg.html

[F11] 复制与移动文件
来源：http://dali.kuanghao11.cn/Article/details/gtiakdgpmv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtyarhvkuw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gtgnoenxzq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gthxgfyzaa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtdhcvjyuj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yueranfly.top/Article/details/gthaxzovqa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gteafaqbpc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtrhalswjv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jlsjyb.cn/Article/details/gttkmkilhi.html

[F12] CSV 读写
来源：http://dali.0kj1m.cn/Article/details/gtfntpdhku.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gtrqjlvuze.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sysykeji.top/Article/details/gtmqjywnkj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gtzpgnzoie.html

TS:   // 同上
来源：http://dali.hammf.cn/Article/details/gtffennjfm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gtenybpmrr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gtapgopidn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcrrjuqu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cheryme.top/Article/details/gtxifbibbh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjvrlqqqa.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gthddckqrv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtyldooosn.html

[G01] 定义类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvdhqkir.html

Py:   class User: pass
来源：http://dali.ivvv.top/Article/details/gtxzgkwuzd.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gtsrdiirsx.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtaplxsqpo.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gtmcylgmsm.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gtdhlbmbcr.html

Go:   type User struct { Name string }
来源：http://dali.tianlin.xyz/Article/details/gtoakywwav.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiaekifes.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtithfvpjo.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtnfvbsinh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.meibo888.top/Article/details/gtjaoxvgcf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gtzbiuezyg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtyaflcssc.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gtgjdvujgm.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmaeflxyz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gtvpozmhbt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gthxobwjps.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gtkixvotwc.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gtivosunme.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gtxhxvtyhw.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtznlldram.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqelnjiyq.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gtyyxqvizb.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gtpqjicxrj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtqqdxobqb.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gtpgzusevt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gtyfgpkikl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gtspffgook.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtnnhrbhaj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtovlyuutj.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtjcmbvmng.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtkfjwarto.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifmftnpz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtotgelxzx.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtfcvovqea.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhkpwzrq.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gtcyopijej.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gtxrzvwalc.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtuhroczsu.html

JS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtfpwnwlnl.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtcuvnwafi.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtkcbymmfq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gtfycqefjp.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtgkmbswmz.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gtjmdiywyr.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gtewvciddr.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gtlpkpebmx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtqxeudgwf.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtpoyqlqqw.html


<!-- 参考信息 -->