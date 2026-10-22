代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ivvv.top/Article/details/gtctbpaicl.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gtyigplmiu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuxming.cn/Article/details/gtmyqfhfyj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gtkszfoakl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.quarkkingdee.top/Article/details/gtneeezcdr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgfzy.top/Article/details/gtvlmkbmrg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gtugibneta.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gtotrtllwt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gtgehqypbc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtfuujlzxu.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gtjnddkgbi.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gthhzmiiqi.html

PHP:  number_format(1234567);
来源：http://dali.cdnleiting.top/Article/details/gtmzssrvzr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtnyivicnx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gttqhaojuj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.redwolf501.top/Article/details/gtzfsdutyx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gtjcuwqrtv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sufxvd.cn/Article/details/gtizqznjhn.html

C#:   1234567.ToString("N0")
来源：http://dali.andypj.xyz/Article/details/gtjuyulzni.html

[E17] 首字母大写
来源：http://dali.jqgufenzy.top/Article/details/gtbrtniked.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtqcavsxzh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sweek.top/Article/details/gtswkboknd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtfyashphh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtcegbpbby.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjokpwob.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gteyvlhlhj.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsuxcfvv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hfpthk.cn/Article/details/gttkaxyjvi.html

[E18] 模板占位符替换
来源：http://dali.mhx1999.top/Article/details/gtahsfupuz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pengpengdd.cyou/Article/details/gtnhzhmljr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daxiang520.top/Article/details/gtxzdpcewj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtsrxdvicq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtpcarpgfn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtuuarctci.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhcqwtys.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gtpodcyvva.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gtwxccqirf.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gtoehwmuwf.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gtzexgxzrk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtruhkblfe.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtpabjfawi.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtjcksdi.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gtdocfatrt.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gtrfbvmfhd.html

Ruby: s.lines
来源：http://dali.dashuyun.cn/Article/details/gtehsxdblq.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gtruywefip.html

[E20] 判断字符串是否为空
来源：http://dali.hammf.cn/Article/details/gtshykdvcw.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbhkqygt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.vqdsnc.cn/Article/details/gtdwkrmmvx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtindyirqp.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gtnxhqwzpj.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtxkfpowae.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gtvugotouw.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gtahjztbmr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gtujzkgoip.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gtylgqwcsu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.316326.xyz/Article/details/gtioficwmc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtxuinnoys.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtdadvmacs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtfnnhvsyn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtlgkojhfp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuanzx.com/Article/details/gtojgdhvhq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtnfdfrhwg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtdjuhgacm.html

[E22] 字节长度与字符长度
来源：http://dali.guannengcc.top/Article/details/gtxqyzbply.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gtqpdyqdxz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtfxixmxpk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtgukjmnmc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtcmxjqfjn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtnvipcwkf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dianchejie.cn/Article/details/gtjcnrsuil.html

Ruby: s.bytesize;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtacyhmmua.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gtynpfpjzt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtrlzpttsw.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gtdenanzqx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmxhoqrvj.html

[F01] 读取整个文件
来源：http://dali.xziqi.cn/Article/details/gtrijlvkjy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gtfyjhcsvb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gtfruatkgn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gtffwdztkt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtaoobjyah.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtujfhcdsv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gtoavqpjqg.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gtyknkmjgw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttipznsks.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gtwmxtskoz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gtittnascc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gthevlmaon.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gthopquyfu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gthorrnenx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtkytawdip.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gtzmnxnpvi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ehwqpu.com/Article/details/gtvoschcwk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gtigcxqgwg.html

[F03] 写入文件（覆盖）
来源：http://dali.fengsongda.top/Article/details/gtrtewyycv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gtrrfolbnm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtxcmnjwjt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtolmokswp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtffumqpmz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gtsymtxpxo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gtfrkxnwee.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtaocdwbku.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gttqxejukh.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gtbmvuvfyx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xziqi.cn/Article/details/gtwlfqfttd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtqwllinbx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gttkkrpyxg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gttxhteogu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.316326.xyz/Article/details/gtbkbvgorh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtnzsddygx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gtgecixzbj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujiixlhk.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gtlnuuauxe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hammf.cn/Article/details/gtkxlyfxwc.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gtlefratkt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtdgtfcxmi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtosuzzrxh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtbdofoalq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gtaqmiwopk.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gtnhwwwkwi.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtnozkzhcu.html

[F06] 删除文件
来源：http://dali.pengpengdd.cyou/Article/details/gttrmjcwjg.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtlqbkmzdz.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtmvxcfoca.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtoaeycand.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtvhhpqmfc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtyduzgltw.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtuqrnuyom.html

Ruby: File.delete("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtjlgkevcp.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtjofstjct.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gtjcxkjbak.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gttlpuszsz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenlongwang.top/Article/details/gtagvckmzf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gthuvgbknf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtiojilmrg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gtqjujygck.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gttnzydzoa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ybcxt.top/Article/details/gtmwdrdrvn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkzykkwn.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gtahxpclxr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hysaishi.cn/Article/details/gtmheoiuis.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.kuanghao11.cn/Article/details/gtgashqsca.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtozjbowtv.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gthqpjbhve.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtovcenrtx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pycfn.com/Article/details/gtogjbjryb.html

Ruby: Dir.children("dir")
来源：http://dali.tanke756.top/Article/details/gtnrvsjyob.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gtjcifiktw.html

[F09] 获取文件大小
来源：http://dali.gotoacloud.top/Article/details/gthtbucpft.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hammf.cn/Article/details/gtphcaqygx.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtuxuslyol.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtxqwcacfj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxqmhpft.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gttgofynkn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gtdgqbwafw.html

Ruby: File.size("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtyjcuaexl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gtsecqhdec.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gtsbxyihfn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtuifkqkjh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtgfetyzke.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtknyhhnys.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtstzdzlsd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gaohongyu789.top/Article/details/gtrwpjhiid.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtyxeipuig.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gttchvawgh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtzzhcmsfn.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gtobwdarhb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtaiuorptf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtjqkcttwc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtciqdchhj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gthrdcttex.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtleavqckd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gtgudtpoqd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsakrqmry.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gtbbikqkaj.html

[F12] CSV 读写
来源：http://dali.yonumen.top/Article/details/gtzfsuuhgv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gtqfvrelwg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gttdrwxiii.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gtyxmleqhh.html

TS:   // 同上
来源：http://dali.bjfxy.top/Article/details/gtmdjhvfem.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gtvqzoxrrr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gtawspsvow.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yueranfly.top/Article/details/gtfkueyssn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gtydpqxxfn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtwshmdjur.html

G. 面向对象
来源：http://dali.chenjidiqi.icu/Article/details/gtqvrnkhvq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtpqfzrzli.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhgsyebv.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gtztnmaqdk.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gttbezbtcn.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtveqivgpk.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgufenzy.top/Article/details/gtbctqxplb.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gtdybbfufx.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusotaaud.html

Ruby: class User; end
来源：http://dali.hnxiangtu.top/Article/details/gtepdtpjbp.html

C#:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtlkgazkry.html

[G02] 构造函数
来源：http://dali.hnqzz.top/Article/details/gtnbpkjdvs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gtahxthidl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtgjjlqops.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwldupsbu.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gtocbgmqly.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtjtsigmup.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gtjccnatnb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtdcjpddou.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtkgpoihiz.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gtuadxwkzk.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtkiyaoavs.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtjvatznnw.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gthbksggfv.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gtkvwesoce.html

Java: private String name;
来源：http://dali.daxiang520.top/Article/details/gtfcojuzsv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtfzidvvnq.html

Ruby: @name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtmhwkavvr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gtgkmwgptp.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcehzpcz.html

Py:   def greet(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtgncjbiuh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtkcezfaby.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtqwshgesx.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtmlwkvzkp.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtvjypseoz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtedoyzppk.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gtbkpsvlwr.html

C#:   public string Greet() => Name;
来源：http://dali.sweek.top/Article/details/gtyiavjqok.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtnfvbgrlp.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtojcbhzsj.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtaxxzdezq.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtkburrsqt.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbeehgkgc.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgouaahe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gtpjlhyvly.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gtekduqqcc.html

C#:   class Admin : User {}
来源：http://dali.ppjwa.cn/Article/details/gtzrobuxjo.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gtbdvosuaw.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gtueaexhbw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtceidlalr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrifrkghe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtgfdtevgl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjoeqrmwl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyhclcqm.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gthaifbnyr.html

C#:   public override string Greet() => "admin";
来源：http://dali.dianchejie.cn/Article/details/gtdhwcivop.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gtunfjyogq.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gtojuckqiz.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gtlpikznqw.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gthajfzjfx.html

TS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtrtljbjad.html

Java: super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtqhuaqhnh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cashguo.top/Article/details/gtpbovbuzl.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gtedgkanlm.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gtnwjfguky.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gtjrcardmt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtesucnkvz.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtfwamnmbp.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gtwburhpgt.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gtbzebuhps.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gtvsesfqao.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gtaqzudono.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gtlefjfcnx.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gtwuvasjys.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtwdmuxuyn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gtngchymfx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtidgckpin.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gtztneosot.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gtfdixdqun.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtertoqhua.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xziqi.cn/Article/details/gtkdgfgzuc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gtewuehhej.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gtrmsyjtfh.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtxbbbshiy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gthcmvtxxg.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtmofefcqv.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gttydzqnui.html

TS:   public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtapynusmo.html

Java: public / protected / private / 默认包级
来源：http://dali.wangshuangyany.cn/Article/details/gtgtpushra.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtjgpotzjl.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtvrimdcwd.html

C#:   public / protected / private / internal
来源：http://dali.svipenyu.cn/Article/details/gtuoobkvjo.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gtldeqpjtp.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtcxpcbkew.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtcmwpcmbv.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtewqdklzr.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtdkotjokn.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gthwdemwai.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtywqsghcl.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gttsvzowwn.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigfzy.top/Article/details/gtqfrywdql.html

[G12] 对象转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gteovznacp.html

Py:   def __str__(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtcdfatylh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtsxdtrmma.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtuxpbvtwf.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtsmkxxjfl.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gthadzewmh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtmyqurosx.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gtgquyxitr.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtqcwfxhze.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gtgajsvnmc.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtdwrgtpmh.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtjpmoasmj.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtvdnsawvl.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtwrfujaia.html


<!-- 参考信息 -->