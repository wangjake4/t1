代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gtrxxcwqdu.html

[E11] 反转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtyomyagyn.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqfdwinh.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtubyaqrew.html

JS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gttllaojcg.html

TS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtthtnmwzk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guowangkeji.top/Article/details/gtbllhsyve.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.mhx1999.top/Article/details/gtcvpawvbj.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtgccrkswh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtjgmqgove.html

[E12] 统计某字符出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiooarhau.html

Py:   s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtwhnvyhpx.html

PHP:  substr_count($s, "a");
来源：http://dali.cucudq.cn/Article/details/gtoldpsltz.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gtvpbczbck.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtvzvdibzd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yueranfly.top/Article/details/gtjdhvjwxf.html

Go:   strings.Count(s, "a")
来源：http://dali.yangfankeji.com/Article/details/gtorcqpaxv.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gthozprfmu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gtffrkvqir.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gtjcqyyafd.html

Py:   for ch in s: print(ch)
来源：http://dali.iojbl.cn/Article/details/gtmuravdxs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gtnwtudnez.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuiqogxwh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwhnqubr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ivvv.top/Article/details/gtkbenweoa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtodbmaqgh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258888.top/Article/details/gtcefojhyh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ivvv.top/Article/details/gtoilpniqf.html

[E14] URL 编码与 Base64
来源：http://dali.guowangkeji.top/Article/details/gtsmvguxbu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hnqzz.top/Article/details/gtlpvcozqn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.bjfxy.top/Article/details/gtkipxnvcz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcieiarl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gtrjqxfqhr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtfgqemfkj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gtsmlwuouj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipedkzel.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtitlpifrd.html

[E15] HTML 转义 / 反转义
来源：http://dali.feifeiyinyue.top/Article/details/gtwhwsmitl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gtcxiqetyn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtzhcpsron.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gogol.net.cn/Article/details/gtlkcfbhwr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gttmenomqi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daria6918.cn/Article/details/gtdhruikwa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tanke756.top/Article/details/gtwdiebyrl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.bjfxy.top/Article/details/gtcturnjub.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtgeknauoc.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gtyhoposjq.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gtkawwchlx.html

PHP:  number_format(1234567);
来源：http://dali.yj202588.top/Article/details/gtmnxlhqmq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtpngtpguz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gtcyqvuemr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hysaishi.cn/Article/details/gtmmanvrxg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sxryk.cn/Article/details/gtuptweoef.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gttsynldxn.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gtqbqygivy.html

[E17] 首字母大写
来源：http://dali.hammf.cn/Article/details/gtxgdtvrtl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hongshengwenyu.top/Article/details/gtobkfozaz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gtgvquoqcm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtiybqfbxu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtwfhimacb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gtwnmgfakg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shzxlz.cn/Article/details/gtoheqjugx.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gtdhnroaik.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gtticbvvii.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhiynazc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gtkbgsejgg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gtvwprkswd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtveaqiarx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtemgrkqjr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtwjgxrzwp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tanke756.top/Article/details/gtjwllolcb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gtkacalidc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shangyingyoupin.top/Article/details/gtsctubhez.html

[E19] 多行文本按行拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtryjsoned.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gtqgcetfuk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtzbxzekrm.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtlhvupicb.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtedyunwgr.html

Java: s.lines().toList()
来源：http://dali.hywenlv.cn/Article/details/gtkfdcixzh.html

Go:   strings.Split(s, "\n")
来源：http://dali.jyoumei.cn/Article/details/gtxjsrvnfv.html

Ruby: s.lines
来源：http://dali.hongshengwenyu.top/Article/details/gtgjjstenz.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gtxlvdwskd.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gtxhpcwpct.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gteejjkdlr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gtdtaltyws.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gtqnciwfvd.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gtbgbvtdoo.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtgarwovpd.html

Go:   if s == "" {}
来源：http://dali.hnxiangtu.top/Article/details/gtjjotyfux.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmxtdpfd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gtqlvfxudw.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gtpgcfiqsp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gtscbsqozv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtsefdfsvd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gttcfgptya.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtzijntbkt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gthiufdrky.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gthwpsornn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtaqyylxkr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtoqodgsci.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gtvrreqcuq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ybcxt.top/Article/details/gtqunaeefo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtyopinsgl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gthcfwrjyl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gterlqxtux.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtndmazmty.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gtlsxrtkpd.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gttrwviskr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtxulxcgsn.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfxnrtmeo.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gtjxrrtwyo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtsjpzbjsu.html

[F01] 读取整个文件
来源：http://dali.ehwqpu.com/Article/details/gtwdfbfzuf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gtlnvyrkip.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtwljuhaun.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxinkj.top/Article/details/gtfkzngtdp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtohutinnx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtlimqkgpa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gtvwzrzubl.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtfsqlfxmz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtaelabjtu.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gtmchitqck.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gtibzgcrsw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjjjrptx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtjptnrcmx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwvnmlpfm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtwpawviqr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gtbyixinki.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zycfv.cn/Article/details/gtnouxtbjs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gtozuuwvmn.html

[F03] 写入文件（覆盖）
来源：http://dali.zhengqikj.top/Article/details/gtvuxiesho.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gtsousipzd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtmococcbb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuwyiheo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gteqmykvdv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvvyvcxs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ybcxt.top/Article/details/gtkoweosse.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sweek.top/Article/details/gtfpixvegq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gttuqjiiyo.html

[F04] 追加写入文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsauibsl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gtzkngsppp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhoulong.xyz/Article/details/gtkbksgzuc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfvvaehe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gthndeabft.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gthcofwdlm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gtpooepblk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gtdvfpdfon.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gtygsugkob.html

[F05] 判断文件或目录是否存在
来源：http://dali.smart0.xyz/Article/details/gtkcdqtcmt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gtvbizmqyo.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtahcqtaqu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtgnfzaejw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtgmffcfjr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gttadzqgob.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gtfozpsqrm.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gttyhlkvmp.html

C#:   File.Exists("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtnrugoavh.html

[F06] 删除文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqktzwfv.html

Py:   os.remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtjgoxdcyn.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtvpmstrva.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtogrlhlqy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtwzbifiti.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtkxdnpmda.html

Go:   os.Remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gttxtauguy.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtoxkgjkpj.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtnqpsfhzr.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gtfwfrwffi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gtcrvmutqd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gtwonyixit.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtvpxluxzb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtgjywpckz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gtyrsmbnlm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangshuangyany.cn/Article/details/gtekuiubte.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtlzqynawp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gtstchlkej.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gtgdetrddw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtgucguusu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hysaishi.cn/Article/details/gtfwzbioqq.html

JS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtzorkphau.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtlkpirawt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtwwhqhznv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtongjbmmf.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gtraljsibw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gtcfkdsyme.html

[F09] 获取文件大小
来源：http://dali.nanxinkj.top/Article/details/gtpncnzfmg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtelnzskcg.html

PHP:  filesize("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtsvztqdsf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtparumhyn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtolrrrold.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtbcorjhrj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cqqwz.cn/Article/details/gtzcnroqsf.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtnxkqjxbf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gtlprbtmxe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gtbtleuhlk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtyiowkntk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtiujjsqha.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtjzmvkjxn.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gtcjrboifi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtrkhcgkxy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtablownfb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtdggspmzp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtoozijhkl.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gtthyjecux.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtmjljkdmt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gtzouxxnja.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtyrczbwgm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtmhouaetq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtvgvncukk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gtgtwjhuar.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtyfumxtkv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dashuyun.cn/Article/details/gtrwixgdzz.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gtjcxebafz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gtgbvrasxf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hongshengwenyu.top/Article/details/gtbapdaoyf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gtecnusrqg.html

TS:   // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtjmvzqvwx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gtbmepqppg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj202588.top/Article/details/gtsvhgguip.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cheryme.top/Article/details/gtgredriho.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.birdmap.top/Article/details/gtqlvoirbd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfbnbzgu.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtwlvapoos.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtrtgqgqam.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gtfwutfelg.html

Py:   class User: pass
来源：http://dali.ivvv.top/Article/details/gtqmzpsarb.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gtenbbonbj.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtkraqugty.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gtvtgpdxay.html

Java: class User {}
来源：http://dali.dianchejie.cn/Article/details/gtywoepwrk.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigkeuihl.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gtfoigoniz.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtxjusqjhh.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtqtlpznmw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.feifeiyinyue.top/Article/details/gtwpnqifje.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.svipenyu.cn/Article/details/gtvblxzcmv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gttqsqtobj.html

TS:   constructor(public name: string) {}
来源：http://dali.shzxlz.cn/Article/details/gtdjhcsjno.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtrwnxdhna.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtimgsfyea.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gtnvzbwyff.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sxryk.cn/Article/details/gtejhulakq.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gtffqiclvy.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gtbnftkaqn.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtuyykeiri.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gtkpqbmmnn.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gtnmuaaeqk.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gtvyvysruc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gteknfuigv.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gtqfdxomfx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjqwcpmt.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gtysewieun.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtohrirqly.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtwxapqvny.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gttaopfdoj.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtkcakzfnc.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtdskkjooj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtpxtuqfrj.html

Ruby: def greet; @name; end
来源：http://dali.aizwys.cn/Article/details/gthofkgpjs.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtlcsgftcp.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtnkydqurs.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtytehyarp.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtkuowzreh.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwubayfca.html

TS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtsryjhbhn.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtsxzhfarj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtvfftbsgk.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gtsfnonsdh.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gtocdltbqm.html

[G06] 重写方法
来源：http://dali.jinqigfzy.top/Article/details/gtflhwfacc.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gtneentktk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtajmwyiwo.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshuzzrmt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtgalbzmft.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtezazekgk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gtofbhqdoy.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtxvampwkf.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmgmcgvl.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gtdaladqus.html

Py:   super().greet()
来源：http://dali.gotoacloud.top/Article/details/gtaagtarvv.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gtnywjurjj.html

JS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtgehcdyfc.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtrmeklqxq.html

Java: super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtatgxkzgz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guowangkeji.top/Article/details/gtxumhfnva.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gtwzwhoqjs.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gtxujakxob.html

[G08] 静态方法与属性
来源：http://dali.yongpay.top/Article/details/gtgozbmizl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gtlpbgtpkt.html

PHP:  public static function f() {}
来源：http://dali.zdqjudy.top/Article/details/gthjgprhcr.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gtxvlvtkfq.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtbzfexueg.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gtzmfrgjah.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gthfdewckp.html

Ruby: def self.f; end
来源：http://dali.sufxvd.cn/Article/details/gtztudcdfe.html

C#:   public static void F() {}
来源：http://dali.tian-w.cn/Article/details/gtrxdglriv.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gtsgvrozyf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtiwjmdvzf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gtzvnbmsea.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gtkscisnnz.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvivxhyvr.html


<!-- 参考信息 -->