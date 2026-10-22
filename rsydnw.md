代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.havefunace.top/Article/details/gtnulahzfc.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtmhrvbmnv.html

TS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtdjgdxkux.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtthnporyu.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmmspytf.html

Ruby: items.join(",")
来源：http://dali.xylfe.cn/Article/details/gtqmsqozqg.html

C#:   string.Join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gteqcycxxg.html

[E09] 去除所有空白字符
来源：http://dali.vqdsnc.cn/Article/details/gtdqortosq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gtigidzgov.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuanzx.com/Article/details/gtvhtzgclf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gttoafrego.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gtwgyktnfa.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gthkmxaohx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdevgyjvy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shzxlz.cn/Article/details/gtpjjsqdlp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gtpwayzznb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guannengcc.top/Article/details/gtfbshphdy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sweek.top/Article/details/gtvifogiim.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.c1oappe.top/Article/details/gtvwwjjwry.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtbjetvpou.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtzoybnlxi.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtaqlhpkai.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtpktjglav.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtetkinltd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenzaomai.com/Article/details/gtawtvvkqo.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gtavlcmyhx.html

Py:   s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtzhaazeth.html

PHP:  strrev($s);
来源：http://dali.cheryme.top/Article/details/gtxrbfqpxg.html

JS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtupistnhx.html

TS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtocmcuzlk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guannengcc.top/Article/details/gtrhriutkf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sysykeji.top/Article/details/gtgscojlev.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gtijgdvswy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtxgklmkyn.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gttniftfkf.html

Py:   s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtnqmaktxm.html

PHP:  substr_count($s, "a");
来源：http://dali.quarkkingdee.top/Article/details/gtchtcbupc.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gtrrfwvqjl.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtrbchsxle.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zycfv.cn/Article/details/gtitjstxek.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvazovowr.html

Ruby: s.count("a")
来源：http://dali.birdmap.top/Article/details/gtgmlbhopd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xylfe.cn/Article/details/gtdzvjlbpg.html

[E13] 逐字符遍历
来源：http://dali.aibaodan.cn/Article/details/gtgtepnfzf.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gtlxdeiurx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmdxibeji.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gtnxvfmilb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyggsypg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigufen.top/Article/details/gttboguygu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pycfn.com/Article/details/gtxrbzasft.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gtpkfdbccp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtshbmlxsc.html

[E14] URL 编码与 Base64
来源：http://dali.redwolf501.top/Article/details/gtmpvkexme.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gtmovgpity.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtfgjfclaj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.haohaochexian.top/Article/details/gtpblqphle.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gtyipcftwh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.haohaochexian.top/Article/details/gthljtcgyd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.iojbl.cn/Article/details/gtkyvdbtfa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gtpojvlfwf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tian-w.cn/Article/details/gtgtlamvdl.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenlongwang.top/Article/details/gtcknrraim.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gtqxyzycuf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnxiangtu.top/Article/details/gteeotjnsb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dianchejie.cn/Article/details/gteaqvusxv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yvedp.cn/Article/details/gtogzphfba.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gtbnrzajvk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gtsxwghrsj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gtooxbnfob.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgufenzy.top/Article/details/gtmnjsfozz.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gteaicrbbc.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtlslqcgfk.html

PHP:  number_format(1234567);
来源：http://dali.guannengcc.top/Article/details/gtumqgonee.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtjxnyqogu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtidzcbjfo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yvedp.cn/Article/details/gtxdfytknq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jyoumei.cn/Article/details/gtycjdoyxf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gtbltvyjka.html

C#:   1234567.ToString("N0")
来源：http://dali.haohaochexian.top/Article/details/gtjmutqrqx.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gtjwrrxetv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gtpgtskatr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuususgk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtytsnsrvk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtgnbobkvj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtkammyitk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gtjyqtsgnv.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gtwewfmdyz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gtsehtcxyx.html

[E18] 模板占位符替换
来源：http://dali.andypj.xyz/Article/details/gtnsokiwtk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.vqdsnc.cn/Article/details/gtaowsvcid.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gtkhamrhdi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtknwdpsen.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtayihcrlq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtiiaghair.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258.top/Article/details/gtoijgfulf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cdnleiting.top/Article/details/gtjkxlbvkx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gtkjsjtjtw.html

[E19] 多行文本按行拆分
来源：http://dali.gotoacloud.top/Article/details/gtivhtdpic.html

Py:   s.splitlines()
来源：http://dali.tanke756.top/Article/details/gtberrbnvs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtdgnhiqrs.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtbnwghgyj.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtgqdivwbv.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gtehsmaxum.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gtfqzycepm.html

Ruby: s.lines
来源：http://dali.zdqjudy.top/Article/details/gtfsetzsjl.html

C#:   s.Split('\n')
来源：http://dali.cashguo.top/Article/details/gtqenhrlfj.html

[E20] 判断字符串是否为空
来源：http://dali.kuanghao11.cn/Article/details/gtlkrysreq.html

Py:   if not s:
来源：http://dali.sysykeji.top/Article/details/gtkjdxuhdy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtlmcotlir.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gtjeyxwirp.html

TS:   if (s === "") {}
来源：http://dali.wangdashe.top/Article/details/gtsosujxmn.html

Java: if (s.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtnxifpwtv.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gtyojsnrnl.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gtthtzckpq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangdashe.top/Article/details/gtgdnlupdc.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gticgivjsd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwginazm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtrbixpjfd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtlhvxlfjx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtwxymkrmr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtskbzeptz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gtnaswtapb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtjzsnejxa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtjcrwfhin.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljcvefyk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gtkcxriwgr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtawlpmeli.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlctpyvyq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtswmeuoto.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqipodzg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenlongwang.top/Article/details/gtguytxfsy.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gtrlnqnwqg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gtykvqyfhx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtmsllmlyg.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gtwpwjfyay.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtvdtwrark.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtibakqcas.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgfzy.top/Article/details/gtbpmgpwpw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvunodsu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hysaishi.cn/Article/details/gtsrgtubmy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gtjhmrtncp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtvbjjphif.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gtbqsvprbn.html

Ruby: File.read("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtidkdsoaj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtyhcxgmyf.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gthmtgtxud.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gtpcjwlibj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gtovxhwjcy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtuvnqpdoh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtqpwyytkb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtfeaowtzx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.kuanghao11.cn/Article/details/gtzweteyyl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sxryk.cn/Article/details/gtgpnmglks.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuxming.cn/Article/details/gtgzzkkrpi.html

[F03] 写入文件（覆盖）
来源：http://dali.ydzc1.top/Article/details/gtmlesyfyx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gtrchpvzcn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtmqmguyad.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtflwvkrtf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilarhooo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.andypj.xyz/Article/details/gtauexxvzi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpozjgibr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ybcxt.top/Article/details/gtqhlyvzdy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gthoraqiyo.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gthgdvluhb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtntvhtozo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gtfrgavbln.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtdurbucya.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsndirry.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pengpengdd.cyou/Article/details/gtvzjgfaoz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jianghu66.top/Article/details/gtbdrvnnel.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gthdhvduax.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gtyrwtiucg.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gtcdqwwodn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shangyingyoupin.top/Article/details/gtquttincv.html

PHP:  file_exists("a.txt");
来源：http://dali.sweek.top/Article/details/gtcvmycyvv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gttexmpgzm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gttqfjqygk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtkwoxrfre.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gtyxirrgip.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtxzudkusa.html

C#:   File.Exists("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gttixbnxvu.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gtjofsvlfs.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtomrpkbid.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtczlvjixk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtgoxcjtda.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtyoedhzph.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtuanxarof.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfueldplb.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtxhufdexd.html

C#:   File.Delete("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtmnlyurns.html

[F07] 创建目录（含多级）
来源：http://dali.316326.xyz/Article/details/gtzbmbruoh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtomrrbahi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtnjkftyov.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfirkpbh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gticvzbvwy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ydzc1.top/Article/details/gthsuoabyx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xinyue.icu/Article/details/gtkbedfbmh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ehwqpu.com/Article/details/gtnnrnjdnn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gtcipqtumo.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gtbmchfwnb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gtjylzzclm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dianchejie.cn/Article/details/gtlvgfjnbm.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gtmkphdowk.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtmyowpkvo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtikddcbfh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtchvkqvff.html

Ruby: Dir.children("dir")
来源：http://dali.chenzaomai.com/Article/details/gtoxyahiie.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gtnzpqgrds.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gtsjmgkedv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtuhisohjp.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnixcwvtk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtxziawdad.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtekecmazn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gttdrrihqg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gtmbzjhmlz.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtobnteylt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gtamlflzwj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafsqxqtq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gthltaqpuj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fengsongda.top/Article/details/gtxicrbyfj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtfuoavtel.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gthxupzlab.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.316326.xyz/Article/details/gtrsgqewxc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtfapzqzxo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtmrprmean.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtszqvkfhj.html

[F11] 复制与移动文件
来源：http://dali.quarkkingdee.top/Article/details/gtljxuzzzx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtdgmbzanj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gtnhbiczej.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtvknkzpgz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtwcqlgmin.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtxhdskiqk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gtgoexaaqe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtzvvoefnt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gtndctrqun.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gttiewinbd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gtxxbfbduy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gtlylbmjtb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gtgrbmljcs.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gtmewoodzg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gtciaexghh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gtmwhjehwd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ivvv.top/Article/details/gtfhpgbvid.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gtbyqoiane.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttduabpxh.html

G. 面向对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtaoxkahkq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtzpibvdmi.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gtubphprcs.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gthysplkio.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gteafwtmly.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtwjbwelue.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtidlxwcxr.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gtmwyeaitn.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gtmazbexek.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtzerovrvw.html

C#:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gthcjlnsds.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gtjbkabayb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gtqxnobaub.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gtqartsavy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtbhmbqhfj.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gtlqgflzdx.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyzcowroi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gtxouutvpd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtzqttwbdr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gttbsjomer.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gtnuaiurja.html

Py:   self.name = "x"
来源：http://dali.daria6918.cn/Article/details/gtjkiglkux.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gthhxzhyuk.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtthwbgpfa.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtygnlbihs.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gtuklkvlqg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtsunebwyb.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gtjiqkjtcq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtmmwjyqiu.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gtyldssbkw.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtjspmydpy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqbkwecoj.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtwwnscyof.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtkdibtmjb.html

Java: String greet() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtnjizcfqg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtunyxnhro.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gtflumxgct.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtjhdqjerh.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gtldxkivcr.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtacknuvzm.html

PHP:  class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtegrqybtj.html

JS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtuoduqvjk.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gttuahpjfy.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtgufjecpo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cheryme.top/Article/details/gtegeskcac.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gtrchidoyc.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gtmczvjywx.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gthnenoiay.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gtpukxrghp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtxpizpvpc.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtxmcceovf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtqmybfnzh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzhedldn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhengqikj.top/Article/details/gtqzplohlb.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gtmllnezup.html


<!-- 参考信息 -->