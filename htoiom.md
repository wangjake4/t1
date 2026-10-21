代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gthxscwzvr.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gtjcszwrfl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhongyouzk.top/Article/details/gtqszxshny.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtpnfwpdmz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gtjdnuicmz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlwjwgms.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gtchpdogwv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gtipohctrw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtlgioegye.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.andypj.xyz/Article/details/gtsmzfwvkr.html

[E16] 数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gthkhvkkto.html

Py:   f"{1234567:,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtuuvobzob.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpziiaxyf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtjcidrqew.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtkigsxekg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtavnizvcc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gtrfiprrwt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gtlxnrrzgo.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gtjirgjmiq.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gtfsanmozy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfckgmoy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ybcxt.top/Article/details/gtzlqjaivp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtfdjdnrnt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtmhaepenz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zycfv.cn/Article/details/gtltywsmjz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gtetowrmgq.html

Ruby: s.capitalize
来源：http://dali.birdmap.top/Article/details/gtjjyiryjk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gtbvcnoeyd.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gtkppfemcd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gtazmvfwro.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.svipenyu.cn/Article/details/gtqlcyvywx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtladvshce.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtxanjbfdo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtnzaezwfr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gtgawhknjr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jyoumei.cn/Article/details/gtsixdujnq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gtcqwdzbac.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gtkqficmqe.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtqprrubao.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gtxmcrxdxs.html

JS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtesmpmuce.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtsmjyzwdj.html

Java: s.lines().toList()
来源：http://dali.fengsongda.top/Article/details/gtgdzvhswu.html

Go:   strings.Split(s, "\n")
来源：http://dali.c1oappe.top/Article/details/gtxclviqmw.html

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gtuvagipmn.html

C#:   s.Split('\n')
来源：http://dali.yvedp.cn/Article/details/gtylknaorv.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gteunknhdw.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gttoyuniro.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenjidiqi.icu/Article/details/gttejkvwfs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gtoguflvhi.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gthvtdacju.html

Java: if (s.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gtomwkfdln.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gtacfiruze.html

Ruby: if s.empty?
来源：http://dali.zhengqikj.top/Article/details/gtuyesqwsx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwppadryj.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gtlqomzpht.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gtzuwikcde.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtzfftwylc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtuiamxmbb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtenlnfrdd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtqchdjtdx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenzaomai.com/Article/details/gtwclthchu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtugvykpfm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtswwalctg.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gticihaazw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gtyjmbvpux.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtsnpddjct.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtbvsitwbe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudpbifet.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gtioyiaghu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zdqjudy.top/Article/details/gtiyitrekp.html

Ruby: s.bytesize;  s.length
来源：http://dali.jianghu66.top/Article/details/gtbwiqikhg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gtflphqhnu.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtpplnkpjx.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtzehvfins.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtewgdzxqc.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gtjrnbceiq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.kuanghao11.cn/Article/details/gtcbdtkboo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gthvpewjfv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gtfynruwji.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sweek.top/Article/details/gtrfwgmuei.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtbomlnyfa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gtpuhffecu.html

Ruby: File.read("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtinjoqwdb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbwfzwex.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gtpkppnyqm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gtanflzahu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yangfankeji.com/Article/details/gtkivdzokr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtujsmmwvg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtgajvzrlm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtreqhjnae.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gtsfgejbxg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gtcduwxviq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gtxrahoomb.html

[F03] 写入文件（覆盖）
来源：http://dali.0kj1m.cn/Article/details/gtpfobcote.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gtmbvsgmew.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtzorffewf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gtdgcsnshm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtsctjuqjt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtlhwntjnz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cashguo.top/Article/details/gtxiqjtkgm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dashuyun.cn/Article/details/gtodwojuim.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyxvwpwk.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gtjdiecdmx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtqgdepkse.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gtyvkwlbyt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gtniucrjgw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtmwgxqgmo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gtuqsfergl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtdjglvsfh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenjidiqi.icu/Article/details/gtyjuwjsbd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.feifeiyinyue.top/Article/details/gttcwzpczd.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gthazapmrz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gtpgnnufrp.html

PHP:  file_exists("a.txt");
来源：http://dali.cheryme.top/Article/details/gtmgpmsffy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtxreevfly.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtlwrteoad.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtdclzryix.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenlongwang.top/Article/details/gtyhskaelg.html

Ruby: File.exist?("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtubnuivru.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gtwfncerrv.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtueevawbw.html

Py:   os.remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtvcjvdoxj.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gtrtxezvvs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtotamjibx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtlverapvs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gttutqrhak.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtrlgzzrbs.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtplarjxwc.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmkzwhxe.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gtmjoquwlb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gtiwiixysi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yueranfly.top/Article/details/gtljasznpz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtpephxyme.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtbviwrzwn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gtdpmoxwum.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gthdbromjx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gtllsfuogq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gtwkaakbja.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gtjjjtiejd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gtosayddqj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gtaobquspw.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtcpktwali.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtqebouqpd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtxleidays.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gtlyfqwbxa.html

Ruby: Dir.children("dir")
来源：http://dali.zycfv.cn/Article/details/gtuplczhol.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtcvgukcdv.html

[F09] 获取文件大小
来源：http://dali.yj20258.top/Article/details/gtdyyvtqug.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtmdsxbnlp.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtvchvwyub.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtdeckwixo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtfutghpch.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtgciileye.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoitxxrkq.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtcsxzinkv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gtilbeixgn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gtofhdatby.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtaoxqbxho.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtvqnqnekq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtokgrjpwo.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtnjzoplqx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gtarbtdrwa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtennqlwcg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtqhgqbcuq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gttdxjmcqt.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gtmllvknxx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtvzpkjjfc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gtgnkmpkab.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtpdjuewwj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtpeblxuql.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yueranfly.top/Article/details/gtxsrwheiv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yueranfly.top/Article/details/gtdjfrjbot.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtrkizzqhn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtfkxmhldd.html

[F12] CSV 读写
来源：http://dali.hnxiangtu.top/Article/details/gtgyjapzkd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdsuywka.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gtwwpxyenb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gtldwiphtc.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gtpptcpwey.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.meibo888.top/Article/details/gtcqzyzrct.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gtjuihuteg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gtfzivytak.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gtqwntjoga.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtkouxsdkm.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtqlrjhamf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwrcwoehz.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gtffvfxwob.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gthoubemfj.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtbozmqtnp.html

JS:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtdvlziglj.html

TS:   class User { name: string = ""; }
来源：http://dali.vqdsnc.cn/Article/details/gtecduqlez.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtjnvlgzvc.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gtpnkwbpcf.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gtkjbysznz.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtkelnhzaa.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gtcinduczq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gtrrefwvhl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuxming.cn/Article/details/gtiwirmpsf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtsaoecqqg.html

TS:   constructor(public name: string) {}
来源：http://dali.tian-w.cn/Article/details/gtfoaszouw.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtgpvlxlhb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiiaxaysd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtjvgmeyix.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gtlncaotcb.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gtcifhevnj.html

Py:   self.name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gttacrizge.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtsdxhuwdk.html

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtxkxtszhg.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtvynicqdu.html

Java: private String name;
来源：http://dali.ybcxt.top/Article/details/gtqgzwmybl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gtivzphaiq.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gtpqhrduqn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gtennaaedb.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gtdjpeytkz.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtkjmbhmku.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrilezdf.html

JS:   greet() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtzcfvogxq.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtozqeqzll.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gthwmcjvhy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gteluvbzhi.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gtfsxelbci.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gtgylwrsiy.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gtbxoyrunw.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtnopuhmuo.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkhfrmbz.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtvvutcchu.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtlobdollu.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtiqflbnvl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtsddnpwjj.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gtgbkxnfet.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gtarjzgdpb.html

[G06] 重写方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkiifnwjs.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdiijibjd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcstbebyf.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtbenbpeok.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gthawzsayv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtfkrmwzpt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj202588.top/Article/details/gtugunzgsx.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gtrfvbwvnk.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gtvchycqsi.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gtimrzbdpv.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gtdfazevqk.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gtdsngjvcf.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtxysmtfsf.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtwawbcacv.html

Java: super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtqntwaykf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gtpwsjcood.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gtamulmyfe.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gthvwpaune.html

[G08] 静态方法与属性
来源：http://dali.c1oappe.top/Article/details/gtrocvzvwf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hammf.cn/Article/details/gtnfpdugwo.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpsilckj.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gtprdcssjt.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gtuucyjdkc.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtckjwaltc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtcaqpnryt.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gtnalaqofs.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gthyhrddvj.html

[G09] 接口 / 抽象类
来源：http://dali.dashuyun.cn/Article/details/gtregreltr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gtzjkaqiau.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gtbjmwqwqq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gtsmxubvja.html

TS:   interface Shape { area(): number; }
来源：http://dali.jianghu66.top/Article/details/gtofxmmacp.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gtjpqmxpmi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gtzveyaxjk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gtvwsffebl.html

C#:   interface IShape { double Area(); }
来源：http://dali.jyoumei.cn/Article/details/gtrxuxfeal.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gtttnebjjm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gtdvwuvxnt.html

PHP:  public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtgrktqtpt.html

JS:   #private 字段；其余公开
来源：http://dali.yanxiufei.cn/Article/details/gtjlihakpm.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtpmwfzuvw.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gtycfvarag.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gtwnfkxacc.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtppzhmdnb.html

C#:   public / protected / private / internal
来源：http://dali.ybcxt.top/Article/details/gtbolwmzwt.html

[G11] getter / setter
来源：http://dali.haohaochexian.top/Article/details/gtbmpbjxty.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gtdbhemglf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtgyaussat.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtmfzxsfdj.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gttohptlaa.html

Java: public String getName() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtxpsarqnu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtxuwwsluy.html

Ruby: attr_accessor :name
来源：http://dali.yuanzhike.top/Article/details/gtjhsbtijq.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gtcacdzakn.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gtqzembxkl.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtlhwdggfc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfslfkavu.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtsumyqupz.html

TS:   toString(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtytnchamp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtyhnpvzds.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtupzmswpq.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gtnmsqrhoi.html

C#:   public override string ToString() => Name;
来源：http://dali.cheryme.top/Article/details/gtoscpgvxh.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gtjytiecbb.html

Py:   isinstance(u, User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvxgqibd.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gtawftnvyo.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtumaihcpk.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtdqzitcna.html


<!-- 参考信息 -->