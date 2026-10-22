代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtomdympnw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pycfn.com/Article/details/gtjtlwwzsg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gtsbkygprm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gtuzijvrlp.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258888.top/Article/details/gtacrudkcz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dashuyun.cn/Article/details/gtucemynss.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gtjfzevgfp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258.top/Article/details/gtqwiekgvs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gtqerqqxgk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtetxicwlr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gtvvngatsf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gteysvcxxz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtjulbubdz.html

[E15] HTML 转义 / 反转义
来源：http://dali.mhx1999.top/Article/details/gtglrxljbm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gttpiwgoge.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jiagoushi.top/Article/details/gtgcgdzbxd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gtnlirwqjf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnavcsxaj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhoulong.xyz/Article/details/gthesjhuim.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtuobuelxl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gttigetoeh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtvpraeqxk.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gtshwuwxzm.html

Py:   f"{1234567:,}"
来源：http://dali.gaohongyu789.top/Article/details/gtrkuqrnym.html

PHP:  number_format(1234567);
来源：http://dali.chenlongwang.top/Article/details/gtxwiszjnp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtsgpggvqi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtykjrvmun.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtuijshpid.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gteymvxxqe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gotoacloud.top/Article/details/gtongoiwgh.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gtcssjemyl.html

[E17] 首字母大写
来源：http://dali.ydzc1.top/Article/details/gttcynxybx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gtjfrkrwax.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ivvv.top/Article/details/gtpafnixfa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrswouhq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtcbrukodd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gtyuhxauar.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ybcxt.top/Article/details/gtuvtfkbht.html

Ruby: s.capitalize
来源：http://dali.birdmap.top/Article/details/gthkijqjtx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuetiantiany.cn/Article/details/gtouwyaqyc.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gtjfxrpfpc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuanzhike.top/Article/details/gtdrnesjaf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gtuxtsjvzy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtrdwmxouq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtufpvrbcd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtonqhdrlz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtehqptxzb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmhtishm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gtqpyyssfn.html

[E19] 多行文本按行拆分
来源：http://dali.nanxuanxn.top/Article/details/gtfmqkpble.html

Py:   s.splitlines()
来源：http://dali.zhiwuduotai.top/Article/details/gtwksopjua.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtdpyrwklq.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gthgwikfax.html

TS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gtlqqcqecw.html

Java: s.lines().toList()
来源：http://dali.yongpay.top/Article/details/gtxcotoeza.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtgzsyranq.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gtixmnyplf.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gtovweabmm.html

[E20] 判断字符串是否为空
来源：http://dali.tian-w.cn/Article/details/gtjuunpzjt.html

Py:   if not s:
来源：http://dali.birdmap.top/Article/details/gtofahqzac.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gtjaluyvsz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yangfankeji.com/Article/details/gttxrqzdxi.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gtelajkcxc.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtrondmyvy.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gtswzcltsh.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gtosqbkmjv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gtsieztrnr.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gtjzmfmdqi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gtsbhzcvah.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtojcgrtmr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyanzult.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtoaksojkm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtxyqrdofz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guowangkeji.top/Article/details/gtjxcqtpgq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtankdskli.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtwwbojmdj.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gtjrtjvwzm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.smart0.xyz/Article/details/gtnfxsqibj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtycczwhsx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtaaguotiu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtyvyquwwm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gtvhymmvdk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sysykeji.top/Article/details/gtdvcdtrjg.html

Ruby: s.bytesize;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtwskrhpqe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhucxjld.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvjumhfwq.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gtzfqxuemh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxvnfeyrt.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gtvmxypyed.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gtaxewcuai.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtjidviino.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ydzc1.top/Article/details/gtnhpowczu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtmknoqhsy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtuoenvuur.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gtmnbuvarp.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtqqhkusif.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gtitknbsxz.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gtnkegiqlk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gtjkvvhsmr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gtgchzvzqn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtokxshvvc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtxvwcvijf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtubvzlqeg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gtxdopadga.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gtmjkfdcnq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sysykeji.top/Article/details/gtvdzhyfeu.html

[F03] 写入文件（覆盖）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuezkyjat.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hongshengwenyu.top/Article/details/gttqercbpj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gtqcnpxnsr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutitotcn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtztfswmqf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tian-w.cn/Article/details/gtniragkty.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.andypj.xyz/Article/details/gttjmydpxq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gtqiprrsmr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtuhjaffkp.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gthgmtcwbg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozlsxqei.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gtzamajkbx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gtwqblnffe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtndwuzjmn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrjufoeh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtpocpokwf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenjidiqi.icu/Article/details/gtshrnedrw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gtftgofzzv.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gtvgdtfhsg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hongshengwenyu.top/Article/details/gtwhfuhmkw.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gteqxxkphw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtirofpmtl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtqqorbeco.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtoboijmfu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gtwoltstez.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtuhdcgjgg.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtuxegxjxi.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gttchxieje.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtvsasrvgs.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gttkqasacd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtrnhqybaq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnratpdc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtcofebewf.html

Go:   os.Remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtrbvlotuf.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtjibkibyz.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtixfsxxhi.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gtytmwonvy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gtucjvlcvm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuanzx.com/Article/details/gtspkvyinx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gtvpihdeyu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtepikgfsw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gtbacpkqra.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gtdfvfvnwd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ybcxt.top/Article/details/gtrxagesyr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gtvhvkcgbk.html

[F08] 遍历目录
来源：http://dali.andypj.xyz/Article/details/gtpejtfxmh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tanke756.top/Article/details/gtzznmtqnf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gtczemchmk.html

JS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtpkoleoui.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtfznhljxo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtofbdfncm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cqqwz.cn/Article/details/gtujfuxsfz.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gtlcitponc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.c1oappe.top/Article/details/gtefycyypw.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gttvqngdth.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtiyugcwby.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gtlrfrmhrh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejkoaecg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtvvyfwvdy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtsfzvodho.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gtvpiaxmap.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtoqgqpdah.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtidruwflj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gtkhofkrds.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtxprqidrp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtgxxjwvyu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtkehjoxty.html

TS:   path.extname("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtaomyudzy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.quarkkingdee.top/Article/details/gtygvmvobx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gttrrhvadc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtmveshoun.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtrdsnqpbg.html

[F11] 复制与移动文件
来源：http://dali.gogol.net.cn/Article/details/gtrzpsyyxw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtvwfeatql.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gtjemiuomj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtrqfahxuf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtfroaziba.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gtigvkexen.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenlongwang.top/Article/details/gtklekrfwj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtvxkyfmcy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gtcabfnaex.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gtozaraztc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xinyue.icu/Article/details/gteyawsfde.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gtidolhwmu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gtesenzswv.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmwasuso.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gtcwjqeusw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gtbnwbidce.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gotoacloud.top/Article/details/gthtinmvya.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gtydcfagzb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gteiejdqje.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gtjtvjxiqc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtshzihqqt.html

[G01] 定义类
来源：http://dali.nanxinkj.top/Article/details/gtzpeqpjrr.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gtrbgvqlzc.html

PHP:  class User {}
来源：http://dali.meibo888.top/Article/details/gtbzyhalpi.html

JS:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtmzwhylds.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gtmzuwxjck.html

Java: class User {}
来源：http://dali.birdmap.top/Article/details/gtwfwcgazj.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gtflkoloxm.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gtzyglbzjv.html

C#:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtqvpthxap.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gtnlwrzhzb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gtqleklyzb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daria6918.cn/Article/details/gtcqowiddz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmttkjwk.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyelxotew.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtxuuivjps.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtqzhuluif.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gtdcbpddul.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gtjkagnltj.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gtpwbpxdzo.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtcfqpvjrj.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtnmvjletw.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtkibbjshu.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gtmnfiwrcn.html

Java: private String name;
来源：http://dali.pycfn.com/Article/details/gtqiveouky.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gtxpjjmpsv.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtcflwxqja.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cucudq.cn/Article/details/gtswerkgnm.html

[G04] 定义方法
来源：http://dali.shangyingyoupin.top/Article/details/gtsgjiaicl.html

Py:   def greet(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gthkhtkmar.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtfniyzrpg.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtsgvdfzxz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtlcndaigz.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjxxxgtuu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtygmecuwg.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtllocmvkh.html

C#:   public string Greet() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtkoagjsfj.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gterddsotx.html

Py:   class Admin(User): pass
来源：http://dali.zhixingplan.top/Article/details/gtslwouzdk.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtgaevthrk.html

JS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gttsfieunt.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdibjzfb.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gthytuvnqp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gtqcqxgwhd.html

Ruby: class Admin < User; end
来源：http://dali.dianchejie.cn/Article/details/gtdkmbdqcz.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfpfcduf.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtjzubbrhu.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgfzy.top/Article/details/gtzfclpawi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtxfbpzmbq.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtnraqlftl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtsynapcmf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtjmafeuyy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.havefunace.top/Article/details/gtxdnexeoz.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gtssiyfvql.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gtuvecgnap.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gtffyvydyx.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtcpjfrrzr.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gtwkwblnpl.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytuypqne.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtsjqkqlgt.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtqrzijagk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gthrjjjdnp.html

Ruby: super
来源：http://dali.316326.xyz/Article/details/gtkgupuitu.html

C#:   base.Greet();
来源：http://dali.tanke756.top/Article/details/gtxfggtmsp.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmknmniku.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnxiangtu.top/Article/details/gtpgsojoht.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtjxxmizke.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gtrgxcjxlr.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gtlmcwekad.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gtywwbelal.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xinyue.icu/Article/details/gthqmoqljg.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gtqxjuyjyv.html

C#:   public static void F() {}
来源：http://dali.sxryk.cn/Article/details/gtnxdrgipa.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gttiznzcao.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.svipenyu.cn/Article/details/gtmnoivgiw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gtdflkzwra.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gtivfjhjic.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gtqjyoruol.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gtvhjbskky.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jyoumei.cn/Article/details/gtzbuxdhvt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dashuyun.cn/Article/details/gtufdsintx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtmkiiqycy.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gtwdevmneh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gtuqfbvdlx.html

PHP:  public / protected / private
来源：http://dali.pycfn.com/Article/details/gttppmhjbb.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gtgggirgll.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtboeuaxmq.html

Java: public / protected / private / 默认包级
来源：http://dali.xylfe.cn/Article/details/gttynajqtg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtppuwqfus.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtzbwdtayx.html

C#:   public / protected / private / internal
来源：http://dali.xuetiantiany.cn/Article/details/gtvzqojmrn.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gtbjogcqbe.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gtgswfyfgi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtjsuonhin.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtvzfscbur.html

TS:   get name(): string { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcjhbuluk.html

Java: public String getName() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtpkgmcdmf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtharvckox.html

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gtzguwoaqz.html

C#:   public string Name { get; set; }
来源：http://dali.nwbrower.top/Article/details/gtdgjajkvt.html

[G12] 对象转字符串
来源：http://dali.tian-w.cn/Article/details/gtvisoykrh.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtckjbomkf.html


<!-- 参考信息 -->