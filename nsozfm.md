代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.cheryme.top/Article/details/gtbcqeriep.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.snrcjt.cn/Article/details/gtbtiigdcj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gttrkgqqni.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gthmraeadn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nwbrower.top/Article/details/gtcuvdnzwf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtyktlconk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuanzhike.top/Article/details/gtgojoaubv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tian-w.cn/Article/details/gtemieitcj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aizwys.cn/Article/details/gtqlvjowmw.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gtcgpqogxx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shzxlz.cn/Article/details/gtklchgves.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuxming.cn/Article/details/gtghiragcm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuanzx.com/Article/details/gtiqarflnv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gtxyclkzop.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gtevkrqqzp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtfhuqhnhi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.bjfxy.top/Article/details/gtoabsivex.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrlwgtno.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtgfdtqijv.html

Py:   f"{1234567:,}"
来源：http://dali.gzhubu.top/Article/details/gtuvxcoaqp.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gtcyfetbgn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtoskpvkut.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtbpruxage.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gthggpzwub.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gtzklylryx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hysaishi.cn/Article/details/gtyywnajgw.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gtlfnqormz.html

[E17] 首字母大写
来源：http://dali.jinqigufen.top/Article/details/gtkjsfxqju.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgfzy.top/Article/details/gtnhjjiild.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtswgkdgdo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtrpztfcvu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtielwbagn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gtdidfdugj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.meibo888.top/Article/details/gtmxgjbjpq.html

Ruby: s.capitalize
来源：http://dali.daxiang520.top/Article/details/gtjefwsjyu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.snrcjt.cn/Article/details/gtzqsrwwec.html

[E18] 模板占位符替换
来源：http://dali.feifeiyinyue.top/Article/details/gtdamcwnqa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nwbrower.top/Article/details/gtkaoomkvo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gtzorqzkqh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gteiwwzlyq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtgytjvluv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtddsttuzn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtsxfjmbes.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtmnchgfye.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuetiantiany.cn/Article/details/gtkcrrafcv.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gtqybalmir.html

Py:   s.splitlines()
来源：http://dali.yongpay.top/Article/details/gtumjpsafx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtarcybysn.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gtihstcffu.html

TS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtscjyywww.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gtzulualwc.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gteuqkddyl.html

Ruby: s.lines
来源：http://dali.zdqjudy.top/Article/details/gtysrmwqzr.html

C#:   s.Split('\n')
来源：http://dali.fzhhl.top/Article/details/gtztyhyzad.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gtzgolafgk.html

Py:   if not s:
来源：http://dali.bjfxy.top/Article/details/gtypglseie.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gtswkdfida.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gtwurfpjxk.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gttjsuoydi.html

Java: if (s.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gtwpogbakf.html

Go:   if s == "" {}
来源：http://dali.jyoumei.cn/Article/details/gtfohbfmbu.html

Ruby: if s.empty?
来源：http://dali.ybcxt.top/Article/details/gtpnnjkgfq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtltzgqcuj.html

[E21] 超长截断加省略号
来源：http://dali.sufxvd.cn/Article/details/gthzpzacja.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.0kj1m.cn/Article/details/gtjlmkgxwy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gttdnyuegu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtdigbcgkf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtbisbcytv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtzdvdvjkl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.vqdsnc.cn/Article/details/gtqiqptycz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtbjmfxwcb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sweek.top/Article/details/gtfljwhenr.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gtlzhvxnsl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbphmelax.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtlwpvdwvi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtlyjduxkh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtkuqqqtfm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gtaenffuzq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gtwhwmyxyv.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gtiiyuzmhn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gtsmixevdm.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtezofpcbd.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gtderianss.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtdcpaxqbz.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gtvdfgejpq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cdnleiting.top/Article/details/gtcudfjwbb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtlhqkyhhp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gteugkaavk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtinqlhkln.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtrosvycmo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yvedp.cn/Article/details/gtvblqmsho.html

Ruby: File.read("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtpyqsmups.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtlvmtwhpo.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsnxdeff.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xylfe.cn/Article/details/gtiolhxcqd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guannengcc.top/Article/details/gttgmwuycu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gttepaeghg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtxhcmdpmu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtgsgwnxbl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnxiangtu.top/Article/details/gtncivzdsd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjaepsrl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gtpyrncoej.html

[F03] 写入文件（覆盖）
来源：http://dali.tianlin.xyz/Article/details/gtgcthhinm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ydzc1.top/Article/details/gtuthbuuoj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gtwdvlnfak.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtiubnvmmv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtyouxxxzm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtbrgjvqjb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gtixdrehjd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cdnleiting.top/Article/details/gtpzltzhel.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtlzvpacgd.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gttdqytzdw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gtifpwukzj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gtufgkhzmx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhuoxnhd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtpegluglc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gtsmjedilm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258888.top/Article/details/gtukhhhpok.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gtemsomupo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gtjqfvywlj.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gtpiavbxlx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gtzjzpyuzf.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gtokokecqx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtyqlmpjhy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqsicbhcu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtawmdzbls.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gtgfnmvrpz.html

Ruby: File.exist?("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtdcyyggkz.html

C#:   File.Exists("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtyopmxpzm.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gtdnikuqjc.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtedxaoyli.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtvymqykdg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtyygiktmd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtkzmlmjkt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtyseqqage.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtozpcnzvs.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtbhkltksv.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtfdmjrbwa.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gtjozpnwxi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gtiasgnttt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tanke756.top/Article/details/gtsguexwkq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtgahaoimt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtlsxfdbny.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gtkdthgppz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigfzy.top/Article/details/gtgjatwbty.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gtpjnryozu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gtrymietmk.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtvuwsmkhs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gtjesxypha.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gtdyhbrjmf.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtprafdmtl.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtpvxthbcw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtkrmkfftb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gtjgcykzyb.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gthzineuzj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.vqdsnc.cn/Article/details/gthhdexqpz.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gtulyujcdd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtpwukljkz.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258.top/Article/details/gthktxcttn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtyqaxvnpq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtvpjpkavk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtxmrjmytz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sysykeji.top/Article/details/gtjdmkqcvt.html

Ruby: File.size("a.txt")
来源：http://dali.316326.xyz/Article/details/gtvcfknajc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtzgmjaoum.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ppjwa.cn/Article/details/gtdjpeizyq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtxpfjmcvs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gtscfqmsle.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtyayvzqsb.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtthfqmbye.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gtwskcwifx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtdhqziomo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpjmrwev.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtgeafdrep.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuhcdeef.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtermqqvpn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hammf.cn/Article/details/gtohprsumf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtkilfniwb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtzlqywvql.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtjrkexqkg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gtaqoiadqu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtugbjcota.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.kuanghao11.cn/Article/details/gtokqvqmqp.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gtsfskogkh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gtnuaonhqe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gtjtnmkcmz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtuwgmph.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gtqkhsalce.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gtvbibnogf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shzxlz.cn/Article/details/gtpfnuplwt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gtymrahqiw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gthbhurxhg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtofsjgkdh.html

G. 面向对象
来源：http://dali.xuetiantiany.cn/Article/details/gtlrwatopa.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmlfcpsgl.html

[G01] 定义类
来源：http://dali.daria6918.cn/Article/details/gtxbffkros.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gtxyahxrle.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gtyeniziam.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtosveetfx.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gtwqcmbkdy.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gtshwhbjsv.html

Go:   type User struct { Name string }
来源：http://dali.hywenlv.cn/Article/details/gtehbggyld.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gtuefekgxg.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtvkpvcwee.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtujvscjlr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gtmhqinsnh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncdwtdjg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtezzainol.html

TS:   constructor(public name: string) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjdcpzwkx.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtkofkdbqd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gtzenivqvo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtaqwwiibl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.mhx1999.top/Article/details/gtooszzwcg.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtvqkujmcq.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gtnprvphlc.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gtbnuhkihf.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtfygqcgsf.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gtezrttzpo.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gtqouyyqkh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtyrnwmprt.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtaemktkug.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.svipenyu.cn/Article/details/gtxervqbpd.html

[G04] 定义方法
来源：http://dali.jlsjyb.cn/Article/details/gtwtwocuug.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gttsgqixmh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtypsfpzea.html

JS:   greet() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtjxughgij.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkqtceqwv.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtudrzepig.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtvtpkqehb.html

Ruby: def greet; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtoanrmjeb.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtymalzydn.html

[G05] 继承
来源：http://dali.wangshuangyany.cn/Article/details/gtrqalpvvg.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gtevshyini.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtcsjlvagu.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtktsmkblr.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtmhuwvfqo.html

Java: class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gteysetmen.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gtvkhbcyja.html

Ruby: class Admin < User; end
来源：http://dali.gzhubu.top/Article/details/gtrcpxpppt.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gtjbkmqufs.html

[G06] 重写方法
来源：http://dali.cashguo.top/Article/details/gteiazhoxm.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gtjzqvdxbg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtnqllxeua.html

JS:   greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtesgpvlni.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtsxmloztl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gthlkhgjtw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gtvarqburx.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gtwoygzaug.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gtksgwnbkt.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gtmpyrluux.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gtrwysegug.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gttzjcljay.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtkllcymwz.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtxomyrbrv.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxufdoqm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daxiang520.top/Article/details/gtreqsfqwq.html

Ruby: super
来源：http://dali.cheryme.top/Article/details/gtodckfmdp.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gthgcseiib.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gtfdmfnhba.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gtjaymyjck.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gtyhpnbwfd.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gtucsddaxb.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gtqkvhmjgi.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gtcvthljha.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.0kj1m.cn/Article/details/gtfmdwgqaq.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gtmadtyvmw.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gtuyynfyon.html

[G09] 接口 / 抽象类
来源：http://dali.cdnleiting.top/Article/details/gtmkuvwztn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gtqyaksqph.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gtrjblvuzm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.iojbl.cn/Article/details/gtafoxyxqe.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gtfgxofmim.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gtwpypiyrg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenzaomai.com/Article/details/gtedgerrap.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenjidiqi.icu/Article/details/gtiinfkons.html

C#:   interface IShape { double Area(); }
来源：http://dali.guowangkeji.top/Article/details/gtdknmzyqv.html

[G10] 访问控制
来源：http://dali.0kj1m.cn/Article/details/gtzwneznlh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gtoemmnsnz.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplikzsss.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtztljwjnf.html

TS:   public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtocflinqj.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gtpltcprus.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pengpengdd.cyou/Article/details/gthsxyjfbk.html

Ruby: public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtvpgcsthp.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxkgdohb.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gtwdcskobj.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gtpbnnjcfo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtxcdwuhge.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtylppwttn.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnvtfxbwd.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtpxysyvdw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtzfkyeyky.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gtnsvkewbk.html

C#:   public string Name { get; set; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjlzatls.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gtgpksssgl.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtaosllmyv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtvtcbpjfg.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtenqnwcfb.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtzvgftkur.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtjhewaxtt.html


<!-- 参考信息 -->