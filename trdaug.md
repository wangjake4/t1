代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.pycfn.com/Article/details/gteyajyjcm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shangyingyoupin.top/Article/details/gtefnhjhmp.html

[E08] 数组按分隔符合并
来源：http://dali.c1oappe.top/Article/details/gtjhgujoip.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gtevziyixe.html

PHP:  implode(",", $items);
来源：http://dali.gaohongyu789.top/Article/details/gtltzkrvhb.html

JS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtkiapvnzn.html

TS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gttxkcfqgv.html

Java: String.join(",", items)
来源：http://dali.nwbrower.top/Article/details/gtuxnaqsot.html

Go:   strings.Join(items, ",")
来源：http://dali.vqdsnc.cn/Article/details/gtzbxlfmxs.html

Ruby: items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtmdnijhll.html

C#:   string.Join(",", items)
来源：http://dali.havefunace.top/Article/details/gtgvtbqdwg.html

[E09] 去除所有空白字符
来源：http://dali.jlsjyb.cn/Article/details/gttzwurotr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gtqvaqcjbu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.c1oappe.top/Article/details/gtsiegietd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtnodwaqub.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gtxjbfnjuu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.iojbl.cn/Article/details/gtzaqyddbq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxinkj.top/Article/details/gtpljyrzef.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtppioqepn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtumviumxe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gzhubu.top/Article/details/gtcqsnayhw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtobmtemfr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gtudywjbvh.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gttiytwowj.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtrrjdoeyl.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtcaufuepr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtggbqfzhf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtuugbwcpv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gtdqlrpmcn.html

[E11] 反转字符串
来源：http://dali.yj20258.top/Article/details/gtvwztgzsj.html

Py:   s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtilmlmmas.html

PHP:  strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtsilagwxl.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdxfzatw.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtqegkfwab.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtrtvovfkq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gtflrdzbcj.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtxbkanuoy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtskzifoqj.html

[E12] 统计某字符出现次数
来源：http://dali.yonumen.top/Article/details/gtaejsjndu.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtsjmkungz.html

PHP:  substr_count($s, "a");
来源：http://dali.cucudq.cn/Article/details/gthizbdfah.html

JS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gtmtdsafna.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtdslmvnge.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkwgnpno.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gttaipscyp.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gtikrxzfnc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ybcxt.top/Article/details/gtbqmkiujx.html

[E13] 逐字符遍历
来源：http://dali.c1oappe.top/Article/details/gtncxxsiis.html

Py:   for ch in s: print(ch)
来源：http://dali.cqqwz.cn/Article/details/gtpcjfwzjt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtknjazlhi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtcyzamczr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtxtzcrhub.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gtiudptzxx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gtpqbmffia.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtlnpaamtm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnwdqfron.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gtwjznsnpc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjgodonc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gtkmmzipns.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzydpqcx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnqzz.top/Article/details/gtyzplhqni.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.meibo888.top/Article/details/gtizjjngft.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ehwqpu.com/Article/details/gtwlystaos.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.haohaochexian.top/Article/details/gtwwlpmgfg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gtqzsexgzz.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gtmjavpych.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gterrbwdch.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.birdmap.top/Article/details/gtfrgucqyr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtngmcsv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258888.top/Article/details/gtjokjdzpe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sxryk.cn/Article/details/gtylglnecq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258888.top/Article/details/gtehhcqbrm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gtkaojlxaz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gtwvtelksv.html

[E16] 数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gtzentivbr.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gtzqnnntjm.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gthvagqwno.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtezfpgbll.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtrzxkzavv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gtsdnuhlwb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxinkj.top/Article/details/gtuqrrfhlz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.bjfxy.top/Article/details/gtzfixfbwd.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gtpursopuc.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gtxfgyjjjg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gtfvvcblib.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yvedp.cn/Article/details/gtnohivfad.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtdngqoeui.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtqstyygty.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gtcyretkgr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtpmxdwvcf.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gtsxermztn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.iojbl.cn/Article/details/gtirhfodjq.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gtrbptzicz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gtdhbhhrbk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daria6918.cn/Article/details/gtjxxcgxne.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtxcgclbdi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtuhliwopa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtcjttyfuw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtuuvyrjbe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gtthlfdajk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gtrnvkaozg.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gtrjcwkiex.html

Py:   s.splitlines()
来源：http://dali.hywenlv.cn/Article/details/gtgbmdznid.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gtxdrntmwg.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gtefvvjvpq.html

TS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtjgslnnmi.html

Java: s.lines().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtvbjhfqfz.html

Go:   strings.Split(s, "\n")
来源：http://dali.yangfankeji.com/Article/details/gtbqyjbpad.html

Ruby: s.lines
来源：http://dali.vqdsnc.cn/Article/details/gtnqishanq.html

C#:   s.Split('\n')
来源：http://dali.yanxiufei.cn/Article/details/gthwnupylu.html

[E20] 判断字符串是否为空
来源：http://dali.nwbrower.top/Article/details/gtfpszmfnr.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gtqhdtjxpz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgufenzy.top/Article/details/gteodudgax.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gtwkeiepzk.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gtiyhjkqtk.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gthkbsceok.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gtvbpwpjji.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtibnezlnf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtuqsqiiev.html

[E21] 超长截断加省略号
来源：http://dali.smart0.xyz/Article/details/gtwhugockg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtgbyotjkf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtbturqgpe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtefwvisur.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtikepxvsh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtuucctkyd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hysaishi.cn/Article/details/gtfgeabeym.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtdezwofeq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtioxujzrz.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigufen.top/Article/details/gtckyustoe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtmimavdig.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gthmljnaxe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtkgsekcpr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtcdfyemtu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtpleshzoc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gtuicpdyvy.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtvzkiuacw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtdgurleyh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtyugeqcns.html

F. 文件与目录
来源：http://dali.andypj.xyz/Article/details/gtljirkjvy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtdaccepzg.html

[F01] 读取整个文件
来源：http://dali.svipenyu.cn/Article/details/gtedvqtlif.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gttggmuzbc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yonumen.top/Article/details/gtvvbcsknx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gtmbyqutev.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtvfjtoiww.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtkwpdcrwp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gthymwambf.html

Ruby: File.read("a.txt")
来源：http://dali.316326.xyz/Article/details/gtkmliuxck.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtxneaxdvo.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gtctlvwqyt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gthcrcvxao.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtovjfemvy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtngdnlwxl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuawyxgxh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gtwiboeimb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gtephebala.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hongshengwenyu.top/Article/details/gtywsenpyq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pycfn.com/Article/details/gttgrraoyo.html

[F03] 写入文件（覆盖）
来源：http://dali.zdqjudy.top/Article/details/gtffyjbfzs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gtpcuwjufj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtgbvteunm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtfwkwlisx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtskvxxppl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj202588.top/Article/details/gtyarrvsbn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gtiqguevvm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.snrcjt.cn/Article/details/gtubspqnck.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gteybzfevi.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gtygkylyef.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtdynavnox.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhoulong.xyz/Article/details/gtrwgydhrx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtqbswvfpd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtekqigygo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gtmofdpqsn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gtxwnfssko.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gtqiwcqico.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hammf.cn/Article/details/gtybplgksb.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gtbiotnuhl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gtftgcmewg.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtowjlbacv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gteywyjrer.html

TS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtflnxvdwg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtwvjkgvya.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gtpicavzup.html

Ruby: File.exist?("a.txt")
来源：http://dali.sweek.top/Article/details/gtxstnzava.html

C#:   File.Exists("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtfgywzgtl.html

[F06] 删除文件
来源：http://dali.chenlongwang.top/Article/details/gtqgdlbwcb.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtouckvbuj.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtbhkxqret.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtswcgwuzx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtnlgusbgl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtzargpeeh.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtlzwueets.html

Ruby: File.delete("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkhynqde.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtgxtwdjbl.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gtadatqxts.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtpyqciheu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gtgdsquwnx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtoxjkailt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtuoevhnzy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhiwuduotai.top/Article/details/gtxpcfumey.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fengsongda.top/Article/details/gtldocjeew.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gtzhgfbtyx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gtssikkrkc.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gtnpjuuvnd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zdqjudy.top/Article/details/gtpyicjutc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gtrwukkggy.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtgibcusia.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtzdeanhxt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gtwmdhldzt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gtigjvdjso.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkzmmqzd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.iojbl.cn/Article/details/gtjukqogen.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gtqugzdsue.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtspaywjcq.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtjvoyelyh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gttriuwbss.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gtlwrglbnt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtoluxkcij.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbzdcedc.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gtatqltdob.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gtluildvth.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gtmhihpscv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtnyrkbpvt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtjcuiprwd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtsgloasfw.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtlkkrofsz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gtasfrwwjt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtkpmoyaef.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtyoufqtgd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtpnievrly.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gtrjpwucpx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gteqtqspey.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxzzaqnd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtsgpoxujn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsypgazxk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gtyzgeegez.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gtnwoyhmyt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtvrbdwkij.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gtotvrxxqo.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gtbknafvhz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gtjgzojsfg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.kuanghao11.cn/Article/details/gtwxoftcjs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gtoajzwtoh.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtcpstzlhl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gtsupojfad.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.feifeiyinyue.top/Article/details/gthkssnjzb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cqqwz.cn/Article/details/gtgdtnyyjm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sufxvd.cn/Article/details/gtugnugrnd.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtsjctjqtl.html

G. 面向对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnawbcmvq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtadajvgiw.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gtzmflnxyl.html

Py:   class User: pass
来源：http://dali.zhongyouzk.top/Article/details/gtxzcawazo.html

PHP:  class User {}
来源：http://dali.sufxvd.cn/Article/details/gtqmprtdvd.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtkpglrfjk.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gtivgqxash.html

Java: class User {}
来源：http://dali.birdmap.top/Article/details/gtlngyrzvq.html

Go:   type User struct { Name string }
来源：http://dali.yanxiufei.cn/Article/details/gthcioitzb.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gtenmtqgqz.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtklkeuagw.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gtokldsjxh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gtmqhcqzru.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gtfziaaruq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gthodoqbid.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gtvhiguumb.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtrygfnfjz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gtuxopkebh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqylyfcv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtfkjjhxvj.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gtfaenossm.html

Py:   self.name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtdigzzlij.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtnyyqrmox.html

JS:   this.name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtqbyzkdie.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gtmwwaqlpu.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gtxqywoivo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtcvifauca.html

Ruby: @name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtbjeqmebi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xinyue.icu/Article/details/gtuvvxhkkk.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtqxcapecj.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtewjfjuwd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gterncngxx.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtqgjunxqz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtyudzscyr.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtzrqrsrur.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtlgjlamla.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gtbiymjdud.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtabasgaex.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gtwdszaqnv.html

Py:   class Admin(User): pass
来源：http://dali.xinyue.icu/Article/details/gthpzdlhvz.html

PHP:  class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtqmulawin.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtphgsahuc.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtidjiplgm.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtrtrdtleq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gtlliaufvs.html

Ruby: class Admin < User; end
来源：http://dali.jlsjyb.cn/Article/details/gtonzbvpix.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gtplqzyzjj.html

[G06] 重写方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtablelztn.html

Py:   def greet(self): return "admin"
来源：http://dali.havefunace.top/Article/details/gttnmihvgk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtbftlktqx.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtlmryvwqr.html


<!-- 参考信息 -->