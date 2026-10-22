代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2gbbzwwyh.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2fhdbtnhs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2llotkmvl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gt2jgjvazxx.html

Ruby: s.reverse
来源：http://dali.cheryme.top/Article/details/gt2ohtvnvey.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gt2ipxvmdhu.html

[E12] 统计某字符出现次数
来源：http://dali.andypj.xyz/Article/details/gt2bewciwtw.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gt2fqmzeete.html

PHP:  substr_count($s, "a");
来源：http://dali.hywenlv.cn/Article/details/gt2tttzuwnr.html

JS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2rgtwapvd.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gt2qlovywhc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.0kj1m.cn/Article/details/gt2idmhuvlg.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gt2qdkznevy.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2miyfcixf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffofswyn.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gt2vamcqwbz.html

Py:   for ch in s: print(ch)
来源：http://dali.wangshuangyany.cn/Article/details/gt2faarjozz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ydzc1.top/Article/details/gt2pxtuqdhd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2wpkubtsg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljflhohx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gcqducvt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gt2zyrmneuk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pengpengdd.cyou/Article/details/gt2znwwztvq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gt2wpjdxsho.html

[E14] URL 编码与 Base64
来源：http://dali.dianchejie.cn/Article/details/gt2destirva.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.snrcjt.cn/Article/details/gt2bfrxdwpv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.havefunace.top/Article/details/gt2ineqktyu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nwbrower.top/Article/details/gt2ojbztfsg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2lpihsqof.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gt2mxhlpsht.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ralwqmhi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gt2vxgdxaim.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2evoqzzmr.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpanlqfj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.smart0.xyz/Article/details/gt2ecpuephu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gt2kepwsqay.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cexehqge.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gt2wmbklelw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gt2iciupgil.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.c1oappe.top/Article/details/gt2ubuxfqea.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ybcxt.top/Article/details/gt2cpeujybn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xohucflv.html

[E16] 数字千分位
来源：http://dali.zhengqikj.top/Article/details/gt2nllmdcze.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigufen.top/Article/details/gt2ibcrncxb.html

PHP:  number_format(1234567);
来源：http://dali.cheryme.top/Article/details/gt2zzfjhfor.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gt2bzjgdkkb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gt2foxztjri.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xylfe.cn/Article/details/gt2govxrfuv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gt2uqmcagaf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ggvwlofg.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gt2hkwpfamb.html

[E17] 首字母大写
来源：http://dali.fzhhl.top/Article/details/gt2adldxwsj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gt2fweqxzsx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenlongwang.top/Article/details/gt2cworunpt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qssvrqep.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2rcjbdauj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuxming.cn/Article/details/gt2ukgbazhe.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2vguepfoe.html

Ruby: s.capitalize
来源：http://dali.daria6918.cn/Article/details/gt2sobpzeck.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gt2xpiaxosa.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gt2iprvolua.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtekjii.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guowangkeji.top/Article/details/gt2eupeolej.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2naheyoep.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2eajxiyji.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2gcvuzcqd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2kmqxphsj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ehwqpu.com/Article/details/gt2lpdyvqvq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ehwqpu.com/Article/details/gt2eqpwwjvi.html

[E19] 多行文本按行拆分
来源：http://dali.wangshuangyany.cn/Article/details/gt2pgmesely.html

Py:   s.splitlines()
来源：http://dali.ydzc1.top/Article/details/gt2yjkyjmye.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uoctocgt.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gt2gmnuzvhm.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gt2jfbcbbzh.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gt2jubtrygv.html

Go:   strings.Split(s, "\n")
来源：http://dali.316326.xyz/Article/details/gt2hpkmitas.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gt2kyycjhav.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gt2ufzaqwam.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gt2lagpbycs.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxzkozll.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yueranfly.top/Article/details/gt2tspomzge.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gt2pkxjfvwe.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gt2oivlnjiu.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gt2orqejkgh.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gt2nfpmoewl.html

Ruby: if s.empty?
来源：http://dali.fengsongda.top/Article/details/gt2wxctxbhe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gt2oblulvdz.html

[E21] 超长截断加省略号
来源：http://dali.yonumen.top/Article/details/gt2xjwuingl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gt2hzykelzo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2vuntidyw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2fxkwuphc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2wrcbisxr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2dlninkeo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gt2ewghjupg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2fyzjxhxj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fzzdlbcg.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gt2ptcsstqg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj202588.top/Article/details/gt2dftkbmni.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lublytzd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2wobvkxkt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2otxswipj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gt2ryplihwq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gt2sammjvju.html

Ruby: s.bytesize;  s.length
来源：http://dali.yonumen.top/Article/details/gt2clmwpnuk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jiagoushi.top/Article/details/gt2ckrsbasw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2jytxltho.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gt2xkuihvft.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2qjstqvxe.html

[F01] 读取整个文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2lfqmzuuu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gt2lmipqevr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2ejnnyvqu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gt2hscavvwq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgqsxqwx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2amyfmnmn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gt2ohuawnjs.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2czduklnn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2qefqbhgd.html

[F02] 逐行读取文件
来源：http://dali.tanke756.top/Article/details/gt2ggmuwvzw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gotoacloud.top/Article/details/gt2pszexkvw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gt2cimgsnja.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbbumwsx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gt2enmxxvlt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gt2heifncrq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.vqdsnc.cn/Article/details/gt2vlrmluyg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gt2qzyoyiry.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gt2ujsnbiym.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gt2fyhrjeyi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.iojbl.cn/Article/details/gt2pxrzhzpk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2zkgslslh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gt2wnaeaaec.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2ttesilub.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gt2ploglmiy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxuanxn.top/Article/details/gt2utebykub.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2ftmnziou.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gt2weuotqfw.html

[F04] 追加写入文件
来源：http://dali.cqqwz.cn/Article/details/gt2qlhwbbms.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2nzbngjpr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fengsongda.top/Article/details/gt2xdkheaee.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nmiyzstu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gt2anizrhjr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gt2cmpzstcd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sxryk.cn/Article/details/gt2yaojvysg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shuidangran.top/Article/details/gt2pmfutmfd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.meibo888.top/Article/details/gt2pztckivt.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2lqvllvlq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigufen.top/Article/details/gt2mvqyoacc.html

PHP:  file_exists("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2llivfusi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2noxtuner.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2qykhzxjc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2gnznjsao.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gt2zrbohvky.html

Ruby: File.exist?("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2xfjdzadc.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2rzlrtnrh.html

[F06] 删除文件
来源：http://dali.svipenyu.cn/Article/details/gt2qmadlgur.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2dbwlxkkz.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2bhmkoaim.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2aoiotird.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqlykjid.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2titenclv.html

Go:   os.Remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2dwscleid.html

Ruby: File.delete("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2hsggmmra.html

C#:   File.Delete("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2dcyquymc.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigufen.top/Article/details/gt2nafknwvm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gt2mhhbbdie.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gt2ykmnjiei.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gt2qbsnbrzk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2kpvrvtsz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gt2cqdxrafl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.havefunace.top/Article/details/gt2lvufhuwf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gt2ctwyvqqc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gt2ioofwldx.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gt2iyipsaxn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gt2wzboknta.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gt2tgxmlzhe.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvcnbqxs.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2gbwpkvnv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2hnexooxj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daria6918.cn/Article/details/gt2whcvtspk.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2ogvpcijy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yongpay.top/Article/details/gt2gqtrkcww.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gt2ouyqyxzx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2yebmdrrd.html

PHP:  filesize("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubluqiag.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzddoxg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2eqvdpkul.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2vplbcgrq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gt2nrvsjczy.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ycanzyfu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gt2vzqaagod.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gt2tmmdemkw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2pledmynu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2agodwjkc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2ojtvjpmb.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2xgwusjeh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ltgirqrj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2uvytfnnp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2pwdhqiuf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2fvzjqwyn.html

[F11] 复制与移动文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ducitbei.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2oyjdedwd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gt2tpyqleta.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2xmiytslj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2pakvsvef.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2xxwsoxdc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gt2ewqwohvb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2nwdfqund.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlyjfeje.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gt2anrdympw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.316326.xyz/Article/details/gt2couhcnvm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gt2emkbosbx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jorkbawr.html

TS:   // 同上
来源：http://dali.hammf.cn/Article/details/gt2duunyipn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuanzhike.top/Article/details/gt2nwghebxs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gt2jihtbtvq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gt2uinheqin.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2gqjdgqhl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ftikvqau.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gt2kkxbvmsg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2xofievno.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gt2balqltmm.html

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2knbatjol.html

PHP:  class User {}
来源：http://dali.xziqi.cn/Article/details/gt2menckmpj.html

JS:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ficbatdj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gt2iyypvwsj.html

Java: class User {}
来源：http://dali.guannengcc.top/Article/details/gt2shnifpsq.html

Go:   type User struct { Name string }
来源：http://dali.haohaochexian.top/Article/details/gt2jfpmtrjb.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gt2aixtzpkv.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmvxfjfo.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezfaequg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gt2kgkirpxb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gt2qtadsbfi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xysexbam.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gt2uqhreikl.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gt2luaetqpa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcovsrtb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gt2ppdxpurf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2qxwdlftb.html

[G03] 实例属性
来源：http://dali.quarkkingdee.top/Article/details/gt2pldxuzbz.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gt2hwnespho.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2dlxidvkq.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2cnaskrju.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gt2bmwpyhue.html

Java: private String name;
来源：http://dali.zhoulong.xyz/Article/details/gt2dbcruuoq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gt2fmhhfswi.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gt2vnfoqlfg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcjcnaay.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gt2zcllatcl.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2wtdwwnww.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gt2cvxwxhhy.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2yiixorgm.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gworznrj.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2gzqwombg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2bnindmmc.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gt2zlcwlofw.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gt2youiryru.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gt2udgnhigx.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gt2tsgclscb.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2xwwqnpwe.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2gfrrynpn.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2yzoxoguu.html

Java: class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmckxvue.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gt2pdwdoefn.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2dnxytitd.html

C#:   class Admin : User {}
来源：http://dali.yongpay.top/Article/details/gt2olkwnkrf.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gt2oeycsmaz.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gt2ggyqzkyf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2tdbouquc.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2wcxeoito.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2stbadgzq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2jrcviaox.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gt2gisrafoz.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gt2kcpjotmb.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gt2gyzuakbb.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2jgmwrlyf.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gt2hsyfypbv.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gt2jtxxsien.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gt2qjztsvqq.html

TS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2hlmniydi.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gt2pwirdnua.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gt2tqoytmkl.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gt2mixdwmpa.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ryksgkxk.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gt2hmjchaeg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gt2ziaiseml.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2lfpffiyg.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gt2cpbtkirs.html

TS:   static f(): void {}
来源：http://dali.mhx1999.top/Article/details/gt2shgggqsq.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2wovcelbk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gt2gsaizcxx.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gt2ywqwqdcf.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gt2qzkhzqca.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gt2xxkrzutn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gt2lwkavqef.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gt2dkkumknl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gt2awytsgnr.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gt2bzgjeuwc.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2zzudumtl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifwbubpl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gt2acoqghqm.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gt2tkotgyvn.html


<!-- 参考信息 -->