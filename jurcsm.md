代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtoenimueu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtawezmaly.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtjymcponb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtwgjlmhiv.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258.top/Article/details/gtgqompqyi.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtqxvpcpne.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dianchejie.cn/Article/details/gtdyalzgxz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtmzchxvlj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbhxjong.html

TS:   s.split(",")
来源：http://dali.zhixingplan.top/Article/details/gtffiauoaw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gtmpmyslpa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.snrcjt.cn/Article/details/gtmabkdwmm.html

Ruby: s.split(",");  s.split
来源：http://dali.zhengqikj.top/Article/details/gtcvkdxgss.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.andypj.xyz/Article/details/gtpzwvuiuo.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gtifjcnkxt.html

Py:   ",".join(items)
来源：http://dali.hongshengwenyu.top/Article/details/gtrertveze.html

PHP:  implode(",", $items);
来源：http://dali.zhengqikj.top/Article/details/gtoitlfyyq.html

JS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtcmzpilsx.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gterdhjiiv.html

Java: String.join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtktcbclxh.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gtsaucswrt.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtfccmrmcq.html

C#:   string.Join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtseutxwgd.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gtdsflsyte.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gtznglnntn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.iojbl.cn/Article/details/gtlzidcccf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtfuegoeza.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gtcgajxcps.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gtmdwojkan.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gtgbmfrsed.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yueranfly.top/Article/details/gtpxsekoxo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtjvffouci.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenjidiqi.icu/Article/details/gtmgjuhvpz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zycfv.cn/Article/details/gthfijtwwe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gtempvjyjc.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtibfietyz.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gttwsjvbcb.html

Java: String.format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtekgtfnub.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtovqzaygn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtnslsabot.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gtbtiafske.html

[E11] 反转字符串
来源：http://dali.aibaodan.cn/Article/details/gtewinvxvl.html

Py:   s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtmaplrsdn.html

PHP:  strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbailxtgd.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgajduoax.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtxjkbxawl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkytloaky.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtcakkkizy.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtrcftrsix.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gthklffmpq.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodrgzaop.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtofjkvwrl.html

PHP:  substr_count($s, "a");
来源：http://dali.fzhhl.top/Article/details/gtszyyvcdm.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtjsgzuvwl.html

TS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtmxvjnmyl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gtxdknlbri.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gttwnjbhwy.html

Ruby: s.count("a")
来源：http://dali.yanxiufei.cn/Article/details/gtmhoqfpml.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnqzz.top/Article/details/gtqogxumwd.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gtbydoyjke.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gtiuqzohgq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gtjgokwlsn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtqjjtxffz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtltdvcgrk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtqkdzhdes.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gtszjwsxje.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ybcxt.top/Article/details/gtkvgewasj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtdbabjbuu.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gtrnnmquoc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgfzy.top/Article/details/gtldxdltcy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xziqi.cn/Article/details/gtfyzexydi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuanzhike.top/Article/details/gtzycobfvw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gtbswbyzrm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.redwolf501.top/Article/details/gteqokonym.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gtxmoubhpx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guowangkeji.top/Article/details/gtzgrtadbp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gttvbnpkpf.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gtuhvjwzad.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jiagoushi.top/Article/details/gtoxjgklhk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zdqjudy.top/Article/details/gtohngbctg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yangfankeji.com/Article/details/gtsxlhimpc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtuksdpvfl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shuidangran.top/Article/details/gtbkvpbzej.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hywenlv.cn/Article/details/gtennabcsx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gtgojnbhkt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pycfn.com/Article/details/gtkofffxbv.html

[E16] 数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gtpllawnve.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxrwlzlp.html

PHP:  number_format(1234567);
来源：http://dali.havefunace.top/Article/details/gtbkydzpkc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gthcfiyrvg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtckblacpb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtdylbnztc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xylfe.cn/Article/details/gtrbdunflf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gotoacloud.top/Article/details/gtwfcszbhu.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gtdlxlsoyt.html

[E17] 首字母大写
来源：http://dali.yueranfly.top/Article/details/gtkmhqqvrp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhongyouzk.top/Article/details/gtgmjurswi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gtyzlhxmxl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtsyhdjnks.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtcscadxty.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gtnrmjspjj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtvszfscpo.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gtgfidaxfq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jiagoushi.top/Article/details/gtdwcqmszw.html

[E18] 模板占位符替换
来源：http://dali.zhongyouzk.top/Article/details/gtbqmmmsbd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gthrfmuyyn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuanzhike.top/Article/details/gtkciopqaq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtxhdgjszz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtvkuuvxgz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtiymadohm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtcqabowqr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gtcybwwuuy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gtzdyeygdu.html

[E19] 多行文本按行拆分
来源：http://dali.yonumen.top/Article/details/gtzicvldqq.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gtnudljcpn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtgvuiwxkt.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtcewaohqe.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gttmbwfzmu.html

Java: s.lines().toList()
来源：http://dali.gotoacloud.top/Article/details/gtdiuyalvx.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gtlejelanf.html

Ruby: s.lines
来源：http://dali.andypj.xyz/Article/details/gtrydsoggj.html

C#:   s.Split('\n')
来源：http://dali.jqgfzy.top/Article/details/gtsztjytgn.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gtecehjaov.html

Py:   if not s:
来源：http://dali.hongshengwenyu.top/Article/details/gtbenamjze.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gtqqveqrwd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwhxfqcd.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gtxuqnavod.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuuyqpqyx.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gtihjiqitc.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gtcjoyacke.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gtbhlcehfv.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gtivifruqs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqpgdtxk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtrxaunnji.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtsudkkkkp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtbnspufem.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtmxnwditw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gttxmqhfll.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtllauqywj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gttycttwin.html

[E22] 字节长度与字符长度
来源：http://dali.shangyingyoupin.top/Article/details/gticsbkmpc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ppjwa.cn/Article/details/gthlnzlzfw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtzqcfnpkf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtlaoglruy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtewujkxal.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtwxzgyoqd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yongpay.top/Article/details/gtdweaftxq.html

Ruby: s.bytesize;  s.length
来源：http://dali.iojbl.cn/Article/details/gtrxrpmtzp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.meibo888.top/Article/details/gtbrsimojb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrxxzsalp.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gtmtxloqac.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtcxezhiyc.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gtyoxwlhiy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gtzvkgtqnw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtgmlyiotx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.haohaochexian.top/Article/details/gtozawccyo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtmupnipvl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtnajckvot.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gtwhztviri.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtyawwccxa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtvhwwlffu.html

[F02] 逐行读取文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpjlabev.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gtjormgmyu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gtlhyhpsho.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtxrnzidjy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtkimmyixg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvbczald.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuanzx.com/Article/details/gtlqikmjhx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gtsspqexun.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fengsongda.top/Article/details/gtjyqqaihl.html

[F03] 写入文件（覆盖）
来源：http://dali.dashuyun.cn/Article/details/gtkpyxpbor.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cheryme.top/Article/details/gtkivqfmbs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gtatlorvps.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtoaaagmgm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtoqpdfegp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtvgmojpds.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tianlin.xyz/Article/details/gtdukbomha.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfkzzaom.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gthyalihii.html

[F04] 追加写入文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgvtbdtn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtoozxiazy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gtjmgdiwxn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtunphcing.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmykwwyxp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gtnaouylpp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtxdczodrj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigufen.top/Article/details/gtafawnnvp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258888.top/Article/details/gtdsfcqxdx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zycfv.cn/Article/details/gtfdrmjamf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aizwys.cn/Article/details/gtfuvxjujr.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtfwfbyasf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtwmlphxcq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtxdftgsva.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtfseiuijs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gtyvojwfga.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtyzcqeztu.html

C#:   File.Exists("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtpwzzypqc.html

[F06] 删除文件
来源：http://dali.birdmap.top/Article/details/gtttxltexx.html

Py:   os.remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtduukvmme.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258.top/Article/details/gtfxjsyhar.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtxgfdyldm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtgejjircp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtxaxdszjh.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtyvjwqvhn.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtsebulkru.html

C#:   File.Delete("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtxerrasui.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gtqflqijkh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtbdslwfqe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gtwygmubwd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdxlgmam.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtzcqycvvu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jyoumei.cn/Article/details/gtdooegvlu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gtuhevxgob.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gthhvqdasl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsgosmid.html

[F08] 遍历目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuigytlk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gtzuckzxor.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cdnleiting.top/Article/details/gtoianmkwp.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopvlorto.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtwxpfjgmn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtgclncofo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuxming.cn/Article/details/gtmldzuwoi.html

Ruby: Dir.children("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtkjyztncx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gtjcbweiaj.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtzbjyzwxt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtwayxwhuz.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtxkvdiugu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gtlnlgrxzx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtvgjjhsxc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtljmmkbrc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gtgudcokqz.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtozkquled.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gtyjqnkjow.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gtvnevyqfb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtfepckpmc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtxaroylbm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtummquftg.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtkywjrnia.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.svipenyu.cn/Article/details/gtbnorrsaz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtccbgpzeq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtuyadltwg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtzbzbhgby.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gtjhbhtivf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtqhaghgaz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtiukvmxuy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtozptuelv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtvljacwur.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtifvcwvtz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.andypj.xyz/Article/details/gtcmpiycjv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgubafhc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gtxdyynfcs.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gtkxtbloln.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yongpay.top/Article/details/gtefwagwnl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxuanxn.top/Article/details/gtsojnxtzs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gtdybshrnj.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gtjaeybztv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gtunfgkegn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gtiqtgzdwq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gtneigpdbs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzadjmauh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtjxbzyoiy.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gtuglctejs.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmbqjbrri.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gtwnlksclr.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gtbxnkrcae.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gtdrlyafyt.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtjkzlqxbi.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gtqcysiiep.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gtrvahbvnh.html

Go:   type User struct { Name string }
来源：http://dali.hywenlv.cn/Article/details/gtckbiyhja.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gtxgwvoppg.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtglgoriof.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtxaebmfeo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gtukrwtmad.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tianlin.xyz/Article/details/gtpdakionx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtcifacyyo.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtwumvxwnj.html

Java: User(String name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtszsabtry.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqerrqut.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gtzpbulwdi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlwxfhsbw.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gtyryizeyi.html

Py:   self.name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtrfmpioes.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gtdgvqfjfw.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtyngzlahf.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gtkoczaanb.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtwzmbxphp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gtzcljvxfr.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gtblnqhurl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gtlefxvoah.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gttkyytmxu.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtbkrdjssj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtfnwmdsqy.html

JS:   greet() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gttmzcrzzu.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtkvxkbqhe.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtrocykhlm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtmbzpofra.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gtrfhffnwr.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtendjwryo.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtzoubkhcn.html


<!-- 参考信息 -->