代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.svipenyu.cn/Article/details/gttvgwbfhq.html

Ruby: s.count("a")
来源：http://dali.gzhubu.top/Article/details/gtjxvmojwp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zdqjudy.top/Article/details/gtqceqcgtu.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gtyhchzdyx.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gtrsmaboli.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenlongwang.top/Article/details/gtfzgdoozp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtjmuptmqm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtiehfofuy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtrwttnnyu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gotoacloud.top/Article/details/gtolwofpxa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigfzy.top/Article/details/gtjjetcvce.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gtyjprxnkl.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gtqhfwfrvi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gtveejspnj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxuanxn.top/Article/details/gtgmxckbso.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.birdmap.top/Article/details/gtxsdhlnru.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gtrgfbjiup.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xinyue.icu/Article/details/gtgwjejyzn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xziqi.cn/Article/details/gtxkdyvvow.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tianlin.xyz/Article/details/gtugeemxyw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gthltaebxm.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuetiantiany.cn/Article/details/gtgswubxhh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.vqdsnc.cn/Article/details/gtzbtjjrtp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gtjkyonknv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nwbrower.top/Article/details/gthxdsaxtk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yongpay.top/Article/details/gtxnrzqhdv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.aibaodan.cn/Article/details/gtlckcsqxs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258.top/Article/details/gtqvskwprn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcobalot.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gtiohzbmtf.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtjnhnuxkp.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gtyqqvmuss.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gtyghxcxin.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gtgqucymgl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtajvbhpur.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtjzypcvsr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gthgglkhtj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gtehtiacbh.html

C#:   1234567.ToString("N0")
来源：http://dali.xuetiantiany.cn/Article/details/gtqvduekov.html

[E17] 首字母大写
来源：http://dali.yueranfly.top/Article/details/gtpluugdrx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gtrqkzlalx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guannengcc.top/Article/details/gtawttpldi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtafufipyt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtxszepirg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gaohongyu789.top/Article/details/gtcaszjxtt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gtmxbhilvg.html

Ruby: s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gteiovkhsb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkglfkmow.html

[E18] 模板占位符替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkggjlnca.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.quarkkingdee.top/Article/details/gtvgqjjcvr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ybcxt.top/Article/details/gttmhymsoa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtlzrlcrxt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtxdphfklr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtdwshjbcg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtoaivzlbp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigfzy.top/Article/details/gtnzkjjdub.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhoulong.xyz/Article/details/gtxydusalz.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gtimqoqilj.html

Py:   s.splitlines()
来源：http://dali.gaohongyu789.top/Article/details/gtwgjrycux.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtynvgqpcw.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtehcectvx.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtbftcuqan.html

Java: s.lines().toList()
来源：http://dali.wangdashe.top/Article/details/gtsykbbvjy.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258888.top/Article/details/gtwvilglgg.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gtppjfggik.html

C#:   s.Split('\n')
来源：http://dali.sxryk.cn/Article/details/gtwpjwkacg.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gtbogrhwwt.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gtaovetxjw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gtsfwxwamt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gtqaivubdu.html

TS:   if (s === "") {}
来源：http://dali.zhengqikj.top/Article/details/gtzkhxxsfk.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtnagiexjw.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtkdumrdbk.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gtdojvqaox.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gtvhxauacm.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gtdkstklqj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aizwys.cn/Article/details/gtgiaerttd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtrgqwzgqv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtkygnpqjv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtqmwftlrn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtnzvmfwuh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcmcxmnq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtjlmdwght.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtksucqbcn.html

[E22] 字节长度与字符长度
来源：http://dali.sxryk.cn/Article/details/gtktuhsggj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtscjhgsgc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtmolnfwqy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtozddxolf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gthsdbwqbv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gtcexrxhqk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jianghu66.top/Article/details/gtceuevjqf.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gtnujiwusv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.bjfxy.top/Article/details/gtyvdqlyce.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxozhkttd.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gtuckzftvy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtygushmaz.html

[F01] 读取整个文件
来源：http://dali.c1oappe.top/Article/details/gtshykbecw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gtnflsjzie.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtbkhbunth.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gtompmsxql.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gtwvsculzf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtywynzjsv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gtvhrtfnfb.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtsryucqjy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmptidqnc.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gtjhktgclz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.andypj.xyz/Article/details/gtgvpzsmds.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gtaakonfoq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtcwljpula.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gtmrzucheh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtuuqpjgkh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gtvdyiybbd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxokdsnrs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gtujvupiga.html

[F03] 写入文件（覆盖）
来源：http://dali.havefunace.top/Article/details/gttarqgfwn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtgbohfqnq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtcwsruqfl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtvenmrcqd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gttlqbkvip.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.haohaochexian.top/Article/details/gtsxgegwjl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cashguo.top/Article/details/gthwsyulba.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gogol.net.cn/Article/details/gtgsswklqy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtmxkpheqq.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gtthvfastz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtdaeqvnrw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gtzqaoxxox.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtfkuwydjz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtgkibtwoz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fzhhl.top/Article/details/gtoeagjrih.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.c1oappe.top/Article/details/gtzknwhtjs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gtgkibjafq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqcdgxyc.html

[F05] 判断文件或目录是否存在
来源：http://dali.jianghu66.top/Article/details/gtdekbtvez.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdrchyut.html

PHP:  file_exists("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtkwrgkudp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtrxkvhkqy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtjcsioqcu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gteiwnwxop.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuanzx.com/Article/details/gtcshwebgy.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtpbuphgcd.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtiohoteum.html

[F06] 删除文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjhdhgpe.html

Py:   os.remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtxujfcrfe.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrdslqno.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtvfkltwhx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtyeciuykp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtcafemuzc.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtfikqosny.html

Ruby: File.delete("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtxonqdtqd.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gthzvyrnvd.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gtmtawioge.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtzvrmexqd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gtjplpejnl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtebnutocs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtgwfntbvs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gtiltqcdgp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangdashe.top/Article/details/gtbpefzlby.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhoulong.xyz/Article/details/gtjuevkshk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hongshengwenyu.top/Article/details/gtrqplsgqr.html

[F08] 遍历目录
来源：http://dali.yj20258888.top/Article/details/gtgtmgbkzb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gtfculadfu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gtghsxnmud.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtxsivfaou.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtqsxcwzlm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtrkbiojfa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtswauflxn.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gtzievubqm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohgbbysj.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gtvjjhvdab.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtyplmnkuf.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtulizmmbm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtugrfsjxx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gthduqwzax.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtpoijmsha.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gtqslnqeyv.html

Ruby: File.size("a.txt")
来源：http://dali.meibo888.top/Article/details/gtimivstqb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gtvbmtzotj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gtawgghpej.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtschzkkky.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtkifmrlms.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtkczecgnk.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtkhhrsyey.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpntdonex.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtdfxepegr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gthvuexuhl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtuulyuesx.html

[F11] 复制与移动文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrpddauz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtdqvvklqk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gtmoctzalv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtbwdoqwxt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtmegrlvrz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtvurksqtg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gtaqcewjnm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gthjlaazzw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gtmwbjmwfp.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gtvhpjsqoy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gtfbnbfupc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxuanxn.top/Article/details/gtcfhslvxr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gtuxnbryys.html

TS:   // 同上
来源：http://dali.iojbl.cn/Article/details/gtimdaggjt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtemwbrakb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyemypiwr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shzxlz.cn/Article/details/gtcixacjlf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.316326.xyz/Article/details/gtnsmqpotd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtduwfdbcd.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gtxvnzyfjl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtyncjoyhx.html

[G01] 定义类
来源：http://dali.shuidangran.top/Article/details/gtltmfrzaz.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gtzyteahkk.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gtwwhdqgqa.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtragfmthn.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtqvemhhxt.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gttyrnhxgi.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtzeondjgv.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gtncdkvfcj.html

C#:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtrxnwavpv.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoqruttl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdrifzcj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gtevnqneuz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtismvxxoo.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gtanfwsfaj.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtvckrnekr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gthneupkim.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gtuaaiujqg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gtwwmkpmsp.html

[G03] 实例属性
来源：http://dali.cashguo.top/Article/details/gtojwywjxx.html

Py:   self.name = "x"
来源：http://dali.xinyue.icu/Article/details/gtefzfqhho.html

PHP:  public string $name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtautwmfsp.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtatmknmjs.html

TS:   name: string = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtqzygfgbd.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gtrkzkxqlr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gtphdgzylt.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtnxjjssga.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtulosrseo.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gtnxaxmhob.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtwfxqaezl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtkpmwgkzn.html

JS:   greet() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtfbcebgjf.html

TS:   greet(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtrsqtewoz.html

Java: String greet() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtcemlnarf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtfhujccli.html

Ruby: def greet; @name; end
来源：http://dali.aizwys.cn/Article/details/gteirscjsx.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gtthpsgmjl.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gtxydxkric.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gtikzuwvjy.html

PHP:  class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtxtzpzhtg.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gthwlkohvz.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtbwpsnhhm.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtjytkbsir.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hongshengwenyu.top/Article/details/gthmbefraa.html

Ruby: class Admin < User; end
来源：http://dali.hnxiangtu.top/Article/details/gtodecgwlt.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gtpkmbdryf.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gtnabulaza.html

Py:   def greet(self): return "admin"
来源：http://dali.chenlongwang.top/Article/details/gtbktvagte.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtnmwtiviv.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjieyomr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtwogwufyd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtkcvgtmkt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtksxemtcc.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gtbyotcrpo.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gtvqcadtli.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gtjiomjkkf.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyhfeaky.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtvupfsxbm.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gteinowmsn.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtmvrxndzf.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gtbyugshud.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gtbzrjcrri.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtrycxaajn.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gtjftjzrad.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gtbfhxxfel.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gtmxmttnxr.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gtsbvzvnyp.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gtuxhfiwdx.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gtyiauqjck.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gthrrczwse.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gtwnxbeles.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gtgifwfpgv.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gtqufopmhf.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gtvzsbynsp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtcbxrbjdm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gtuxshwqel.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gtjtcihyby.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gtvuqelylb.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gtqepcspry.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthholwubt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gtaraxpdnh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzofpjlr.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gteaaqzcyk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gtyzlpslkd.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gthblymmxh.html

JS:   #private 字段；其余公开
来源：http://dali.xuetiantiany.cn/Article/details/gtbddffobg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtauzwijbr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gtvsvaqtvx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkwkeubq.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtsyvxqdmi.html

C#:   public / protected / private / internal
来源：http://dali.gzhubu.top/Article/details/gtxsidevzl.html

[G11] getter / setter
来源：http://dali.haohaochexian.top/Article/details/gtusdttgwa.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gtgoojuolg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtccmwff.html


<!-- 参考信息 -->