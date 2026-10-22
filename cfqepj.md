代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gtjyzgzobp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxinkj.top/Article/details/gttslyzpvx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.iojbl.cn/Article/details/gtdvkeukzz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gtcorxcbbn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gtxtleqcrv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ivvv.top/Article/details/gtiktgwumd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbzuosdb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cheryme.top/Article/details/gtocvcxjxv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdyycajt.html

[E15] HTML 转义 / 反转义
来源：http://dali.zdqjudy.top/Article/details/gtlalvptlw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cheryme.top/Article/details/gtqrkqxssi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pycfn.com/Article/details/gtbedpjjxn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhongyouzk.top/Article/details/gtipqiwxwy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.svipenyu.cn/Article/details/gtztqsicfq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gtumcdngwz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gogol.net.cn/Article/details/gtsmetmcmj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jlsjyb.cn/Article/details/gtzptzqtbk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gtgtufhfvg.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gtfadtsrph.html

Py:   f"{1234567:,}"
来源：http://dali.wangdashe.top/Article/details/gtpglzpknz.html

PHP:  number_format(1234567);
来源：http://dali.pengpengdd.cyou/Article/details/gtqdhphfxk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtxpjancrh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcblixir.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gtupkvhhtk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pengpengdd.cyou/Article/details/gtnkeoqcjo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.quarkkingdee.top/Article/details/gttqhatvax.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtuwcqgopr.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gtezlinvhg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gtiplrqkrp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtifrhacxd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtsfppgutn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtregteyfu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gtcsknbafh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xziqi.cn/Article/details/gtrtscwrvj.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gtditwsttu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tianlin.xyz/Article/details/gtyclkcscl.html

[E18] 模板占位符替换
来源：http://dali.tanke756.top/Article/details/gthppevgzi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigufen.top/Article/details/gtiwkpksyr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gtysbystyb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtplhoppap.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtpkklgmxp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtbeosabev.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gtkksdbwwb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gthdnwexui.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxxndfeg.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gtabtpwcfs.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcijcvcfe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xinyue.icu/Article/details/gtorwupciy.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtafjubuvd.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtksohmfvq.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gtqesyhxjm.html

Go:   strings.Split(s, "\n")
来源：http://dali.jyoumei.cn/Article/details/gtcjkewsbg.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gtvfoyybzo.html

C#:   s.Split('\n')
来源：http://dali.svipenyu.cn/Article/details/gtezukzmyx.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gteogtekzq.html

Py:   if not s:
来源：http://dali.svipenyu.cn/Article/details/gtagqpgmuy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiykivydb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gthszsoncr.html

TS:   if (s === "") {}
来源：http://dali.dashuyun.cn/Article/details/gtoqiqbuil.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtlswujkeh.html

Go:   if s == "" {}
来源：http://dali.aibaodan.cn/Article/details/gtgbzpfefa.html

Ruby: if s.empty?
来源：http://dali.hfpthk.cn/Article/details/gtuaytscqv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gttdjztjme.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gtssfvmmba.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yanxiufei.cn/Article/details/gtdncwmglb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtuxqmcwpm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtixmuofkz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtpeaabxkd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtrulmiejc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gtynzsakjw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtkjxqxhpl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtnvobqsru.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gtkhvtdbdc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gtctvkuaop.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtbeumpwcy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtfssiqdsp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtxicphgfw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gtbppokzrq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gteiykyjjf.html

Ruby: s.bytesize;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtcgsqtwji.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gthfbvcfkh.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtihoyioxw.html

F. 文件与目录
来源：http://dali.xuanzx.com/Article/details/gthfvcsrnt.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtiyikqtbb.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gtselcskxe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.birdmap.top/Article/details/gttbkikbds.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtmsnmuqlw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gttuvptgaw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtpvirraov.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtzqpfulla.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gtufqldbpm.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtddfsqodk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbkfygmb.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gtzcysvexl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gtzuodwjmh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jlsjyb.cn/Article/details/gtytvyzriy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtvuldasib.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtxejlnlxl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtmlltifxe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.andypj.xyz/Article/details/gtxgfplkob.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gtfhghccud.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sweek.top/Article/details/gtqqbfkmfc.html

[F03] 写入文件（覆盖）
来源：http://dali.cashguo.top/Article/details/gtixdjcxrh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gthrgyuycr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtokvprqpa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtohrmfbxn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtxoxhjcsd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gtwiirvbwm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gtmgmbzltf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtjflslyda.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gtpofyfwwg.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gtpzuuznqe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtlhrexhaz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhengqikj.top/Article/details/gtvdzdackq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtlsvnebib.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gtfhhbpftw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daria6918.cn/Article/details/gtdaflowis.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gtzlvktzcg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gtxucyrijk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtkqyjqarc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtlitvwbzt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gtojndkdgp.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtfwcxkfhn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncvjlaap.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtzrhcjvcc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtymnjfkig.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gtlmfwjjqx.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtaojymlcl.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtcjzqwzay.html

[F06] 删除文件
来源：http://dali.yangfankeji.com/Article/details/gttoalrona.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirsaakji.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtdntmnhmx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtofvfjita.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtkeklgmpe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtuzoidwzp.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyulkihrz.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtjxhwqqhi.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gttmckewsi.html

[F07] 创建目录（含多级）
来源：http://dali.dianchejie.cn/Article/details/gtywjjshif.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtgnyhikvn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.c1oappe.top/Article/details/gtoakswhwg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxejlghe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gtzwvepadh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gtnmtuybns.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtreitlnin.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shuidangran.top/Article/details/gtzirgbkwm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtkqtkwgoe.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtbprxnzvg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkltpeibu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gtpjntsrzl.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtpdudibhd.html

TS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtugpovqqq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtagscecnk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dianchejie.cn/Article/details/gtlybupqvp.html

Ruby: Dir.children("dir")
来源：http://dali.ppjwa.cn/Article/details/gtvbhjpeqj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gtqdohcrko.html

[F09] 获取文件大小
来源：http://dali.c1oappe.top/Article/details/gtijkrztvd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtinxjxryy.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258.top/Article/details/gtqlncsadm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtgpfsntwi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtrdojuiax.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtebqriuig.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtducbpwcv.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtmplzrjhy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtauymfwmd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gtkysyubmy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtepavtaoq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yongpay.top/Article/details/gtojnnyyxo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtxzpwbsef.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtppsyomxd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gtlxkfnqqh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtapywmwwj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtwqjzulou.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtzhpnjxmt.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gtfegeiyeg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtbcfyhhgc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtbhtmlvmo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtrequbmvd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtrugystmi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtwzuovpqs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gticvizsfo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtnbuxunbb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gtslqfmzbi.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gtenlgvnac.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fengsongda.top/Article/details/gtjouidfao.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.kuanghao11.cn/Article/details/gtcfqqprtv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhixingplan.top/Article/details/gtdknxqjya.html

TS:   // 同上
来源：http://dali.zhongyouzk.top/Article/details/gtyrmjgexo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ehwqpu.com/Article/details/gttgihmxyi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gthyeljyhu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gtksjtomrc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gtqbwhfgxu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtgahgbtht.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gtfaafeplx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdszckyrw.html

[G01] 定义类
来源：http://dali.shuidangran.top/Article/details/gtufsxsdzg.html

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynmdhzdd.html

PHP:  class User {}
来源：http://dali.xylfe.cn/Article/details/gteupwvkfv.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtmfqduscu.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gtzidgdfur.html

Java: class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtbdoikrze.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gtqtdidpxn.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gtpcdwsdgs.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtlszfogsu.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtudcrqqyn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.haohaochexian.top/Article/details/gtzmuxazee.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gtikykgudo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtcfwrcqvf.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gtravjskuw.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtzzabzxor.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenlongwang.top/Article/details/gtxlycrvol.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtinmswmaq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtiqmqwspv.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gtzruqbgdu.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtfqmtxzhe.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gthgededbg.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtsngqzdme.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gtgsvbjurf.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gtxokgjdgi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gtzqovosmw.html

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gtdzwprnpp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gzhubu.top/Article/details/gtbtnjhlci.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gtcunzqjgf.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtfuovbrau.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtwbxjucyk.html

JS:   greet() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtbgicvrlf.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtamgsgxmb.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gteqygsfhs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtfloeqiuo.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gtegsthjid.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtylozorxb.html

[G05] 继承
来源：http://dali.smart0.xyz/Article/details/gtwobiwgtu.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gtlmyvmfmu.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtvqqrpjro.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtpjvhwaix.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtuookbkeu.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtcoszpzkq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtpzxgampt.html

Ruby: class Admin < User; end
来源：http://dali.sufxvd.cn/Article/details/gtedidjgvg.html

C#:   class Admin : User {}
来源：http://dali.yonumen.top/Article/details/gtkcdeouht.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemoadatp.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gtcwoxboit.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtzeyqykty.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtnrawhsyr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtacljfvrw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gthupbikzh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dianchejie.cn/Article/details/gtqhiuqqaq.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gtyrugwtrx.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gtxensayic.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdinghya.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gtestsfcer.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhedrvmw.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtzrprcmhx.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtymszfaox.html

Java: super.greet();
来源：http://dali.tian-w.cn/Article/details/gtsbhncrqe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sufxvd.cn/Article/details/gtjvsmkoyf.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gtvnxozswd.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gtvyimgewl.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbucueag.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guowangkeji.top/Article/details/gtjoirvwka.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtbwlnarfh.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gtccmttkqr.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gtztrbkntm.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gtkwmqkehs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yvedp.cn/Article/details/gtvstznfsn.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gtztljnhlw.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtleqsuasy.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gtdtrihcom.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gtzpbhoker.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dashuyun.cn/Article/details/gtrmccuoih.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gtdlxmomzk.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnxiangtu.top/Article/details/gtslacqqgu.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtygykaepz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tianlin.xyz/Article/details/gtdubfnvat.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfzkhcil.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gtibvraidi.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtwaannfyg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gtfscekdnc.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtbzwrjjjc.html

JS:   #private 字段；其余公开
来源：http://dali.zdqjudy.top/Article/details/gtpttunmay.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtcfxloefc.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gtfalpuqxf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gtfgbknlem.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtkewkquqh.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gtuxfkxkdg.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gthayvtldx.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gtvgipbcju.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtectgzkwm.html

JS:   get name() { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtdoamwfqk.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtdzakdwxo.html

Java: public String getName() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtebpuyhie.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtqncgadwr.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gtsgknxtph.html

C#:   public string Name { get; set; }
来源：http://dali.c1oappe.top/Article/details/gtvntihjcg.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gtfsoqoaum.html

Py:   def __str__(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtzoxvqeoy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtvlshexpk.html

JS:   toString() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqggvauzm.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyolslhp.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtqdcwgzio.html


<!-- 参考信息 -->