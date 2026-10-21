代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrkkvimz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgufenzy.top/Article/details/gtvylugsjo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtqkdjidij.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtdgelvcxg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yonumen.top/Article/details/gtradaidjm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daria6918.cn/Article/details/gtljxyehcx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sxryk.cn/Article/details/gtxerbajng.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtznbigqeg.html

[E14] URL 编码与 Base64
来源：http://dali.ydzc1.top/Article/details/gtcngmngum.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.316326.xyz/Article/details/gtrmnecovl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guowangkeji.top/Article/details/gtxtwvhdjo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gtwbrzmhpu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuanzx.com/Article/details/gtyidogpem.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtxbygwodt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gtjrgkjdcx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gtbvnkaips.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtonabrtlf.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gtzpieqsfc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gogol.net.cn/Article/details/gtavmwizrm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gtebjbrvkr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxuanxn.top/Article/details/gtnzefkbes.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gtbspeqmvd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gtyufzkwmn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiixairji.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gtnubwrkuw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gtivfmyeqf.html

[E16] 数字千分位
来源：http://dali.sysykeji.top/Article/details/gtncrhdbuk.html

Py:   f"{1234567:,}"
来源：http://dali.yonumen.top/Article/details/gttxzukhhh.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gtzzigejey.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtrzyoxear.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtjcbmxtbw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupqudvdr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.havefunace.top/Article/details/gtgxqczqfu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtmknezqva.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gtcfjjddul.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwdmlbff.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.snrcjt.cn/Article/details/gtczgzqgfj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnqzz.top/Article/details/gtesopkqcb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtprevijus.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtawlqcjfa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhengqikj.top/Article/details/gthsbzsehr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtbnlstmrc.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtvzorqwcv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.havefunace.top/Article/details/gtwuodaihz.html

[E18] 模板占位符替换
来源：http://dali.fzhhl.top/Article/details/gtnufvsvyp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gtmtcmrrfc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gtxjzgvril.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtqekfnkyu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtgtruuyst.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtwyqkojrs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtxmlsykjy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pycfn.com/Article/details/gttkijzwvz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.andypj.xyz/Article/details/gtqydmzpru.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gtsisrbslb.html

Py:   s.splitlines()
来源：http://dali.jinqigufen.top/Article/details/gtzofwlhjz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyvnkdmu.html

JS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gttphmlucl.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtfzkzakwz.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gtbaqzkhee.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gtvpbsbpwy.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gtjbzjehih.html

C#:   s.Split('\n')
来源：http://dali.chenjidiqi.icu/Article/details/gtfqbmolig.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gtieuaslgp.html

Py:   if not s:
来源：http://dali.yuanzhike.top/Article/details/gtvwdfpnbr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtbrocgjcq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gtynlfetea.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gtvjdyueix.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtrqvwtasv.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gtzotdfvae.html

Ruby: if s.empty?
来源：http://dali.jqgfzy.top/Article/details/gtwzvcmlld.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtceejstlp.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gtjbetdbks.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gtsqkcgrqu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtcgclypcx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtmmxjxqln.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtwirssmyr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwozaxqhg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvimmubq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtqufmxhqe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtytbvuslu.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gtdoirughn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvciyqmuz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtgomqyojz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtvnftcqtd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtrbiincsr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gtzvzqnxny.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yonumen.top/Article/details/gtssacquwm.html

Ruby: s.bytesize;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtbgxzlgmp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtnewyuucc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtzafksqmh.html

F. 文件与目录
来源：http://dali.birdmap.top/Article/details/gtsajoqomo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtpkcqkqyz.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtjyynvquu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gtpfrrvebk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gtvoblglhg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxuqectn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtljivyemg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtrbfybnxp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tanke756.top/Article/details/gtdzpcsqsf.html

Ruby: File.read("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtvrbvyrbz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtqlfraeay.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gtjjftovvu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsiqmlzsr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gttytucdel.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtsnvrvloz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqqjyyap.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtgntmumno.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gtesgvklwu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrscmgxlo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cheryme.top/Article/details/gtxxsxdppu.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gtbqukwuus.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gtmyjfxgrq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtcpecisxx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtoiqmuzsp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtqdrdaqel.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gtxmqfhuay.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gtfrefqach.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gtsjpeiltc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtcsqiqzch.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtimfkocif.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sweek.top/Article/details/gtodvdofir.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gtekiojomt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtbielqdso.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtymgsedcm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guowangkeji.top/Article/details/gtufbismzc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.bjfxy.top/Article/details/gtmcdkyqox.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gtyxxjwzau.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.meibo888.top/Article/details/gtvwizywtw.html

[F05] 判断文件或目录是否存在
来源：http://dali.zdqjudy.top/Article/details/gtppetvgxe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hywenlv.cn/Article/details/gtwjrhmjgn.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtjyoouhwq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtinhorwxs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtyjtvawsv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtcuiuyfqs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yongpay.top/Article/details/gthbakzaze.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtabomgell.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtofpvshqn.html

[F06] 删除文件
来源：http://dali.ybcxt.top/Article/details/gtjqynyeih.html

Py:   os.remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtjxpocxtk.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gttalwdsbc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzuaquuo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtpcyxjybg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtxvmxhzdv.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtnasdaoyo.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gtvnzovwik.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gtqbwtaanj.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gtuhcvjtgr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtbhovicvk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sweek.top/Article/details/gtgbdekmce.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtheaesdzo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtqnwvyjmt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gtnjsweufv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtveglgaze.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gtecqjugqc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jlsjyb.cn/Article/details/gtbbqsropo.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gtmzcqmwxw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkqdrpyn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sysykeji.top/Article/details/gtkawnfdhz.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmusswxao.html

TS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gtoykxuytm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtcflcdobm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gtytjgrntu.html

Ruby: Dir.children("dir")
来源：http://dali.zhengqikj.top/Article/details/gtogusdbsk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.c1oappe.top/Article/details/gtiyhpuuio.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gtawzsufon.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gtecokymiy.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtiutclerw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtojzznbkr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtjhqashtj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtyxlbgmol.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gttkhzqefh.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtbiidsiqw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tianlin.xyz/Article/details/gtjokfpzqx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gtwyhndgfq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegpfgekv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtjsnnuagq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtavlxvfyx.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtzrfrgabn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gaohongyu789.top/Article/details/gtgzkyhfxe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gttvhejrtj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtrctjgpmw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtfchrwwnx.html

[F11] 复制与移动文件
来源：http://dali.gotoacloud.top/Article/details/gtgrrahryo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtgyxtiylx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gtigypynwx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtbikmqskp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtjffpstgd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hywenlv.cn/Article/details/gthzkchkfy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gtzjriuuhy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtwjokjmfl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yongpay.top/Article/details/gtqifgdgah.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gtejicdtsg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtximlzvvl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gtwpabmnom.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gtsnppknyf.html

TS:   // 同上
来源：http://dali.hammf.cn/Article/details/gtzkjbcplz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gtkgzuisxl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gtqgpdkjmu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gttcnzzxrh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gtkyizwivj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtpmijcvyw.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gtmyrfacjc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtimwqjfha.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gtxesocycz.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gtzmbrshgn.html

PHP:  class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmueyeds.html

JS:   class User {}
来源：http://dali.iojbl.cn/Article/details/gthtgrfeir.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gtgydpbpyn.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gtbzlvxbhu.html

Go:   type User struct { Name string }
来源：http://dali.gzhubu.top/Article/details/gtmnunkfhm.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtjhkxzhmw.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxvkwdxc.html

[G02] 构造函数
来源：http://dali.cheryme.top/Article/details/gtdjdvccdg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gtjwwtmxsy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtqjxhnbsm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtpbvrcewy.html

TS:   constructor(public name: string) {}
来源：http://dali.zhengqikj.top/Article/details/gtbwrwgqhz.html

Java: User(String name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtmofzdyhc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavjsmstg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gtapyxoigl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gthoiuxgao.html

[G03] 实例属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdirzmgd.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtupulmnuz.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauvosbrk.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtopnttwel.html

TS:   name: string = "x";
来源：http://dali.aibaodan.cn/Article/details/gthzslwzpl.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gteyhjerca.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gtpzgpczyo.html

Ruby: @name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabzgnuxr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtifrytyjt.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gtmisltucx.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtxnkufjbp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtcfzkxmfz.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtmwvnkcea.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtdojjhmpq.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtlnvpmghq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtiigytymj.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtrhuszbdi.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtavuuodxd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gtvhykfuih.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gttnmmtqfr.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gthwvzxuwx.html

JS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtcdhtqaua.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtgradquqk.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtmaplalhy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gtdhlahwbz.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigzjxxoz.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gtfvreulod.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gtgrhtlgpu.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gtoqljntng.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtkwliwzhx.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtiqillyvy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtqldxpbrl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gttksgdgrc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gtqhxvfcqf.html

Ruby: def greet; "admin"; end
来源：http://dali.xuetiantiany.cn/Article/details/gtdbyhevqp.html

C#:   public override string Greet() => "admin";
来源：http://dali.daria6918.cn/Article/details/gtjbituwal.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gtfierahzx.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gtitvujgrf.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gthaxdjbaz.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtfxivhhyo.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtgksqvqit.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtfqdhzjbr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtybuhljee.html

Ruby: super
来源：http://dali.redwolf501.top/Article/details/gtbcenguct.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gtswqodagn.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gtmoistzts.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gtuwsqhkve.html

PHP:  public static function f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtvokfsbku.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gtdadcsouw.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gtinpqsmkw.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gtvdeztzkf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gtywjkulqf.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gtwjscrixm.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gtoguvbymd.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gtfnvykjmn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtffyhyfbq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtxlnxnqkf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gtwkklwblg.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gtkaznsglo.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gtggvtnqii.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgufenzy.top/Article/details/gtbldgajwg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtwaisiwen.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gtaybslixg.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gtwkxnnhhl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gttejccrhm.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtiipoynaq.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gtwhwhreng.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtydryvbrv.html

Java: public / protected / private / 默认包级
来源：http://dali.tianlin.xyz/Article/details/gtwaaduiia.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guannengcc.top/Article/details/gtcdekhtjs.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gthmrwnorz.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gthmrqdkmh.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gthhavwiwn.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gtqfgcvhna.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtscdfbxxj.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcevtjmil.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtmamvmsuq.html

Java: public String getName() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtqhsktkko.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtodtwbsab.html


<!-- 参考信息 -->