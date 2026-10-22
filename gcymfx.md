代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.nanxinkj.top/Article/details/gtviehgldg.html

Ruby: items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtannsqjbg.html

C#:   string.Join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvozypwc.html

[E09] 去除所有空白字符
来源：http://dali.guannengcc.top/Article/details/gteosgipit.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gtglxnjlhx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yvedp.cn/Article/details/gtnpamvlcv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gtbfklzltk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtipiglyai.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gtbhhrbubn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yvedp.cn/Article/details/gtnvappaqb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cqqwz.cn/Article/details/gtbgqvmujn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gtztxderyk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hfpthk.cn/Article/details/gtvavpwufl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtwbvxxkqk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cqqwz.cn/Article/details/gtpobxmqkg.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtkdgqjzeb.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtlmadgobp.html

Java: String.format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtxlhcpvsy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtxlwtnnwg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtidgxzfks.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuanzhike.top/Article/details/gtxnffpjkc.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gtynojixvw.html

Py:   s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtufwrzvlt.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtuyjklzdx.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtlhgitocz.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gthiuxusaq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.havefunace.top/Article/details/gtijuwlzbw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gtvdljkmll.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtzdlwhput.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtbfytlsfe.html

[E12] 统计某字符出现次数
来源：http://dali.jianghu66.top/Article/details/gtbbrzxnwi.html

Py:   s.count("a")
来源：http://dali.zycfv.cn/Article/details/gtldrnyloj.html

PHP:  substr_count($s, "a");
来源：http://dali.xuanzx.com/Article/details/gtiyvjuehs.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtmsbalruf.html

TS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtoltpmizw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gtihingznw.html

Go:   strings.Count(s, "a")
来源：http://dali.zdqjudy.top/Article/details/gtlhxmbjuj.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtarczxhea.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hywenlv.cn/Article/details/gtnnpgrkxz.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gtyehgsebz.html

Py:   for ch in s: print(ch)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobxjlqdv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtweyqwnmn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtmauadpeh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtfjdhjydu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gtcfvpahwa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouuaxgki.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gtvbarnqsu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtjnloteyb.html

[E14] URL 编码与 Base64
来源：http://dali.dashuyun.cn/Article/details/gtptsmmfzq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtchhzkfsl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yangfankeji.com/Article/details/gtwmdqznfp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gtwjfyzlkm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gtazpbwqkm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gtrngoibib.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gthbmtfmie.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.quarkkingdee.top/Article/details/gtuvuddbgp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtmgnvhcxk.html

[E15] HTML 转义 / 反转义
来源：http://dali.gzhubu.top/Article/details/gtuljnpgoe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yangfankeji.com/Article/details/gtwaxeiagc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gtotcrxyay.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fengsongda.top/Article/details/gtltmtwlji.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtpkrmtrcy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fengsongda.top/Article/details/gtoqcbsbkq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gtojcvlqug.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrqmxhey.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yvedp.cn/Article/details/gtgpbrpflr.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gtuzhlxuty.html

Py:   f"{1234567:,}"
来源：http://dali.xylfe.cn/Article/details/gtaeaxxiqm.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gtqhkyydll.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gteivtoodv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gtleauhgnk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258.top/Article/details/gtwnnxyonh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gtzsebomav.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtqaisdsde.html

C#:   1234567.ToString("N0")
来源：http://dali.smart0.xyz/Article/details/gtthvallpt.html

[E17] 首字母大写
来源：http://dali.yueranfly.top/Article/details/gtxqicwgwg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gtzdvvzvog.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtxjvxegxg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtuipwbmub.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtxbqkofyq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gtsougwvyv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gthnxkpicw.html

Ruby: s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gtjovpewgr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.quarkkingdee.top/Article/details/gtxblhthut.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gtnazcdmcl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jianghu66.top/Article/details/gtmncygbof.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gtmworaiyx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtbkvukpgh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtmalwwqta.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtiooxhxiq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gtqghjqmwe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gtdzpixxib.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gtxpvxotez.html

[E19] 多行文本按行拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtkhoqjszl.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gtnbsninnv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtcnxphawa.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtqsurtorg.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtyqumnbpf.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gtbefucqph.html

Go:   strings.Split(s, "\n")
来源：http://dali.cqqwz.cn/Article/details/gtglkqzvcx.html

Ruby: s.lines
来源：http://dali.jqgufenzy.top/Article/details/gtngskilcz.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gticpfhneu.html

[E20] 判断字符串是否为空
来源：http://dali.bjfxy.top/Article/details/gtahjvkpnu.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gtjdsqorml.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gteeuuqnfu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jyoumei.cn/Article/details/gtdnijkrmg.html

TS:   if (s === "") {}
来源：http://dali.hywenlv.cn/Article/details/gtghcblkrd.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbcqarkmu.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gtgvfljttd.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomsivmgm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jianghu66.top/Article/details/gtlwthjfjr.html

[E21] 超长截断加省略号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojqpkzto.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gtrawmgplo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtinbpjgps.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtptcfpyfl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnnxbhaw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtrcewsoce.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gtapjwbvrr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtgfuohglz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtidxrqdtw.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gtwqnbazor.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.havefunace.top/Article/details/gtogvryzxu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtlxepizmv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtucebmthy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtiangmkws.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtzfgsonzj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gtqxytwkij.html

Ruby: s.bytesize;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtlpvpwddj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gtvsqdhrqj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtisscbphg.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gtzdeblhdv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtzbeltewg.html

[F01] 读取整个文件
来源：http://dali.guannengcc.top/Article/details/gtamnufmyu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gtawqcmysp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtkptstckx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqstrxej.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtjzddkrxj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtolzrjqfl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gtqifdzbxu.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gtoxfpakmr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtrshntrup.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gtscaxqxuo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yonumen.top/Article/details/gtwodsrtcy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gtdneiumfp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtbzafywnm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gtnwhldegw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gttsolhqez.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gthpqyxmuw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ppjwa.cn/Article/details/gtgiiskyfd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ehwqpu.com/Article/details/gtbbwgzqfy.html

[F03] 写入文件（覆盖）
来源：http://dali.xziqi.cn/Article/details/gtruebovkc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hammf.cn/Article/details/gtvayymjkt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtxzpyjdwh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtyvlbvjvx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtlnatsgle.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhongyouzk.top/Article/details/gtefoteeob.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangtech.top/Article/details/gtapfuzjfq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtrzlemzmi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtawlhqmfo.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gtwvqapvuk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrqgseua.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenlongwang.top/Article/details/gtdehytmaa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gtfffxxvmj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtcbeyotoq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.bjfxy.top/Article/details/gtunqjtwql.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daxiang520.top/Article/details/gtbfipqgfb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gtlfimewyd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gtkouytmfc.html

[F05] 判断文件或目录是否存在
来源：http://dali.hammf.cn/Article/details/gttiuofmrs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxuanxn.top/Article/details/gtcqkbossi.html

PHP:  file_exists("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gthcctbxwp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtifgibbrr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtmlilosup.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrauvgwsd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yueranfly.top/Article/details/gtvvrgrems.html

Ruby: File.exist?("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtoppuomvu.html

C#:   File.Exists("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtiipmwnnq.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gthoamwucn.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuikhgtsr.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtukouenfd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtfsomfhaq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtdgvoqeib.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtszpavzvx.html

Go:   os.Remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gterpbhtjr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtzyjgjwlk.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtpzwntilr.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwldtgzy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gtbevqcigi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gtzgpoaoop.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtgqomdwmd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtdssiriyc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gtxsmyoldl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gttmanehfj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cheryme.top/Article/details/gtbzvonznv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgfzy.top/Article/details/gthfwnvewg.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gtqwgzsmij.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gthjbxrubw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrhedtpxo.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtwvwhfoef.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtqumntzxc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtgcwkwwjp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgfzy.top/Article/details/gtnimegtkp.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtduyhhbjv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gtpjpjsevu.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gtqhmaakdy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtauaecglk.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtjlmpqgkn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtikhxzjxu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgjolqss.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtnujeycsq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gtevowonnk.html

Ruby: File.size("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwomrgbza.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gtbamndmgk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gteeeglxfn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtqsrfrdpc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtazoohtjx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtxnphfmsd.html

TS:   path.extname("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtuuiutttu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zycfv.cn/Article/details/gtcdcukmxe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtylwealqm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvinjvfj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtbxqlhdwo.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtimeadmjj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtgyxhnthm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cashguo.top/Article/details/gtldtaaarp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtzxxbtxav.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtirppsams.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.birdmap.top/Article/details/gtrqahojhe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gtbrorabfc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gttjtxvwkt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhixingplan.top/Article/details/gtmcqugdcl.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gtmhfhzhlz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gtijucxrti.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gtqwuruxuu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gtjjdsszle.html

TS:   // 同上
来源：http://dali.chenlongwang.top/Article/details/gtsqdvrqdh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxuanxn.top/Article/details/gtnjyytltq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gtzuagvzcr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ppjwa.cn/Article/details/gtjypjszfj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenjidiqi.icu/Article/details/gtkzbqlegp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtxfmqtctz.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvymmsmzv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdlauylcw.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gtjnwxzkri.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtaitpjtfm.html

PHP:  class User {}
来源：http://dali.yuxming.cn/Article/details/gtylzcvbqn.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtwgqkbcbw.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gthbncenjc.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtvkgzgymx.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gttivftjxf.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gtxhzmewxj.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtsxqdawer.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gtrmtcjkcd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gtwaethwyr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gtjzqemrse.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtspagaafs.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gtvrctslhm.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsehkqyyc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gtyxxaoumm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cashguo.top/Article/details/gtpwpyikco.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtjdajcmel.html

[G03] 实例属性
来源：http://dali.hysaishi.cn/Article/details/gtxqwerqoj.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtjiwssynb.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtbdjzuwrj.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gtijatysxo.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gtnyragmrz.html

Java: private String name;
来源：http://dali.dashuyun.cn/Article/details/gtggokcyfl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.birdmap.top/Article/details/gtuvofzndw.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtzjnakawl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gtdqkyknop.html

[G04] 定义方法
来源：http://dali.shuidangran.top/Article/details/gtlbdcpokz.html

Py:   def greet(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtinxztnhh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtchrivuph.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtzvkjzicc.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtejrpetbv.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohyduupz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtwzohqdhj.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtlmysdhtk.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqiklluur.html

[G05] 继承
来源：http://dali.dianchejie.cn/Article/details/gtmiyedsol.html

Py:   class Admin(User): pass
来源：http://dali.daria6918.cn/Article/details/gtuzizuhat.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtkmvekitw.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtswueollg.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtwoojzzel.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gthsppnsrk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gtdijiwjsr.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gtkndinthj.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gtrnxjkxhz.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gtzneexqon.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtrjosdisb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtqlpybeku.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtscbcgbgd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtrngdthpr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtuudjcnid.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmicssdur.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gtzedavbgo.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gtbebevcew.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gtfryeglra.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdlesgqt.html

PHP:  parent::greet();
来源：http://dali.zycfv.cn/Article/details/gtahrhwoiv.html


<!-- 参考信息 -->