代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtniznsvvu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhoulong.xyz/Article/details/gtsemweplb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gtmfwxwgjg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gtyvwxhdwu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.316326.xyz/Article/details/gtsczcbcaj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtgypswzkc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gtrybstqjw.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtpdvdgpfj.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtyhdfeufc.html

Java: String.format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtbxixinzd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtsfulbwwl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtrbemksss.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gtyyacjzoa.html

[E11] 反转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtyrmwcgoa.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gthwswkgwt.html

PHP:  strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gtadirhses.html

JS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtmxmmaaez.html

TS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtqlncnjmz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tanke756.top/Article/details/gtkxwjhntz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aibaodan.cn/Article/details/gtgtpzppga.html

Ruby: s.reverse
来源：http://dali.zycfv.cn/Article/details/gtjtdindlb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtugsnihbx.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigufen.top/Article/details/gtbcuznkdy.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gtmsadjmem.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gtczsrilrd.html

JS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gttqhaeoiq.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtevbqoksx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gtouxbghgy.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gtnhagsgjb.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtihnknjxz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangshuangyany.cn/Article/details/gtnuipqhzk.html

[E13] 逐字符遍历
来源：http://dali.snrcjt.cn/Article/details/gtturgzklo.html

Py:   for ch in s: print(ch)
来源：http://dali.ybcxt.top/Article/details/gtmkzkkxod.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gtjqutqhiz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gtgjgnhcge.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtmiwmzdek.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtymlfewhs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258.top/Article/details/gtngxhncdb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.snrcjt.cn/Article/details/gtsypdbgsn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuxming.cn/Article/details/gtldnomajl.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gtknfevbrd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmffvaon.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gtmulzcavn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pycfn.com/Article/details/gtuutmheiy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gtudrqsgik.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtpdsgzwcd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gteovqkzwn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pycfn.com/Article/details/gtugsecafm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gtzadehfww.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gtzzdcyscm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenlongwang.top/Article/details/gthlwckguo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cucudq.cn/Article/details/gtdxlclocq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.316326.xyz/Article/details/gtaygyktzh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aibaodan.cn/Article/details/gtzugxwxrw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ydzc1.top/Article/details/gtiacepwtw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gtuzxkyqoc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gttnkzfpdf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cucudq.cn/Article/details/gtmeaxqyub.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtmjpsfgpl.html

Py:   f"{1234567:,}"
来源：http://dali.nanxinkj.top/Article/details/gtbinevvph.html

PHP:  number_format(1234567);
来源：http://dali.guowangkeji.top/Article/details/gtvzmdiqsu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtfyxajsze.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtwwbcfqzb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gtrlnhpwlz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgufenzy.top/Article/details/gtmbnnknvy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.redwolf501.top/Article/details/gtdczkxvpr.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gtfzwbpfyy.html

[E17] 首字母大写
来源：http://dali.chenjidiqi.icu/Article/details/gtilrsourd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cheryme.top/Article/details/gtfvrowoee.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gtmmrcinzb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtoejzwjrx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtqnuvlcxd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yonumen.top/Article/details/gtwyezgzdx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gtzukffasd.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gtbkxaijib.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.bjfxy.top/Article/details/gtxnmqxevu.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gtzjmmvnsq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dianchejie.cn/Article/details/gtjkzrsxkj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gtqdceomfr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gteplrmols.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtwnprqacb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtmermlfum.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtoyejchzg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gtthavpxvs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtoliplkgh.html

[E19] 多行文本按行拆分
来源：http://dali.gogol.net.cn/Article/details/gtgwjwkiok.html

Py:   s.splitlines()
来源：http://dali.guowangkeji.top/Article/details/gtyymxthyn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwddkjwv.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtmoruawui.html

TS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gtruvnagpv.html

Java: s.lines().toList()
来源：http://dali.zhixingplan.top/Article/details/gtlpvksffv.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258888.top/Article/details/gtfwiyeeav.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gtvyzvcrmo.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gtjamfwatp.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gtbltttshe.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gtttykmqrt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jlsjyb.cn/Article/details/gtluzlkyyd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sysykeji.top/Article/details/gtluxcckin.html

TS:   if (s === "") {}
来源：http://dali.quarkkingdee.top/Article/details/gtjtrecwok.html

Java: if (s.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtupbtufoa.html

Go:   if s == "" {}
来源：http://dali.hnxiangtu.top/Article/details/gtegztorqr.html

Ruby: if s.empty?
来源：http://dali.tianlin.xyz/Article/details/gtvyvaenmp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gtchzgkizq.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gtowixhbwv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gtkiihpeql.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtjsbbcben.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtmgmsmtmo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtzhxqolir.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtrfpnzwnx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxuanxn.top/Article/details/gtocwybtww.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtlfhjcdwd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtgilatahe.html

[E22] 字节长度与字符长度
来源：http://dali.birdmap.top/Article/details/gtpqvyiwoy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gtaoarxmva.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilcdqiek.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtyvblfcbu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtrrbdtoda.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258.top/Article/details/gtsbzekhua.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sweek.top/Article/details/gtcdqpjwpu.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gtfartumoq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gtnzipnaoq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwdhxnvvb.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gthavepsnl.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtmsyxhkbb.html

[F01] 读取整个文件
来源：http://dali.meibo888.top/Article/details/gtqvmkqezg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shangyingyoupin.top/Article/details/gtfnbncktv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtreywdepq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gtdxihnllu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtzqpkvivi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtencmgumv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.redwolf501.top/Article/details/gtidrffycj.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtxksrbjyd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtzenhnnhl.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gtfimfbeuf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gtduspekiv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtxunfdqud.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtvgmcwbho.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtlmoionui.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gtmvjvxiub.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtxyrqsucu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedfcapmj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gtnyrnbbay.html

[F03] 写入文件（覆盖）
来源：http://dali.havefunace.top/Article/details/gtkrtebnmd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gtbykoixfe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtvwzymrnt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtbahpnzgj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtbnpmuqxm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gtamoktpmz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cashguo.top/Article/details/gtmmlqgjxk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtiygdwyeu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtmwupruyv.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gtxckoeihf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtrquhakao.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gtiqvzcmag.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtfmixueux.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtfqpalpzj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gtwogozvdq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtqwfnkvlk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cheryme.top/Article/details/gtnpggsxpe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jiagoushi.top/Article/details/gtebzuxkxi.html

[F05] 判断文件或目录是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtlbaegwtn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gtqdvhvivl.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gtvhztzuae.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtrqnhbhai.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtldtauhxg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gthadcgcpn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenjidiqi.icu/Article/details/gtjflrawqj.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtnlwwhngm.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gtjmjepwku.html

[F06] 删除文件
来源：http://dali.jianghu66.top/Article/details/gtfjizexrv.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gttgmfoglo.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtvzlkvqet.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtkgbtouso.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtkcgploxy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtccepoiir.html

Go:   os.Remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gttmtujpgd.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtmfqclpmq.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxsflizo.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gtlcukmvmr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtvaqdepkx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gtqvhaioxv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gtzyvzqpfa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gthaahqamc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gtjttdhmjq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.c1oappe.top/Article/details/gtllpyxdjr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gtqptuoykt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.kuanghao11.cn/Article/details/gttejmoxvq.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gtabwotsmh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gtcslzxjjs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmfvlxvwj.html

JS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtpbmozoxa.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtvhnorfpp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtnrstokrg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ehwqpu.com/Article/details/gtuknljtpu.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gtqbqeofai.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gtltqfdmyw.html

[F09] 获取文件大小
来源：http://dali.cucudq.cn/Article/details/gttzzucpgl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtjdszdhvl.html

PHP:  filesize("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gthznritlx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtvyjfmrkv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gthxfyfpdh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gthtpszagl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gtejcvachr.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtbfctpvpe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigfzy.top/Article/details/gtdpqzlhyh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.0kj1m.cn/Article/details/gtnhjvrszz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gttiurolmb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ybcxt.top/Article/details/gttgurwpej.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtghalcyso.html

TS:   path.extname("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtxpwkcajj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gtaiwajhgw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtuizibjoy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtpwlvkuas.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtalcxysso.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gttzpglfeh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtcxdgmohg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shuidangran.top/Article/details/gtodpekuzt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtwdsdzrpl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtdhrtcomu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtdkzytwiv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtioynyakf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtmmednaag.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gtskegvzqk.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gtbzynvlie.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gtgrboqzed.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gtozjzhvmx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gtnfibgkvw.html

TS:   // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtrogauyzb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtoximeazs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gtlxnzifcx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aibaodan.cn/Article/details/gtuvcaahvq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gtmrtlbykz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtbcilabdc.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtjgardkjl.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gteycifyoa.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gtrrrngluk.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gtxfoysilg.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gtugrcggng.html

JS:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtmirjvyre.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gtqfaijihl.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gtaydprkec.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gtshuwrbqc.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gtgxdysncv.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gttutdwesc.html

[G02] 构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtbscwqajh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtjbtrstlg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gtgdqolzlw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtofihsrjn.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gtclrjfgql.html

Java: User(String name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtngadhynz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgbhxrmf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmcgrxfe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtqxdnfgnj.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gtnrxczaab.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtahxqjqxb.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gtlowzmbgp.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtywxrfowa.html

TS:   name: string = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gthptfittg.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gtknhrfytx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cucudq.cn/Article/details/gtqgvapvso.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gtjfrvaecg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtaymduajg.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gtrvpmasxk.html

Py:   def greet(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtgcfowind.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtgcfxcvcj.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtbzihdgxw.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtehxkjmro.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtoogctyrp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gthvicmayk.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gtktoeqbed.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gthkvnyjup.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gtfsqmxvov.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtzinqhnat.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtmwvxjwqj.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtbdvzfzic.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyzfkylz.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubfkhjce.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gtxxjigihm.html

Ruby: class Admin < User; end
来源：http://dali.guannengcc.top/Article/details/gtmthcuybb.html

C#:   class Admin : User {}
来源：http://dali.ydzc1.top/Article/details/gtnmqwvlag.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gtfhlxydbv.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gtegyodsji.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlxefomil.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtxhuijfrp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtdasyvbcj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtbjjhlbbs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gtmikpfafv.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gtlkrbflpr.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gtppwzsfjn.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gtijwllrpr.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gtdtqnokyg.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtfyrsafzl.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtlrlilfek.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gttrazsrue.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtmzkcwbbt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gtjqpmmfol.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gtdouhyuhz.html

C#:   base.Greet();
来源：http://dali.hnxiangtu.top/Article/details/gtezzohcqf.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gtjqpjicxp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxuanxn.top/Article/details/gttrqasdxa.html


<!-- 参考信息 -->