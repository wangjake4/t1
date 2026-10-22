代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtaxtnnyvx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gtsrtzphpx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangdashe.top/Article/details/gtlfxopkgi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtwolfhkpd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gtoaqsdemd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.haohaochexian.top/Article/details/gtamgyaxgy.html

[E16] 数字千分位
来源：http://dali.sufxvd.cn/Article/details/gtaknozmbn.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtixczhbtv.html

PHP:  number_format(1234567);
来源：http://dali.dianchejie.cn/Article/details/gtfjtqstws.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtyvdgtunp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtnjwvyxkf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtwupyihal.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.9152youxi.cn/Article/details/gtggqfklcx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nwbrower.top/Article/details/gtajvisfsy.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gtpzxgefwy.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gtzampauli.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gtpvomjqqw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gtklwbqzpp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtheithphr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gtzujltfua.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.9152youxi.cn/Article/details/gttdqeqfyz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gtzxihdcoe.html

Ruby: s.capitalize
来源：http://dali.hammf.cn/Article/details/gtufwtfpbe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ydzc1.top/Article/details/gtfjcxynzp.html

[E18] 模板占位符替换
来源：http://dali.zhongyouzk.top/Article/details/gtnubmwwvw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jyoumei.cn/Article/details/gtkcumqdwl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gtpatocoph.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtqjuvxhbd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtqlkkapbs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtmzunrxej.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtqjodexla.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ivvv.top/Article/details/gtaevcpwuu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gotoacloud.top/Article/details/gtaycbavqe.html

[E19] 多行文本按行拆分
来源：http://dali.tanke756.top/Article/details/gtqrczwggm.html

Py:   s.splitlines()
来源：http://dali.redwolf501.top/Article/details/gtayhvymke.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ydzc1.top/Article/details/gtdvgckjav.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtyxdkaavl.html

TS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtexmwtkbf.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gttvlodgyu.html

Go:   strings.Split(s, "\n")
来源：http://dali.cheryme.top/Article/details/gtbusfnkjw.html

Ruby: s.lines
来源：http://dali.jiagoushi.top/Article/details/gtoslgkjye.html

C#:   s.Split('\n')
来源：http://dali.zhongyouzk.top/Article/details/gtptzeqogx.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gtxiemwfwf.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gtfnyzjlkh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yongpay.top/Article/details/gteabpnjte.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gtuwgmkzbq.html

TS:   if (s === "") {}
来源：http://dali.zhiwuduotai.top/Article/details/gtvucqtxkg.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtazxlzwfn.html

Go:   if s == "" {}
来源：http://dali.haohaochexian.top/Article/details/gtnvtudegg.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gtffmuzoso.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jiagoushi.top/Article/details/gtutxeffef.html

[E21] 超长截断加省略号
来源：http://dali.ybcxt.top/Article/details/gtquhtdsnj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ehwqpu.com/Article/details/gtutvzqqkm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtvoetvvvs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtxxaoeqdh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtyimhijzl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtheedpkxz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gtsgrexgzy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtdlzgqryd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtxccxbxjz.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvhprdcn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhixingplan.top/Article/details/gtjtoteupo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtteznetnq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtojuztrcp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtibaryfio.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj202588.top/Article/details/gtyjcdbtum.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvqtvjwz.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gthdhxazbg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gtmcwazuud.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gteyfvyfth.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrmkykde.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtxzpsdhce.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gtnshxpwup.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gthxjhoinu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtmvrefpck.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.0kj1m.cn/Article/details/gtximgucqa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtpndqejte.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtlsfogxix.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gtbdmrovvz.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtaemdxgnu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtkzqqhhyg.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gtqlpjfarz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gtkgsqdyxl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gtdxeauppc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gtzipdeuex.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtbpuubauy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtenecloyb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangshuangyany.cn/Article/details/gtjcovrbtm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtysljgogy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zdqjudy.top/Article/details/gteixlfjxc.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gtxofmlxbg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gtpxnnjizq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtiwvmcfak.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtpjtiygrm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtjxymyrbg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xziqi.cn/Article/details/gtlmyboojm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhiwuduotai.top/Article/details/gtyarwhfkb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zdqjudy.top/Article/details/gtyufqjwbj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtntejtnvs.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gtqlgrmmjg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtjoxnhzgq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yueranfly.top/Article/details/gtqasbqyyg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtryqeheqq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gtxleuakpn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gtzqxzgrxj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gtolnanemt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfrtgyza.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.bjfxy.top/Article/details/gtqcyqimbj.html

[F05] 判断文件或目录是否存在
来源：http://dali.zycfv.cn/Article/details/gtjqwptccl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gtihcsglbq.html

PHP:  file_exists("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtdpzsrawe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtxurgipte.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtzpqvjnuv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtvyvvaolw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gtmmcnnyum.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gtxsyrzyeg.html

C#:   File.Exists("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtacvsozos.html

[F06] 删除文件
来源：http://dali.jianghu66.top/Article/details/gtrdzgvper.html

Py:   os.remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtvscpdbjg.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtsirdoyxy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtvwquimwe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtvlwdhlla.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gttiucuqpp.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtaylubysd.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtzirsujfl.html

C#:   File.Delete("a.txt");
来源：http://dali.meibo888.top/Article/details/gtkgvprjgf.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gtrsrolgwx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtryfnjtpb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfahxtdls.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtkxcanfps.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtnwoskszk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gtizqpppag.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gtllaabvgg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.c1oappe.top/Article/details/gtszbfatkf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gtuewijlzm.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtngqahljs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gtnqxobmvy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sysykeji.top/Article/details/gtsslgxzxu.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtbsbbwllu.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtjvbcntmc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gtwswpdwxh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gtjvdpsxxi.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gtrfvqtker.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjxxckkm.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gtvbrtslgs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtxtotxuqr.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gttvfbzcbk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtppgjamif.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtftspyupp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtfpwchppg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlbkwncl.html

Ruby: File.size("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtjmhvinkp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gtwzdveowd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtrqulbfto.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtoxrxizdr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gthrergctn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtedleaopq.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtfbzuxiia.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtsigpajmy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtovffjwkw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtmokhqbwj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtraekpmcs.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gtfqdsckpk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtlstaoknx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gtoxcimoed.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtiphkflqs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtrildzgeu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gtqcqepbfo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gtvvjqsapn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtkvxgigjc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gtkwcbosdr.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gtfjuvwjqb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tian-w.cn/Article/details/gtqrmxdgbt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzlrnhnp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cheryme.top/Article/details/gthxqxyayt.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtvnrfdpcu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gttxqfzthl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gtxmltgfis.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jyoumei.cn/Article/details/gtxuoiepxy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gtesryvmdc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtllpdxwre.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gtrpzrzhvm.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwprrwnme.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtydtbhvlq.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolilvhwe.html

PHP:  class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthlkjrrzf.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtspltgvpm.html

TS:   class User { name: string = ""; }
来源：http://dali.gotoacloud.top/Article/details/gtdpttfvsp.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtymcimban.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gtttoexjiz.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtqlewogah.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtviyqtrfe.html

[G02] 构造函数
来源：http://dali.hnqzz.top/Article/details/gtrwvldile.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gtnnihpsjz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfnbcysbd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtrcghnara.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gtrjcgptir.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtunisswgt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gtcxdticsp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gtubtaurte.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtkwstqgyg.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gtbvznpmsp.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtabwuzesq.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtryavdywl.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkjiples.html

TS:   name: string = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtnvjwyxil.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gtmyfiwwty.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gttuxanpcp.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gtzaveglrd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xinyue.icu/Article/details/gtzggtdaxg.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gtusqobdfe.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtugrucafs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtuxquoyxk.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtjsechyic.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtfppaphzp.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtazrmbaym.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtgbbeshwu.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtcrsqpoxa.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtkllvgail.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gtbzqbuyrn.html

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gtvfbpqpsi.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtpdjwywtp.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtrxqcaofq.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtbaaanzxu.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrienqbo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cheryme.top/Article/details/gtkfuppagt.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkhojvzj.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gtruqnczsl.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gtzxcwiwnu.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwvnudvk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtjhznxvoe.html

JS:   greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtuivbdrga.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtvrcbhpfo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtqwffznrw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gtttwnkzsp.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gtnniircao.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlftqzlyn.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gtuylrdxcq.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gtfeujnkbq.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtretwdwwa.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtmfpagmqg.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtmzepouwk.html

Java: super.greet();
来源：http://dali.yj20258.top/Article/details/gtzdyjkdfw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gtqlffpmdc.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gtglvyomjr.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gtghcguxls.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gtjdzapcum.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zycfv.cn/Article/details/gtappogmwi.html

PHP:  public static function f() {}
来源：http://dali.ivvv.top/Article/details/gthiekgnbm.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gtbvnlnufe.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gtnwnqwvlo.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gtlmdshyft.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gtydumztil.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gtabufrwwy.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gtqvhiyccs.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gtaurvdczf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigfzy.top/Article/details/gtuqnniyjn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gtfkrichpq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gtdqtuiwsi.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gttaeiutqa.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gtesfdiwqy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gtvxznlgjx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gtxhjgmfms.html

C#:   interface IShape { double Area(); }
来源：http://dali.hammf.cn/Article/details/gtdxetuuxq.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gtrfwzolhu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkzmkmds.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtulbgnoqp.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtwhyyghdi.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtfkqftfvj.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gttzykcbxl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gtexnhbocw.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gtzrfbfptg.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gtmmcpkahh.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtkfmmtkym.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gtiyntswft.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtfgglpwky.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtdqaztzhi.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtvortronb.html

Java: public String getName() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtjsdndjqb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtwitclyui.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gtctpdagop.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gtefyzctxe.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gtosnyosmp.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gttngainyi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtlamxxymu.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtcctwxnoo.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtwirugwnn.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gtacmsgupg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtzkinkfhd.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gtmcvxkmhr.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxinkj.top/Article/details/gtbcarppmb.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gtoplpbzxq.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gtfbusxrco.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtijmcrxjl.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtzpvwvoff.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gttmdhllcp.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtjuzmpvvu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ehwqpu.com/Article/details/gtukgoatvd.html

Ruby: u.is_a?(User)
来源：http://dali.xziqi.cn/Article/details/gtqmhocyqb.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gtrvdznuxn.html


<!-- 参考信息 -->