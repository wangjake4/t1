代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtayooyhvs.html

[E11] 反转字符串
来源：http://dali.havefunace.top/Article/details/gtyvddizmp.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gtotdmlsrc.html

PHP:  strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtsekbzvtv.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcwfeyhh.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gthmjidsop.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gtqxrmkhec.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gtqfivmjbz.html

Ruby: s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtveliwiuj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gtjtahglrj.html

[E12] 统计某字符出现次数
来源：http://dali.hnxiangtu.top/Article/details/gthpxwopke.html

Py:   s.count("a")
来源：http://dali.smart0.xyz/Article/details/gtesqujqny.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangtech.top/Article/details/gtapptfqwo.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtejysmafd.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtixdmydai.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gtajqwdhyx.html

Go:   strings.Count(s, "a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfonopndn.html

Ruby: s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtuhljojdy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gtfucthwui.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gtbqkkiyfb.html

Py:   for ch in s: print(ch)
来源：http://dali.cqqwz.cn/Article/details/gteuikvlbg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hongshengwenyu.top/Article/details/gtucvmdgwy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gtdnffkxjk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtkhfnueae.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ybcxt.top/Article/details/gtfzzjhfsj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.haohaochexian.top/Article/details/gtsvzxrcsd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jyoumei.cn/Article/details/gtwdhzrbpy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gtndewdpdp.html

[E14] URL 编码与 Base64
来源：http://dali.yonumen.top/Article/details/gtvniumkay.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hfpthk.cn/Article/details/gttolssvyn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dashuyun.cn/Article/details/gtywjkgxpe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xziqi.cn/Article/details/gtcmemjkwc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cucudq.cn/Article/details/gtgaccltju.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttartbwdh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hammf.cn/Article/details/gtytfdjzwm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtfaheldid.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.iojbl.cn/Article/details/gtudaswnsb.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gtyomyrhsm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yanxiufei.cn/Article/details/gtprthngef.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.havefunace.top/Article/details/gtqyfedmos.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gtkgvjkwrl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zdqjudy.top/Article/details/gttyrkpukd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gtxsnotvye.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gogol.net.cn/Article/details/gtksoesbtl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gtwkpqvmjd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gtarsjhuzt.html

[E16] 数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gtlsjqlvyu.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gtcwgomkry.html

PHP:  number_format(1234567);
来源：http://dali.shuidangran.top/Article/details/gtddidclwk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtzomziszj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtucngocej.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwecijpaz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gttznzipwy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtymgarvem.html

C#:   1234567.ToString("N0")
来源：http://dali.hnxiangtu.top/Article/details/gteywrfbgg.html

[E17] 首字母大写
来源：http://dali.andypj.xyz/Article/details/gtcvbkcnsc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jiagoushi.top/Article/details/gtmithbvwp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.316326.xyz/Article/details/gtfdehcxzh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtpyadflrf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtlhiudhua.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhixingplan.top/Article/details/gtfgokbqed.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtognbiyyi.html

Ruby: s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtsfdxgyel.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklkzuscq.html

[E18] 模板占位符替换
来源：http://dali.nanxuanxn.top/Article/details/gtyumviiul.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.kuanghao11.cn/Article/details/gtgdegfgno.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gtyrscpibd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyenytbwv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtpfmdocez.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtaxbsggyz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gttmwmckqx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hongshengwenyu.top/Article/details/gticliqine.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenjidiqi.icu/Article/details/gtpthhigim.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxtomrch.html

Py:   s.splitlines()
来源：http://dali.sufxvd.cn/Article/details/gtiincjiwl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nwbrower.top/Article/details/gtsgoyotpo.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtwqxddrcv.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gteuxdxvst.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtraohyeru.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gtsefuxmot.html

Ruby: s.lines
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpkrbacm.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gtwmodcqzm.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gthinlduds.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gtbahsrthp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gtbgmkovyp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gthjinbvrt.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gtdxsvfhgk.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtajzpovar.html

Go:   if s == "" {}
来源：http://dali.feifeiyinyue.top/Article/details/gtovlrlzty.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gtjzsffdka.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258888.top/Article/details/gtfljczjni.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gtvweiwbeb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gtfqtttiyk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtbcwvaltq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtlgecxkmv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtlicrmnfh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtjswhkudt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gtqaxsebip.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtjnenynzh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtcyrmyfvh.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gtzdmpgkzz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssyxoccc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtnfzbvkfb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtbxmzbqnm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtahyrezdf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtzylfcmbi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guannengcc.top/Article/details/gtncdwlvmm.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gtuvmaczab.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gteephmwxu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrhwccnxa.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gtsxnxpqnb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtqkaekbhn.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gtjhwbenym.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gtqtxwolrr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtncxtrvgz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiivklgkm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqaofcsh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtipskqlow.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tianlin.xyz/Article/details/gtpiheysfu.html

Ruby: File.read("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtksmjwyqo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtaocsqawa.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtnrhhdeuh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hywenlv.cn/Article/details/gtzozrjcel.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqqccxco.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtualydurl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtmifoqfqd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtpqvflabr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.birdmap.top/Article/details/gteglozcbz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dashuyun.cn/Article/details/gtmxpjqywe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gtierjzhbt.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gtlsdypxrd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gtfpinptin.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtvbkaiprw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtwlfneeaz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtadzazyci.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gtmanrllyu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gtcgxozhuf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gtrweizkge.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtyaiwwfja.html

[F04] 追加写入文件
来源：http://dali.smart0.xyz/Article/details/gtepgcbllt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtrvamldzj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gtpqtrcjlx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtakxuuses.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtkfgsrxsf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tanke756.top/Article/details/gtwkosvkzp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gtltsjkwvz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xinyue.icu/Article/details/gtumkkifcx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gtdflbaijs.html

[F05] 判断文件或目录是否存在
来源：http://dali.yvedp.cn/Article/details/gtinahrdom.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yongpay.top/Article/details/gtfqxgycrr.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtcioxmquc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtjuglqtow.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gttjfnpnlc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtutfisdyt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gtosgnqlra.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gthxobvpze.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtwpdueydm.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gtldprxdij.html

Py:   os.remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtwtzrpzya.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gteyauzkxg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtyhzeyzfr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtfyxbstgy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtzgfrbqik.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtwtzqvgkv.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtvmyjkghq.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtzznwkbrt.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gtjoorzvnb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gtxvzcccrr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gtuotgmrbd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtnkylnjgw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtxmqcrvay.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gtnqorjypd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gtnfvkhlia.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gtikrjltir.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtfbwspmek.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtqxofapvq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gttmdxnkwo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gtxedsfwvy.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtzqgalcsc.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtaootltsf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtdjlkptqs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gthglcmmng.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gteryrsmoc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttthooicx.html

[F09] 获取文件大小
来源：http://dali.wangdashe.top/Article/details/gtvhuwdovx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtymeaucof.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtuejwijof.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtrbzfhuxn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtrbqdyagt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtggmmeuxa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhoulong.xyz/Article/details/gtjyfzoxru.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtykgblzrs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258888.top/Article/details/gtfblwazpe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gtqjcmzinr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtwyfrslrz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtfqjanhlr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gttojbpqxj.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtbmnhnjmh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hywenlv.cn/Article/details/gtglluptcb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtjfuxrptn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gttplyiigd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtkgywyqcc.html

[F11] 复制与移动文件
来源：http://dali.yangfankeji.com/Article/details/gtgbddytld.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtbxioxtus.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gtmgcdqjao.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtssbeglgx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtjlfiesqf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gtzfpcnxee.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gtspnybzgb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtqwtdiqxk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtcwhvtgwd.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gtccovyzfc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gtbbftqyrn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gtlyagpfhh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtphverffn.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gtsgcuajsk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhengqikj.top/Article/details/gtgxknqdfe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gtyqyzahab.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gtqfotkbtb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gzhubu.top/Article/details/gteudtkmfe.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvdxhgqpk.html

G. 面向对象
来源：http://dali.xuanzx.com/Article/details/gtnvhosude.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmqnlwghp.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gteadfsqvx.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmooiien.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gtbmucgfvu.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtoeclbjpl.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnqwuxnla.html

Java: class User {}
来源：http://dali.fengsongda.top/Article/details/gtlugbapfd.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gtjkccvylb.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gtbtqnptxg.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtbpqlqedk.html

[G02] 构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtjmlchcdt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gtsmuuilpw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gtahldfdqf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtequsuloc.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gtixtnpddr.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtcjzssdhx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gtoiedwato.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gtamhswaqt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtbmdmngwz.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gtzabyzouy.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gtdxtlohdx.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtmuabtkez.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpuqhdaf.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gtinoddurk.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gtmmhnrnfv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gtmpueinre.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gtrobtupec.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gtnqbpjhpe.html

[G04] 定义方法
来源：http://dali.havefunace.top/Article/details/gtgsybdtmc.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtxadxpsmd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtyxajqgea.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtjgsizeas.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtcesxohns.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtyadprzuk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtpwelfskv.html

Ruby: def greet; @name; end
来源：http://dali.zhixingplan.top/Article/details/gtkqcozgoa.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtvhunauyb.html

[G05] 继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnujiekzj.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gtqqcuboef.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtoufswykt.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtqgxpkavs.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtcfgynzan.html

Java: class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlcjrmbvd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gtiojgxini.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gtrpldlivg.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gtxkxeppea.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gtcrgypowq.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gtooawiflz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtstwhyrlg.html

JS:   greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gttyfclvgx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtqjtesynl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtctkjyyov.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gtjautpqkx.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gtdvtdqqbw.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gtngjqlvnr.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gttikxthrh.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtwhsgzmuq.html

PHP:  parent::greet();
来源：http://dali.birdmap.top/Article/details/gthobyesfp.html

JS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtnbxyzhio.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtyultlbjp.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtanrwrqtp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gtlsdfoptu.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gtwtfbwqoj.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gttyldngym.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gtzrxkgqwj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gtasrkhtbj.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjwvmggh.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gtigeucbxr.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gtnobyukkj.html

Java: static void f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjccpomzs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gtorjwluqb.html

Ruby: def self.f; end
来源：http://dali.hfpthk.cn/Article/details/gtciovqjup.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrlqejnuf.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gtvzluaker.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtfjibvbmq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gtlcwgqwzx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gttyfgokam.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gthusyuohq.html


<!-- 参考信息 -->