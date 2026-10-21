代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtvcmbizko.html

[E15] HTML 转义 / 反转义
来源：http://dali.ydzc1.top/Article/details/gtwmtcclen.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sxryk.cn/Article/details/gtvwhvfbkv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gtqawkawsc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gtboyxrsbg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fzhhl.top/Article/details/gtspuvhqju.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.vqdsnc.cn/Article/details/gtsnzpuwpy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgfzy.top/Article/details/gtwhzpkbqa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.kuanghao11.cn/Article/details/gtyplqvbxk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yangfankeji.com/Article/details/gtnbiydyfm.html

[E16] 数字千分位
来源：http://dali.fengsongda.top/Article/details/gtkqkuqzlf.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gtnikgaoid.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gttcgzjjvg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gtykrbarlv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtzdceemvj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pycfn.com/Article/details/gtjhucdaxl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xylfe.cn/Article/details/gtjqisxufz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gtzmdnbhua.html

C#:   1234567.ToString("N0")
来源：http://dali.cqqwz.cn/Article/details/gtsdhgdifa.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gtzitttcub.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuanzhike.top/Article/details/gtcaysmaqb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gtwcslkntz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtkbmzvsjs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtruernwmj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tian-w.cn/Article/details/gtmlfexqvy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtbtriatjj.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgogzxux.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tian-w.cn/Article/details/gtpizptnfu.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gtkpbftutz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gtimxqwuxo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gtzztztrzz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtyiddxcnr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtgwukcpdu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtinofkiqw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.316326.xyz/Article/details/gtbainzrer.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuanzhike.top/Article/details/gtrouiijqe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gtzqeildqn.html

[E19] 多行文本按行拆分
来源：http://dali.aizwys.cn/Article/details/gtxyilgdtj.html

Py:   s.splitlines()
来源：http://dali.jiagoushi.top/Article/details/gtyaxbnxqx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtzlyyqbqu.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtikthipho.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtyshhnbfs.html

Java: s.lines().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gteoejhnlt.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtevmggpcr.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gtuqpctmpc.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gtdxvlotrx.html

[E20] 判断字符串是否为空
来源：http://dali.chenzaomai.com/Article/details/gtooqsgsom.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gtkigntbcy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shangyingyoupin.top/Article/details/gtfdxvdgtm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gtizdvzbeh.html

TS:   if (s === "") {}
来源：http://dali.zdqjudy.top/Article/details/gtjcvkjrec.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqozujgas.html

Go:   if s == "" {}
来源：http://dali.gaohongyu789.top/Article/details/gttnymuudd.html

Ruby: if s.empty?
来源：http://dali.svipenyu.cn/Article/details/gtsjwsiyhn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.andypj.xyz/Article/details/gtiwfuyhby.html

[E21] 超长截断加省略号
来源：http://dali.meibo888.top/Article/details/gtdkuheane.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gtgaxtyykk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtvlaywfor.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtlusgzrsz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtkxmpgknu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtsoccvwcu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgfzy.top/Article/details/gtcuhnevkm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtdxpwkmpl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtquuzfsuh.html

[E22] 字节长度与字符长度
来源：http://dali.nanxinkj.top/Article/details/gtawylawpv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtzwoizghq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gteyhxvhgf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtfjuzskxd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtwsusfbei.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yueranfly.top/Article/details/gtptaldqvs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zdqjudy.top/Article/details/gtnjbfwbqa.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtmefkctpt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dianchejie.cn/Article/details/gtkjkjuunu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwudbkrxk.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gtxhhnoqpu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtmlstxwra.html

[F01] 读取整个文件
来源：http://dali.yvedp.cn/Article/details/gtvenkddly.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guowangkeji.top/Article/details/gtddmaiack.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtkibtkhzk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yonumen.top/Article/details/gtgjxvnuxd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.meibo888.top/Article/details/gttcmfdkes.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtqjzoukfj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigufen.top/Article/details/gthbkaxwgs.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtyflzuqyw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtdlqsqryk.html

[F02] 逐行读取文件
来源：http://dali.zhongyouzk.top/Article/details/gttveqkknr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gtzwicwrni.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfzehqhwn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtsebxfvyy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gtuqtghodw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtkeihqzui.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigfzy.top/Article/details/gteuunvnqp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtjpcmyigq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gtwjtbbcdr.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gtaxcpgodv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cqqwz.cn/Article/details/gtfzuqeqab.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtcqfkvfgw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtqghcxhjy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtmrkwvfmc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtkadelmip.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.9152youxi.cn/Article/details/gtzpvzfmzo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xylfe.cn/Article/details/gtipnmkrds.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtaoclckcp.html

[F04] 追加写入文件
来源：http://dali.ehwqpu.com/Article/details/gtwrwonwaq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtajcpxavc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gthrdetghs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gtuduxybxa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbobavtfl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ppjwa.cn/Article/details/gttnqalobx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtgvzubimp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zycfv.cn/Article/details/gtpftglucl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.kuanghao11.cn/Article/details/gtqzqznmcn.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gtflcnoqki.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gtntnwiuaa.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtgahtrusb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtfafvsikk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtvturyzdp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtiyqdcwui.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigufen.top/Article/details/gtgtqeljnk.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtnoimilrx.html

C#:   File.Exists("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtbkdzbnxf.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gtuwhuvusq.html

Py:   os.remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtydlzxock.html

PHP:  unlink("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtcsnsxuiy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtccfcdjyl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhwpdsbf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtarxocygm.html

Go:   os.Remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhdwlmgt.html

Ruby: File.delete("a.txt")
来源：http://dali.hammf.cn/Article/details/gtjazaonzm.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfbjrsds.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gtskiktbqr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtieltuqmm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ivvv.top/Article/details/gtkjslfexm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtvzpijsey.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtydnzvcam.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daria6918.cn/Article/details/gttqqgdsge.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jyoumei.cn/Article/details/gtphivjrrw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gtntzhwjlf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gtvrlzwkjv.html

[F08] 遍历目录
来源：http://dali.yj20258.top/Article/details/gtjikbmcof.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dashuyun.cn/Article/details/gtthxymzwu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tian-w.cn/Article/details/gtqrebyack.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtomuwzlxx.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtqhftjzrh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gthqzguxvo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangdashe.top/Article/details/gtxugoxkoh.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gtxllbavjf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtiicwkkmi.html

[F09] 获取文件大小
来源：http://dali.zhiwuduotai.top/Article/details/gtjofchygc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtnlvasvdo.html

PHP:  filesize("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtzcjixdkl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtaxmqwzrl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtmhqkwjbm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtlvljpsdy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gtiluxgbnk.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtfrnjqutm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258888.top/Article/details/gtszxhjgsa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gtatjiyoso.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtsylsrvkp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtsmbgzoaw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtquxyfwgt.html

TS:   path.extname("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtcrgzhxgj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtchhtteni.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtjotrtqav.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtfxrlhvbh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtowtzgutz.html

[F11] 复制与移动文件
来源：http://dali.tianlin.xyz/Article/details/gtumdpriwc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtqcogppiq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtwycnvwvv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gteltalria.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtzuvxumgj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtjtvoupkd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gthczvibcq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtrqknmbpp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gtsquzcfsg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gtxaksnszc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gtcookcexj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gttbjvnqaf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hywenlv.cn/Article/details/gtjzesemyh.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gtjduxdksr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtasghljoj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenzaomai.com/Article/details/gtmtiblxcc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.meibo888.top/Article/details/gtqxdjtypj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gtzdhwwayy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gthyjshmus.html

G. 面向对象
来源：http://dali.feifeiyinyue.top/Article/details/gtfhgmdfcl.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttvxmhifw.html

[G01] 定义类
来源：http://dali.mhx1999.top/Article/details/gtwfamrcpa.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gtxkjswnwd.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gtblaaefak.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtmodgbkej.html

TS:   class User { name: string = ""; }
来源：http://dali.gotoacloud.top/Article/details/gtjhuwxvda.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gtoahmpnni.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gtxgobketn.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtuxxosfnh.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtazrqzvah.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gtcycquilk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gtrizdfnhc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtcwedhbag.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtqiwimyqx.html

TS:   constructor(public name: string) {}
来源：http://dali.yongpay.top/Article/details/gtpqsvbbfb.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtlmifztqb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gtrlkovguh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gtaowyboqh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtkoqxfjkz.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshraqlsd.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gtquthhmrr.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmszmcaes.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gttssqupwc.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtxkwromvk.html

Java: private String name;
来源：http://dali.dashuyun.cn/Article/details/gtxivhikxf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.mhx1999.top/Article/details/gtetlodeqy.html

Ruby: @name = "x"
来源：http://dali.pycfn.com/Article/details/gtagwwnwmf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsqhjgfh.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gthemqawuv.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtmuxdejbk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtzmgvaovp.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtwtznhade.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvaroazft.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtfrlitflj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gthmgfjpvd.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtaejpakbg.html

C#:   public string Greet() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtjocowlgg.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtiezneiss.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gtbcsnjevy.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtruxdkjfe.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtectevhaf.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtaobknqfu.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtrcxnrjks.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gtiejjpffh.html

Ruby: class Admin < User; end
来源：http://dali.0kj1m.cn/Article/details/gtejhbvcgp.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gtiphlnzrj.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gtdnnhzpej.html

Py:   def greet(self): return "admin"
来源：http://dali.havefunace.top/Article/details/gtcanszhep.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtxpktuwru.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrvqrxkah.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtyiabcvuz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtyifrneey.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gtsoltcjcd.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxinkj.top/Article/details/gtpnallzfi.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtvqliompn.html

[G07] 调用父类方法
来源：http://dali.snrcjt.cn/Article/details/gtmbryejhv.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gtgmiwysvf.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gtzcqkskdz.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtnhxxhgjw.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtcvhrrwcd.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gtyqcaftlm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gtexsuxjit.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyggszdyb.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrkwkbxk.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gthfilgnxl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gtogeimdqu.html

PHP:  public static function f() {}
来源：http://dali.guowangkeji.top/Article/details/gtiwkfiimd.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gtqlvpzoyo.html

TS:   static f(): void {}
来源：http://dali.yueranfly.top/Article/details/gtrmgmnzzo.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gtbqxsrcvj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gtjasvadrz.html

Ruby: def self.f; end
来源：http://dali.guowangkeji.top/Article/details/gtjsaxccnw.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdordcaal.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258888.top/Article/details/gtljqmbfcx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hfpthk.cn/Article/details/gtqttjlqxc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gtgigulgdz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gtuuramrgj.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gtrlikanzl.html

Java: interface Shape { double area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtrwbrpcxm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gtonpjpmiu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtnqpadalk.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxinkj.top/Article/details/gtvldkwsey.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gtsqivjece.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gtqqpujchp.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtyuxwherf.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gtroeoxeea.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtbnrneoim.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gtmcwsygis.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gtshvjxbxy.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtragyuhhc.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gtughqvewu.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gtzeisokrg.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gtehxxpvfq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtvbvhvlhn.html

JS:   get name() { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gttujvinpc.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtkospuzjw.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gtsgubuied.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtvupcyoph.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gtmlbmrxff.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gtsrwqacys.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtkefyegdq.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtbugovmzo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtntgnodhy.html

JS:   toString() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtljtgstdh.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtczynywer.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtjfowotii.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyimrzguc.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtdgvtxlzo.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gtpmksskxc.html

[G13] 判断对象类型
来源：http://dali.mhx1999.top/Article/details/gtcxhmunyl.html

Py:   isinstance(u, User)
来源：http://dali.jinqigufen.top/Article/details/gtaphhxmrj.html

PHP:  $u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtdizdrmwl.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtfayvwycd.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtpkegbmil.html


<!-- 参考信息 -->