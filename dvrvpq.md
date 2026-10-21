代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtkxlihkan.html

Java: String.format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtspufhyko.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtlkjofzrf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtcrblwadf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gtpmrpvdsi.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gtolprvamg.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtqtvphssd.html

PHP:  strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtkdeyigjg.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtieoubobp.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtnipjrunb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangdashe.top/Article/details/gtwlntcvlm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pycfn.com/Article/details/gtcahbcazb.html

Ruby: s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtrcndgrgo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpefjfjqm.html

[E12] 统计某字符出现次数
来源：http://dali.fzhhl.top/Article/details/gtzkdpthgo.html

Py:   s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gthhmewlon.html

PHP:  substr_count($s, "a");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthyaqrlba.html

JS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gtguoqhysj.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtjrpipfcm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigfzy.top/Article/details/gtlsckxqqc.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyahhsdy.html

Ruby: s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gtnebqwytu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gtvwtpaejg.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyljytuls.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gtiqnqwjfe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.bjfxy.top/Article/details/gtayijread.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtdusowmtw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtdutubzyy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtmzqlmizy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yvedp.cn/Article/details/gtejckfbfa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gtbevidswh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zycfv.cn/Article/details/gtjfyntytl.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258888.top/Article/details/gtihaliybq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pycfn.com/Article/details/gtrwnjyjpx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gtrfwibzeh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.quarkkingdee.top/Article/details/gtbxiupcjw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gtulfymtek.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hammf.cn/Article/details/gtigivjnbh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuetiantiany.cn/Article/details/gttzutsnct.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.iojbl.cn/Article/details/gtrcsqnzzf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cheryme.top/Article/details/gtethoefiv.html

[E15] HTML 转义 / 反转义
来源：http://dali.jianghu66.top/Article/details/gtcxisoxky.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shzxlz.cn/Article/details/gtdiaolkow.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gthntdylcz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtqmogqwia.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigfzy.top/Article/details/gtdivaujvs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ppjwa.cn/Article/details/gtmtgpehvz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cqqwz.cn/Article/details/gteaikihqw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gtkhlnpkwr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxinkj.top/Article/details/gtrzviizfb.html

[E16] 数字千分位
来源：http://dali.haohaochexian.top/Article/details/gtqrqqmtuk.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gtzfhlevit.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gtqhabgmof.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtrefxjvvh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtbcqhtbtf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtdyvgrfpi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daria6918.cn/Article/details/gtdpnbqpta.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gtusjqalnn.html

C#:   1234567.ToString("N0")
来源：http://dali.sweek.top/Article/details/gtlqeaxjau.html

[E17] 首字母大写
来源：http://dali.jianghu66.top/Article/details/gtjuumlxff.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtritldjzg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.birdmap.top/Article/details/gtsjfbubjh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtrwlsmnxv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtcklbvxdv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgufenzy.top/Article/details/gtropjnolv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gzhubu.top/Article/details/gtimfvjvge.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gtupoxhsky.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.0kj1m.cn/Article/details/gtnyfwcgor.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtxnplvubw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gtwujquhzl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xziqi.cn/Article/details/gtxwzdvgap.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtwrzvthhy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtezokdfeu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtvbggcout.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtmgygpmgr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gtggpdewag.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gtyexocxbf.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gthugnnzzj.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gtzfxolunu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbjsusap.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoinavcke.html

TS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtixpaffzs.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqdtgynh.html

Go:   strings.Split(s, "\n")
来源：http://dali.sufxvd.cn/Article/details/gtueyewlgo.html

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gtvijxarwa.html

C#:   s.Split('\n')
来源：http://dali.wangshuangyany.cn/Article/details/gtijmfelgq.html

[E20] 判断字符串是否为空
来源：http://dali.birdmap.top/Article/details/gtsemptrax.html

Py:   if not s:
来源：http://dali.andypj.xyz/Article/details/gtgqqzulga.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gtivptdywk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aizwys.cn/Article/details/gtrtezxjgh.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtpdsuzdhl.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gtmvfpjmni.html

Go:   if s == "" {}
来源：http://dali.dianchejie.cn/Article/details/gtlsvgcwzx.html

Ruby: if s.empty?
来源：http://dali.ppjwa.cn/Article/details/gtajzjyvbe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gtgiunyhaw.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gtddvfvkob.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gtnakkpzta.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtzefiqnbn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtlrfpdthg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtrghhaase.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtfovvcpwj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gtvcbeftyi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtismrzdtq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gtannnsgdm.html

[E22] 字节长度与字符长度
来源：http://dali.hnxiangtu.top/Article/details/gtjcrurlsp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkztatsel.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtxvydyauy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtnukedcxl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtzqhsqooe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gtdmqehbrt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gtffvbiuoo.html

Ruby: s.bytesize;  s.length
来源：http://dali.yueranfly.top/Article/details/gthqxaadta.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtvvouuxbz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gttmbumnuu.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gtpmojtloa.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtctobafcv.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gtrrhxqswj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gtpticxxqq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtecgexwtf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gtciubesmd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtxsfkwxms.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtomvfwkak.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gtszlmrrjv.html

Ruby: File.read("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtxlksvnlr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtoqhqnpku.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gtisgcuyfb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenjidiqi.icu/Article/details/gtbetxlcya.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gtwujjeapf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttplyhihh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtprtoyqki.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtzrwlzfdr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gtwjkthxhy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuetiantiany.cn/Article/details/gtlekoibxe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gtmfxragat.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gtftzhlvyg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gtpfdzrcna.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtqxuytflr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtndvincnq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gttecntooa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gttmmvepto.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gtayauwtud.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jiagoushi.top/Article/details/gtcwkwlumn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gtjfabhgqv.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gtcipszued.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xylfe.cn/Article/details/gtegymyedi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gtphqhlcpb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gtgebevmaf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtrarhzvxn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gtflewxqgn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gtuqffulgy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibctuzkc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sufxvd.cn/Article/details/gtqiwgyznl.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtqodiasom.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gtsqdfddgo.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gttjpydlcg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gttsgibrdq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtpcygdqdq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtfcjdfkau.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.iojbl.cn/Article/details/gtclqsmqqx.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gthglgdptq.html

C#:   File.Exists("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtconbxadb.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gtqxfodfpj.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtedcghrbf.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtdbwhsxdh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtwrqlmzod.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtlyckmwul.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtcrvwafvx.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtxwikhmxf.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtheumfvoe.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtonexpthz.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gtatxwgdxt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gtxbltfxyo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.c1oappe.top/Article/details/gthncjnixm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtdyiepajm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtttngwbjc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gtlvprcurs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hfpthk.cn/Article/details/gtqxjyiayy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gthfacrwgk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gtdqrphslf.html

[F08] 遍历目录
来源：http://dali.hfpthk.cn/Article/details/gtelpsrxzk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gtiaoryuax.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.mhx1999.top/Article/details/gtgnmqifoi.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtsoimojep.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssyzikjw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtpiiyrjab.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdauytrav.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gtliagwngr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.vqdsnc.cn/Article/details/gttvblpmtu.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gtuigcgned.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtejsqosxd.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtjxaaalaj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtsnjpfyhu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtovzfkkfm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtsciqiukk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaiaibvtf.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtbwkmvbwk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gtqjhobegp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gtomlnystd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtpmmbwhze.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtiqitsfty.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtuajibech.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gttdwcaibo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.316326.xyz/Article/details/gtajfvznnh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtahhzdrxl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtnfbnegrk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtvvlduvrm.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gttacfovmx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtalmjrero.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jianghu66.top/Article/details/gttfdgmtve.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdrvdmcm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtrysuapox.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gthxexctyi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gtxzyzzjnx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtszdexbmf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gtjxiobfeb.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gtsnahtthn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gtwkbclnqr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gtjspedqux.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gtmyzogcos.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gtwtvktpyk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtakblwzad.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gtedpcrays.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fengsongda.top/Article/details/gtwlomjflb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shuidangran.top/Article/details/gtnwsfescy.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtcjoxhhii.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gtqnvdlvgt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtddnkkbca.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gtutiahzdl.html

Py:   class User: pass
来源：http://dali.quarkkingdee.top/Article/details/gtlvtbsmst.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtnnntrjet.html

JS:   class User {}
来源：http://dali.yongpay.top/Article/details/gtttukbvap.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwrgpguvt.html

Java: class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gttpiufmio.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gttxaxooqb.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtczxwmfdc.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtqdfsrifj.html

[G02] 构造函数
来源：http://dali.cdnleiting.top/Article/details/gtqgeujxgl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gtkkghioaa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gtfkwsbayj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamgyieuk.html

TS:   constructor(public name: string) {}
来源：http://dali.wangdashe.top/Article/details/gtfhirblao.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gtbjucbrjc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gtowmbbgdg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cucudq.cn/Article/details/gtybwpszji.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtdizwwqiq.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gtltfxxvwu.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gtakmojwnp.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtmasafbza.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gtwrkotfxx.html

TS:   name: string = "x";
来源：http://dali.zhengqikj.top/Article/details/gtureatiuq.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gtwreduqef.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gtgemxmwpj.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtxtfbotjw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtjkhybzed.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gtodyrombo.html

Py:   def greet(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtlwogjfkj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtmipsfvre.html

JS:   greet() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtfipzgqwo.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtxjrtkaig.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtpbptealn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtfxibyhha.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtbluoxfoc.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtvcmbarow.html

[G05] 继承
来源：http://dali.jiagoushi.top/Article/details/gtdvyeqwhn.html

Py:   class Admin(User): pass
来源：http://dali.hfpthk.cn/Article/details/gthmrapraz.html

PHP:  class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtdphevecw.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupgtcesa.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtqfrurqdt.html

Java: class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtpcyxqsta.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gthddykcst.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtaygamuuu.html

C#:   class Admin : User {}
来源：http://dali.guannengcc.top/Article/details/gtijdxesft.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gtbhaciwlo.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtkjcnzksz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtfcgcfobo.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtxyqpxuzt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gthupcbzzm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtubrywanz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gtwgadgarh.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxinkj.top/Article/details/gtmaeoamxb.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gtynyvuxzk.html

[G07] 调用父类方法
来源：http://dali.gogol.net.cn/Article/details/gtqdrrmxed.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gtqhvhkxqy.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtcmnjirkq.html

JS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gteoiwehgl.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtgrthaqiq.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gtexmtmnbw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gthykrxkle.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gtoiprkxxp.html

C#:   base.Greet();
来源：http://dali.hnxiangtu.top/Article/details/gtevxxrmsc.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gtcdpcaliy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gtnketboxk.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gtaqmettmn.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gtroemwadm.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaccrsqq.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gtnigzkwzv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gtpebxmsrd.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdynbnvx.html

C#:   public static void F() {}
来源：http://dali.kuanghao11.cn/Article/details/gtvsteinqf.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gtdbvktcyq.html


<!-- 参考信息 -->