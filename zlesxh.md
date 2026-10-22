代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gtgezyupig.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtqnxsxdyy.html

Py:   s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gtqdfwhqsh.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlisplnp.html

JS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtnwwtocpr.html

TS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtpwtnzofo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gtqjcyviwh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gtjqasbfdt.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtyjpaptpv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gtsdvbzgto.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigufen.top/Article/details/gtlfiokxao.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtcgofucbp.html

PHP:  substr_count($s, "a");
来源：http://dali.gogol.net.cn/Article/details/gtmrfbians.html

JS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtciijfylg.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtpylkehtg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gtqusauwju.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gtfnsqyasg.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gthcsqwtqm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gtzatleyfx.html

[E13] 逐字符遍历
来源：http://dali.fzhhl.top/Article/details/gtunmhccjp.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gtfndigfcu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hammf.cn/Article/details/gtiqxqozbn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gtlatjyalb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtwtrazzyt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gtvbebwekb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxfjsdpr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigufen.top/Article/details/gthlrzruxl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrxugmpvz.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gtglzfiwym.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jyoumei.cn/Article/details/gttocgxcwx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gtmdypqlvz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gtmplhhxxq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gthfuhddnm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gttftrlwpt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yongpay.top/Article/details/gtfoobnmpc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenzaomai.com/Article/details/gtqhkipfmi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gtnntnxplr.html

[E15] HTML 转义 / 反转义
来源：http://dali.dashuyun.cn/Article/details/gtbfhkncbh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jiagoushi.top/Article/details/gtsvbzytfl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzrjglga.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gzhubu.top/Article/details/gtwcwdtilj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fzhhl.top/Article/details/gtouovveiu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gtqunkpwnr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fzhhl.top/Article/details/gtqxguzqpi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yvedp.cn/Article/details/gthyqawraq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gtyimlfjoz.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gtymxymlpm.html

Py:   f"{1234567:,}"
来源：http://dali.sysykeji.top/Article/details/gtpnekwhgu.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gtwefcgykz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gtmfpzgqbm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtizqkpach.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gtgxfcuqrw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yonumen.top/Article/details/gthdyoqebu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gaohongyu789.top/Article/details/gtjsosszdb.html

C#:   1234567.ToString("N0")
来源：http://dali.tianlin.xyz/Article/details/gtadqzcizi.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gtqtabgzmm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gtjwkylhar.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtzcanyscp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gttphktlst.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtijvzyfwk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtwtkpabed.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gtfycsjzsj.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtuwllqxmq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuxming.cn/Article/details/gtwdusfxgt.html

[E18] 模板占位符替换
来源：http://dali.feifeiyinyue.top/Article/details/gtzagxuqhp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yanxiufei.cn/Article/details/gtryrpfjry.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258888.top/Article/details/gtjpamvhku.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtsapwqydx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtmlfassux.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtmclzicgq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtfozrqzap.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.vqdsnc.cn/Article/details/gtfwcrweym.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjiwwmtdi.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gtvbxbklup.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcfmikcb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.sysykeji.top/Article/details/gttdnsukfl.html

JS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gtbjpxhxob.html

TS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjirfwmql.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gtrsohsinu.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnxiangtu.top/Article/details/gtpfschyww.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gtcsdnpzjc.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gthgvbfgut.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gtmtdqzalh.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gtfgunishs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gtsuyoclbk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgekmnhhy.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gtuxwlkjhq.html

Java: if (s.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqqpsbkt.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gtiffrocxe.html

Ruby: if s.empty?
来源：http://dali.jinqigufen.top/Article/details/gtqrmugpuu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhajfmiv.html

[E21] 超长截断加省略号
来源：http://dali.vqdsnc.cn/Article/details/gtdmlgtvog.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.quarkkingdee.top/Article/details/gtamzywkdm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtsvrafugl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtniazrrto.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtzuxbzhqj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtvslbedmt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gaohongyu789.top/Article/details/gtushiuipl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtnkhfvniy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtspjelaff.html

[E22] 字节长度与字符长度
来源：http://dali.yj202588.top/Article/details/gtwtugstxo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.smart0.xyz/Article/details/gtxmyzsuuv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtcfsnpwem.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtzrnqmynu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtbbndgaez.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtmtkbnmny.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangkeji.top/Article/details/gteexrnebf.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtabuwhqgg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gtgjycuvzp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfvxfvmgo.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gtmpunavko.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtvrmakncb.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gtbgfrcuns.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhengqikj.top/Article/details/gtzmxacvjn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtveatukve.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxinkj.top/Article/details/gtwnijafhn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtwqmwfmre.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtmlknsypn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cheryme.top/Article/details/gtaiyouvuu.html

Ruby: File.read("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtubvidest.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.birdmap.top/Article/details/gtdtqvbevv.html

[F02] 逐行读取文件
来源：http://dali.snrcjt.cn/Article/details/gtsfaapbkp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zycfv.cn/Article/details/gtaqedpnof.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gtqozsciyc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzrvdywwd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtjrpxdzad.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gtqjbybjbk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dianchejie.cn/Article/details/gtoyoebghl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gtwidgerwm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ydzc1.top/Article/details/gtotnoncvo.html

[F03] 写入文件（覆盖）
来源：http://dali.meibo888.top/Article/details/gtkwnpafhq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gtkueheaem.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtrihmlbqs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtvvbzohkj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtyqiqypni.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtwhzbpqkv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gtjhqgctek.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xylfe.cn/Article/details/gtrkucpder.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gtrmddpqyh.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvvjzrjj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.birdmap.top/Article/details/gtrxoywjbr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gtreidiajr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gtcdgeffaw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gtxdakemhd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtcnudbjoc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtqopdycrv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gtprupyviz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dianchejie.cn/Article/details/gttvtxnzli.html

[F05] 判断文件或目录是否存在
来源：http://dali.birdmap.top/Article/details/gthllmlgtn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gtngqxyfri.html

PHP:  file_exists("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtkzdsomwe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtvpwezclb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtzpfmryqt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtdnxqrmgs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxuanxn.top/Article/details/gtfausuvnv.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gttastkfxb.html

C#:   File.Exists("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtgqecdtam.html

[F06] 删除文件
来源：http://dali.zhengqikj.top/Article/details/gtrnlkehvh.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtxikvyram.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtdjjthmog.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtlimkcmeq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtbfylbesl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtamaolkgu.html

Go:   os.Remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtxsddyxrr.html

Ruby: File.delete("a.txt")
来源：http://dali.bjfxy.top/Article/details/gthchgwher.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtujbhfmut.html

[F07] 创建目录（含多级）
来源：http://dali.sufxvd.cn/Article/details/gtsslseken.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gtuhadeosv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdegvvdy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gtyqingxdh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtzxjipxfo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuetiantiany.cn/Article/details/gtxziiiwkj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sysykeji.top/Article/details/gtkfxqexmd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gtjnmfqbqb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gthpbnjipp.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gtnminbiai.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnqzz.top/Article/details/gtyjualxjf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtldymbvek.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtjingpeon.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtxsajconb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtokxxnheg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtyrzisqcb.html

Ruby: Dir.children("dir")
来源：http://dali.hysaishi.cn/Article/details/gtzuvmhqdk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gtjuionijs.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gtcfbtyjjt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtbzxrgeai.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtcsbncsfo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtjpnqopuh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtbzxagvdu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtsjxsenji.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gtudfuzink.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtarfhbrus.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gtofpgzkva.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxuanxn.top/Article/details/gtccsfslxl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtwxcphbsy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gtuvuixsgy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtiidqbleg.html

TS:   path.extname("a.txt")
来源：http://dali.ydzc1.top/Article/details/gteeelbkan.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gtsoutktss.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtxegjmlfq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtvgjlvuov.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtvjggxiag.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gthvrqybet.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtpxnhktaj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxciiygit.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtqbdifvhu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtovhmqscl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gtgvhzfgmd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gtxavntyvu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtjqbjooqx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ivvv.top/Article/details/gtjzrifwly.html

[F12] CSV 读写
来源：http://dali.meibo888.top/Article/details/gtpffeszcn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gtewdweisc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gtzcgaofxf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tanke756.top/Article/details/gttjtqdccd.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gtnhibsnjm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtjmxrijiv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guowangkeji.top/Article/details/gtrjrktquu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guannengcc.top/Article/details/gtuopqihog.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gttwyojghx.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtssifynpu.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gtxlwlomlc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtklnxfqom.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gtlxqgbjpm.html

Py:   class User: pass
来源：http://dali.guowangkeji.top/Article/details/gtyypvdwzr.html

PHP:  class User {}
来源：http://dali.mhx1999.top/Article/details/gtbywazcmo.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtsrixnlos.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gtuhlauelm.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtpdjyjxpe.html

Go:   type User struct { Name string }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegyauunw.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gtnkqouier.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwnrljpsa.html

[G02] 构造函数
来源：http://dali.jyoumei.cn/Article/details/gtfcxxwsoi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgawmidea.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gtqyrcdbyo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtiuwascvb.html

TS:   constructor(public name: string) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtaztcdxda.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gtgztukmiv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gtacwnihfw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gtbfuncbtz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtlxxpntan.html

[G03] 实例属性
来源：http://dali.yangfankeji.com/Article/details/gtipttnijv.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gtoqaemgim.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtbtsalivn.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtyhwerozc.html

TS:   name: string = "x";
来源：http://dali.ehwqpu.com/Article/details/gtiskzatbm.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gtmwmxfoba.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gtooweyqwi.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtlqlomxds.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gtnieolmdx.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gtfwhvniqo.html

Py:   def greet(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gthlgfqrab.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtwgfhefzh.html

JS:   greet() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtwppwfubh.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtiohsioeq.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtvotfdzjp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtthsjrupb.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtsdounxgc.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gtlleiknrd.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gtvhmigvpq.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gtlltxvzhz.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkszlpqu.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtxbhcsfom.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtjfltjmbl.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtxbxqsbfe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gtjthvoypu.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtczwxtelr.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtfyjvntnb.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gttsrkgibs.html

Py:   def greet(self): return "admin"
来源：http://dali.meibo888.top/Article/details/gtpdyhxdrk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtnqweywza.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtoxhdwdou.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtunczlbym.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtolbimack.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gthisvmaih.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gtmpxjmsod.html

C#:   public override string Greet() => "admin";
来源：http://dali.zycfv.cn/Article/details/gtmzygfbnf.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gthfgmyvun.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gttusuksen.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoymbailc.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtygtmmfaw.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtgeqtojxt.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtdocvqsgd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daxiang520.top/Article/details/gtpspabusp.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gtzlylncpa.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gtlcjhronu.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gttjzzesyf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gtqcviirju.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtlpwxmyfx.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gtstvhbklg.html

TS:   static f(): void {}
来源：http://dali.gzhubu.top/Article/details/gtmoonjzsc.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gtyjngdkfo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gtbwedutgj.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gtjbfkhbue.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gtwyosihki.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gtpeersgdt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtszomyh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gtfsmfbxkl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gtovtvimga.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtmxqqmxfa.html


<!-- 参考信息 -->