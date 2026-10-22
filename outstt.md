代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gtvvfhrgkm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gtsykdncnq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cashguo.top/Article/details/gtsmvumveu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhengqikj.top/Article/details/gtjivrgdya.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdwaxjjp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gtjqsiynhn.html

[E16] 数字千分位
来源：http://dali.hnqzz.top/Article/details/gtqlvwuxlq.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gtxrvlclkj.html

PHP:  number_format(1234567);
来源：http://dali.316326.xyz/Article/details/gtkyfpuioz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtwdedfnsr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gtvdhrdjkd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gtievhdvui.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gtvundwkur.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gtysniuteh.html

C#:   1234567.ToString("N0")
来源：http://dali.cqqwz.cn/Article/details/gtlayhbejn.html

[E17] 首字母大写
来源：http://dali.zycfv.cn/Article/details/gtikdgrqub.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gtdzcgzfcg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gtknfzvabp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtqmnkjbmf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtiyjiiqjy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gtoccfbbfl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cashguo.top/Article/details/gtjekvmiwd.html

Ruby: s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gtejllzpib.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pengpengdd.cyou/Article/details/gthkzqmaym.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gteeezvldk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenlongwang.top/Article/details/gtbfmaqhlf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sysykeji.top/Article/details/gtykowspre.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtxapaxakx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtrutourma.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtiutnkhld.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtzyxonozc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hysaishi.cn/Article/details/gtqjwlfkny.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gtzizqmhfc.html

[E19] 多行文本按行拆分
来源：http://dali.zhiwuduotai.top/Article/details/gtvuhpuhbo.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuktdxkap.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtwinosvto.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtfkgjwyth.html

TS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtotyafnlf.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gtjuzjftzd.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwajstap.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtriumfewm.html

C#:   s.Split('\n')
来源：http://dali.yueranfly.top/Article/details/gtxdwepvpo.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gtgbkrxopg.html

Py:   if not s:
来源：http://dali.birdmap.top/Article/details/gtwtxcxhxw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuxgmftm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtddgwmxrk.html

TS:   if (s === "") {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoowbnenn.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtmfmzuuyx.html

Go:   if s == "" {}
来源：http://dali.fzhhl.top/Article/details/gtdfuujqis.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gtyozjxokk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gtaoqxlksz.html

[E21] 超长截断加省略号
来源：http://dali.tianlin.xyz/Article/details/gtyopcmgzr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gtbpjcugjx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtfqgjdeec.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjougdgy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtfxcowafg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtqovdhwza.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yongpay.top/Article/details/gtztlhkymm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gthxvggpem.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtniigymqs.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gtwbpprgqb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gtkneggpws.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtfpupldyl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtonshjybj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtzjzftovm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtlqlewfcg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pengpengdd.cyou/Article/details/gtnyaocofj.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtuurkcssx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtvcksbeoa.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtmupavait.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtkjvxdwvx.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcptueuoj.html

[F01] 读取整个文件
来源：http://dali.iojbl.cn/Article/details/gtcxgjdbqc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gtvrqizmjx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtlmdqcqtu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jianghu66.top/Article/details/gtqabwahvt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtszosjynn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtylcojegu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gtpwuuujfc.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtmmijsaxt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtylzjcitn.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gthfrhucyq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aizwys.cn/Article/details/gtcwqmghww.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gttybzvxrn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtnikuvdjy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gtsebhvuxz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtpcsianfk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.meibo888.top/Article/details/gtqyiiaqqp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gtjtkssqfx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gtmsjatvkh.html

[F03] 写入文件（覆盖）
来源：http://dali.yj202588.top/Article/details/gtshjwhemy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtrxbglcns.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtuyxaekee.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtwrtuloea.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtjfyxshoq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gtcvbimxkg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gtbdjjofau.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cucudq.cn/Article/details/gtbqvpzaug.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtsofhkkiv.html

[F04] 追加写入文件
来源：http://dali.sysykeji.top/Article/details/gtpockdmhp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cucudq.cn/Article/details/gtyhwufngu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gtgblrffzx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtrympkmqk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtzunycyju.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdbxrflk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daxiang520.top/Article/details/gtlhwsekrw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gteyubqdvb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaeyivbv.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gtrsbizrzt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhengqikj.top/Article/details/gtjzwghbgd.html

PHP:  file_exists("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtavdwppbp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtlyyimdhb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gttyoytcyf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtzuaumwwc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gthenxwcxp.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gttfqaotgd.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtwyjeksca.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gtixkqjhvg.html

Py:   os.remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtbpzgbnjl.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtgdurnozu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gttcajnpps.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtfvnzflkn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtrwmyarge.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtamxeqzdb.html

Ruby: File.delete("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmaairdbd.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gtixoyrjbi.html

[F07] 创建目录（含多级）
来源：http://dali.birdmap.top/Article/details/gtzkfrnblq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gtgkbkbuyw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gtoszncjiw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtxiqudgzw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtbabvoehz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aizwys.cn/Article/details/gtuzgbdmtv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.smart0.xyz/Article/details/gtoiuynhws.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gtgmxcxnsd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gtuhxxdsln.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gtipummxax.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ivvv.top/Article/details/gtutzdnrvz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gtmocskkse.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtzwnngjtc.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbmvlsuu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gtmkizhajm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gtufhakyve.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrvlffiu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gtqxhacpum.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtfmhiddnw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtzlkoeqmy.html

PHP:  filesize("a.txt");
来源：http://dali.yj202588.top/Article/details/gtrjndivhd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiywktzyg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfbyvqbp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtllztoevu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gtplaggqpt.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtvdsvhbgf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.haohaochexian.top/Article/details/gtbqxlmzef.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gtygmagtlv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtpaxpkjqn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gtszciymba.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtfnaqraeu.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtenykbwvh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gtmhcnpwhk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtcgjfkonp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtcscpkvmq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtxbrfeyia.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gtpbknbief.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtzynahtnw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gttstfmxnh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtkbgcntqh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtgybbhwty.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtrbxnltmx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gtehhntqfx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtqxhjhyzc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.0kj1m.cn/Article/details/gtpxypeuax.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gtcunasong.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gtivkzwnaq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gtaxisvsnl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gtrcurabmx.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gtxaaxfqqb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gtvmokjlvr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gtzazhxyli.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gtfctgavtd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.havefunace.top/Article/details/gteabptpkl.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtrjxgfylv.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gtjfvfmofz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtvgagcknz.html

[G01] 定义类
来源：http://dali.zhongyouzk.top/Article/details/gtztdmkgcx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gtmqrburuv.html

PHP:  class User {}
来源：http://dali.jinqigufen.top/Article/details/gteemnqsvy.html

JS:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gteltndmis.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gtvgalmpsr.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtgsgykkzp.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gtzgnvefhm.html

Ruby: class User; end
来源：http://dali.jqgufenzy.top/Article/details/gtpqqvbhqx.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtiyskgsdw.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gtxmdafvhj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgufenzy.top/Article/details/gtxdxgtvwm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pycfn.com/Article/details/gtjpplcded.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtgflhqnbj.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtihlnpmlv.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtrbgasgap.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gttsemaqmb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gtfiokvswz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gtwxlmabka.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gtvgxmkigr.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtnfveqava.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gtcixtczjo.html

JS:   this.name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtebiapbmq.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gtbifqyhlv.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gtzjvmijov.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gtwojddxsd.html

Ruby: @name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtseygrcrt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gtaedzohld.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gtfstwtrqs.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gthhlmttzd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtqkyekrcw.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpoqablah.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtofzcdaec.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsouamhvs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtcdnclfrl.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gtwbduorba.html

C#:   public string Greet() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtdcvesucc.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmxzstfg.html

Py:   class Admin(User): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gteohohdlu.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtfxxuhgna.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gthnhqtycq.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtfykyadgz.html

Java: class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtitlbyxrs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gtfsydvkso.html

Ruby: class Admin < User; end
来源：http://dali.meibo888.top/Article/details/gtpllvzeuw.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtbzkwskvv.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gtjnliivel.html

Py:   def greet(self): return "admin"
来源：http://dali.gotoacloud.top/Article/details/gtgdwrbwuc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtukezdavv.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtrtearbds.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtvbvukrva.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtqxeujhhr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ybcxt.top/Article/details/gtjktpnbya.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxinkj.top/Article/details/gtmufvplpp.html

C#:   public override string Greet() => "admin";
来源：http://dali.birdmap.top/Article/details/gtyntabajc.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gtldgdgsgy.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzajgyrsf.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjmzwlva.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtcdzbebmh.html

TS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtzzsjtrsf.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtlijzupfx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtvpdlcvll.html

Ruby: super
来源：http://dali.jqgufenzy.top/Article/details/gtqkijshdg.html

C#:   base.Greet();
来源：http://dali.cheryme.top/Article/details/gtlnzolhbp.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gtitewavqr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gtudzcptjr.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzvjovide.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gtwgplkfps.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtwwgkcrhz.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gtymnzbpra.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gttcekjyku.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gtemwvocal.html

C#:   public static void F() {}
来源：http://dali.gzhubu.top/Article/details/gtdomephhu.html

[G09] 接口 / 抽象类
来源：http://dali.fzhhl.top/Article/details/gtsuzbsmgt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gtzcppcsyv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuxming.cn/Article/details/gteeqvwpfj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gtvbteablu.html

TS:   interface Shape { area(): number; }
来源：http://dali.9152youxi.cn/Article/details/gtsxgikbye.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gtgxcagwca.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guowangkeji.top/Article/details/gtoytkastn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.iojbl.cn/Article/details/gtixhjrmtc.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258888.top/Article/details/gtsauzarmo.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gtkjfoymeu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gtbvifcyer.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtogqpomoi.html

JS:   #private 字段；其余公开
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngysgwhi.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtsftabufq.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gtwaeymjjx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gtkgvakpcr.html

Ruby: public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtptpzyyzh.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gtzgnjnebi.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtbshopyga.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gtqwebgchh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtmkkhiyhm.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtonnqcnns.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtnawpusmu.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtucfkebrd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtmrhrbqvh.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gttbenlelq.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gtkqlaiyqm.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtcxmgphmu.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtsnxgfcik.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtwdwynlbh.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtnfioqthy.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtsgdpkwtg.html

Java: @Override public String toString() { return name; }
来源：http://dali.havefunace.top/Article/details/gtkmpzjwyr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gttnznmprg.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gtmhbzjimj.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gtkcmglbdy.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gtaqgifsrs.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gtsisqrlpa.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gtszxaxijc.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtrpvtoygc.html

TS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gtaiacknnq.html

Java: u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtkoogmkqx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gtlrmklcct.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gtemfaptff.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaxzczox.html


<!-- 参考信息 -->