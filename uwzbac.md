代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtujdycoji.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gtivchfmwr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gtgbggiixp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjribnudy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhixingplan.top/Article/details/gtvzmovjdt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gtgoyqjguj.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtwdmmymvj.html

Py:   f"{1234567:,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gteycafvru.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gtagasmjgp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gteewoqxdc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtlfiokyub.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtvepmkuev.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gzhubu.top/Article/details/gtnzadyvui.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gtsidgkrwb.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gttwwurdrc.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gthfglnivl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gtsndqyhga.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtpimxdrex.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gthdexmbfi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtgivzdreq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gtxnzlhvzo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gtvhnwmsrw.html

Ruby: s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gtvpoguouh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangtech.top/Article/details/gtelnihdwn.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gtjriprdou.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.feifeiyinyue.top/Article/details/gtswiqrulo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jyoumei.cn/Article/details/gtdqoaswaw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtbfbncqvg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdhpnxbt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtoshwiaeh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gtrcooevun.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gtpskfznjt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gtucczwczd.html

[E19] 多行文本按行拆分
来源：http://dali.gaohongyu789.top/Article/details/gtrqbtedxw.html

Py:   s.splitlines()
来源：http://dali.yj20258.top/Article/details/gtztboddud.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtacpaddgy.html

JS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtszvyqbsa.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtzcvdekvt.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gtyvrxjxoi.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gtwludiiad.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtunxqtgyn.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpeonzzfn.html

[E20] 判断字符串是否为空
来源：http://dali.ppjwa.cn/Article/details/gtupstrfpw.html

Py:   if not s:
来源：http://dali.ydzc1.top/Article/details/gtvupdzypy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.vqdsnc.cn/Article/details/gtezxsvzcn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gtruembymk.html

TS:   if (s === "") {}
来源：http://dali.shuidangran.top/Article/details/gtryanqvqp.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvkepwhnd.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtulurrvut.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gtiamxekas.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gtcdoeeykm.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtzcbwsrss.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenzaomai.com/Article/details/gttnskknkw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtsmmrwbqu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtytjagfwu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtrkboyaaf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtrukzjxtb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gtaavedexk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtzgfzhivs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtxviukdkn.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gtlmezerzb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jyoumei.cn/Article/details/gtjsluljwj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gthqpsugxn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gttiaqssrq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtdkqxspyn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.316326.xyz/Article/details/gtvrtwrqfo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gtaplhbfxb.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtwzmliujm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuuswmtvm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtepqnepzo.html

F. 文件与目录
来源：http://dali.havefunace.top/Article/details/gtdcnqabgv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtyysgkgno.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gtdzksmttd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuetiantiany.cn/Article/details/gtponxxodm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gteimymdfx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gtwkorldvw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtbvoqdara.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtusptccry.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangtech.top/Article/details/gtlitoilbj.html

Ruby: File.read("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtetnhemzn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtvxryfxat.html

[F02] 逐行读取文件
来源：http://dali.jinqigfzy.top/Article/details/gtlrqknwph.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj202588.top/Article/details/gtegtuulmf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqdoqbcvb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhvwwywo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtehiusave.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gtbccqpqaw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gteuxkecqn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gtsyjtapea.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtdlsakluf.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gtsemnohsd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yvedp.cn/Article/details/gtnsubyeli.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtgaginnmv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtwtrwjlqi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijxtgzkp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gtnpnlegnr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jyoumei.cn/Article/details/gtmwiqfpjc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwdimtvy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gttorhkyty.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gtqxwrfpmx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuanzx.com/Article/details/gtwzjtiynw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gtlkmozcym.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtuusrkhvm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtjhufjluy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gtdnmrrcqa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtwmmnmjzb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyavibvt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gtoirgxetw.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtkquqmzes.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jyoumei.cn/Article/details/gtionvkjuh.html

PHP:  file_exists("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtbweknsiz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtlybcnskx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtgdmhzibz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gthouksbia.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtczxjnhmr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtuleosprh.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtfcozandj.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gtsxrwouly.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtywromkhj.html

PHP:  unlink("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtzemgjbtz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gthhyznfjh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtxnbrbftg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtdowwkvee.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtelayumdp.html

Ruby: File.delete("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtxtsezray.html

C#:   File.Delete("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtshlurncl.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigufen.top/Article/details/gtomndkyie.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtarsyzind.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtyrmukbuf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtzdtmrumu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtuiohrjaj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jyoumei.cn/Article/details/gtplcoxech.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258888.top/Article/details/gtlnjyhxqm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gtxuyiqlkx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gtdliscdnb.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gttmmbvxzk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangshuangyany.cn/Article/details/gtlljavmjd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenlongwang.top/Article/details/gttfqrntiy.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtlemmxhsa.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtoxqhmtew.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtedqomzjd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gtwkfizmtb.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gtxrkybapf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gtzhhbnkdi.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtfevehiip.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtpttosqbf.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtpobibhfn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtdtbguegw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtsyckycph.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gthafwolrs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gtdffprjqt.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtxfjzkivs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.meibo888.top/Article/details/gtgjsksbjs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvruzmef.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtcjueelvf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gtkvageola.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtkumpiuxj.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtbrigoovx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gtovmviibs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtexlfgobv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtgztjoanr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtdzoautvs.html

[F11] 复制与移动文件
来源：http://dali.quarkkingdee.top/Article/details/gtupvggqns.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gttrxcrybd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtlxsmbzwk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtrbyatgel.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtxwgouppu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtvcejacnk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gttiiqayzk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtbwaaeydn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gtlidcxoym.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gtoifpthrw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhiwuduotai.top/Article/details/gtjjmmrimq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gaohongyu789.top/Article/details/gtexbluiop.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gtioztsmjl.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gthnynfoxk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhengqikj.top/Article/details/gtngxnevcq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gthqmwbend.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gteaohorwg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gtxthjhirq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtajxswtcu.html

G. 面向对象
来源：http://dali.zdqjudy.top/Article/details/gtydditnra.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjdkaynsb.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gtjstxwtql.html

Py:   class User: pass
来源：http://dali.yuanzhike.top/Article/details/gtdtndwmxb.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gtncusmhfv.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtfemrmgld.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gtwdsivofb.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gtypjxwyoq.html

Go:   type User struct { Name string }
来源：http://dali.jinqigufen.top/Article/details/gtuhpyaqru.html

Ruby: class User; end
来源：http://dali.cqqwz.cn/Article/details/gttmodrexv.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gthivaynyb.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtftuvtsgl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gtolhylote.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtebwedrak.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtqytmfwbw.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gtertvoisy.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtkgzprmze.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gtirvhdmdv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gtzgouurxe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonfftthz.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gtrfwpheue.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxsgdhae.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gtdenykjvx.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gtfoatjcsu.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gttnaxbvdr.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbwphfrt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gtycqrzjzx.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gtmatdcltu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gtjgzvhurs.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gtahzgfnxx.html

Py:   def greet(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtfkkptubq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gttyedhnnr.html

JS:   greet() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtidtblpdu.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtvezfjrjg.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtdrfwnute.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtneleeifu.html

Ruby: def greet; @name; end
来源：http://dali.smart0.xyz/Article/details/gtzncvifva.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtoejulqex.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtdjiktolf.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gtpictrbgb.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtyubaivzh.html

JS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtatylrmfi.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtwpfhetcb.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtiqxmbzvw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gtuefjtblr.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtbphjzlhv.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtlnhtxmcv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gtymqmgtgs.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gtdgxojlxy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtuxnlactk.html

JS:   greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtpfrikaqp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtgsoarezb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtlwyrqvvz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqocraqeo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqcjmqvq.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gtqvxnjiqo.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gtbvytqxcp.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gtcvjivwtm.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gtoghvlhtl.html

JS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gttlloslup.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtsqlwdvuy.html

Java: super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtrnaoqymz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gtakbhvdrj.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gtrzdmcmqi.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gtroxxmkng.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gtacujosxf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbdiylpt.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gtevmnncxv.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttacwanvc.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtihypoiru.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gtpelzwcxo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtvcfelwoy.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gtdrnrqwxh.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gtpynwjnei.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gtawoatwlu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gtyydhrobn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gtzeysfyfk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtzlzasboe.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtevaiybsr.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtakppwojv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gtyambglom.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yonumen.top/Article/details/gtmztmoopk.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtcuxcsepv.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gtweaftadf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gtznulmkwb.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtzuencuwi.html

JS:   #private 字段；其余公开
来源：http://dali.jqgfzy.top/Article/details/gttntwyhti.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtaaoqlsyw.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gtepsjlfqh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgfzy.top/Article/details/gtsdjmzbwg.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gteofvkoiu.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gtvdqwctbl.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gtokeiqpav.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtrnlqhklh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtcxxmzcie.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtampcnrbc.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtagjvixoa.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtlwfhhzjk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gthuiipfex.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gtqdsdmxfn.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gtslilxvfe.html

[G12] 对象转字符串
来源：http://dali.smart0.xyz/Article/details/gtfntdgepf.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtuzoafcsi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtsxuneqwv.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtzogjkqcn.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtivsxylab.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtkigrdsej.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtucwjbutq.html

Ruby: def to_s; @name; end
来源：http://dali.cheryme.top/Article/details/gtcblslvys.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gthwkcghcu.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gtiuowapyt.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gtozhlhpkw.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtffyhyjya.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtnjnhanvl.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtincjeqju.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gttunbwaie.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gtqrqruisg.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqwuzymv.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gthpvkzwkq.html


<!-- 参考信息 -->