代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtqlgwugzf.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gthsqajzww.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sxryk.cn/Article/details/gtgmrweiud.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtthqyyavm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dashuyun.cn/Article/details/gttmunviay.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhixingplan.top/Article/details/gtxixispky.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tian-w.cn/Article/details/gtmroaptgv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gtidkpildg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jiagoushi.top/Article/details/gtcpaprdqm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gtqtfpkcbl.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gtgwoaphze.html

Py:   f"{1234567:,}"
来源：http://dali.hfpthk.cn/Article/details/gtphsgzahz.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gtthublzoa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gttvdsmkdq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtnxmibmne.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmioscdi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.havefunace.top/Article/details/gtmntvivlw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gtkyjipayz.html

C#:   1234567.ToString("N0")
来源：http://dali.guowangkeji.top/Article/details/gtjihwjdyh.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gtskngqkkm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gtmeyhvhsz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtlynvetqa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtuvmmtkfm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtfcjnnhki.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gtillueblt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jyoumei.cn/Article/details/gttxhafdun.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gtxzvbzfzi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxuanxn.top/Article/details/gtcdpsxmte.html

[E18] 模板占位符替换
来源：http://dali.cheryme.top/Article/details/gthvwhgxve.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gtdafxadty.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gthnycbwbn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtsfarterq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtzrsmhnme.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtusynzbjz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtibszyysr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuanzx.com/Article/details/gtwhkzkzbp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gthcjaunin.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gtyqzalwcc.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtrjzjdjpc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gtmpygahpy.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gtjxzatrlz.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtikmwcyjh.html

Java: s.lines().toList()
来源：http://dali.sysykeji.top/Article/details/gtzxeogxou.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplobbwfo.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gtlkqkvgwm.html

C#:   s.Split('\n')
来源：http://dali.sxryk.cn/Article/details/gtmgbduglu.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gtzfisvkwd.html

Py:   if not s:
来源：http://dali.birdmap.top/Article/details/gtjlpxoplr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cqqwz.cn/Article/details/gtxoqzcpqv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj202588.top/Article/details/gtkacvwpos.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gtugfzdkuf.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtsxvflliv.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gtsgfgoznp.html

Ruby: if s.empty?
来源：http://dali.pycfn.com/Article/details/gtqryowwiu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258888.top/Article/details/gtaynfoagp.html

[E21] 超长截断加省略号
来源：http://dali.zhixingplan.top/Article/details/gtsjyslwbj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gtgmaglbpy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtngbiwkmi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtdnynlvtx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtqcpfratd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtjgnogfzv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gtyrwefbyh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtorjeldnh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtryzilfxc.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gtpusxjpis.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtsiijbjec.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtfbenepki.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtaatjrfca.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtcaienofj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xinyue.icu/Article/details/gtubslscqn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtgtfyxpqz.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtpfmbmjth.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtlhmzwvmm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtcafbbicp.html

F. 文件与目录
来源：http://dali.jinqigfzy.top/Article/details/gtfdipbqgg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzmwrgnds.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gtfrdvmclg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gtjnfgpama.html

PHP:  file_get_contents("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gthxsrfqup.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gtmofeulby.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gthsprptuz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtrjphndzj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gtwrqkjqbz.html

Ruby: File.read("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtqhphcxho.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcdjbjlr.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gtjexaqggj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gtjienvnnf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nwbrower.top/Article/details/gtjdzgfkul.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtaozqicra.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtpcxomxns.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtpjdnfjqt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.havefunace.top/Article/details/gtwfydwdwk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guowangkeji.top/Article/details/gtliqclgpf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gthsazxqoz.html

[F03] 写入文件（覆盖）
来源：http://dali.havefunace.top/Article/details/gtctdfbied.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtgyqlgtxs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtcqfiqbyf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtqvqivhik.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtbbkgkpeh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hywenlv.cn/Article/details/gtpjwcvhgk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yvedp.cn/Article/details/gtcogqjtdz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtnhphatbg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtgoyrwmpn.html

[F04] 追加写入文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwfutuqu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yvedp.cn/Article/details/gtexbrscbq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj202588.top/Article/details/gtwxlvftny.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtwanbzcqp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtmuslfccm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.c1oappe.top/Article/details/gtcgypfdiw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gtgwchnlhs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gtrowlbmfy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gtmfsgxzdo.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtdgitqkmj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gtisxxkycb.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtbjoaogof.html

JS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtqpnmslgh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtqzhlzzxn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtcqcwjbpn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gogol.net.cn/Article/details/gtjjfhhvqa.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtldhmjsih.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtqduoqwas.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gtnvvlmpat.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtssjrhczn.html

PHP:  unlink("a.txt");
来源：http://dali.yj202588.top/Article/details/gtvlxsccen.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtcwvhivxr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtygaxmwre.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtocyfwjdb.html

Go:   os.Remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtndzpwqwm.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtqjpbczaz.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtmgyiuoqw.html

[F07] 创建目录（含多级）
来源：http://dali.nwbrower.top/Article/details/gtvuglnnyg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtklgioxvx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ehwqpu.com/Article/details/gtcpheeffv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlyyzjlt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gteicuksqe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gtigyshbrc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gtfplzxgpw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gtqjbunwuj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gtdvoeuyxm.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gtnlkkhmwy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hysaishi.cn/Article/details/gtbmagstzj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gtvpkkuags.html

JS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gttrbkshir.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtdvyhsupv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpidadnba.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dianchejie.cn/Article/details/gtjskjqqup.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gtuyschiel.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gtnmejjgbp.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gtntwggvod.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gtisursvlc.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtzgpkzorh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtuviojszx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gthrssufmh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtazpiszoq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shuidangran.top/Article/details/gtlclxpzfm.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtitoduhhc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtrbmhiowk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dianchejie.cn/Article/details/gtaklgsrdn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtfucscpoa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gteahpyeqt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtbkcoogmk.html

TS:   path.extname("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtuadetxmt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gtvxceosiw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtrkfgymfb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gttwgjtpfg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gttsaoeucs.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gtehxdrial.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gttfmlrdpt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtgapceosi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtufsvkqlz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtvnhbsfoy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtczfstqzh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gtaahvrucv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtbtiudyad.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtdbqhpmjs.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gtoyjemzlw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtgwbsxpyq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yueranfly.top/Article/details/gtxbbzphsh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gtpgdlxote.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gtwzdrbndu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gtfpwejbwy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ydzc1.top/Article/details/gtpvhalcha.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gtzuubrfcl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.snrcjt.cn/Article/details/gtellooxof.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjecolulx.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gtkgnvidiz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtllkdzkmk.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gtzamjlmwz.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gtdlkjhsll.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gthfyjcvsj.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtthuxzhhx.html

TS:   class User { name: string = ""; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxdpztui.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtuwqwvyxf.html

Go:   type User struct { Name string }
来源：http://dali.havefunace.top/Article/details/gtxujelpqy.html

Ruby: class User; end
来源：http://dali.sufxvd.cn/Article/details/gtvvgrbpzt.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtxqhwpdid.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gtoconnvln.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gtnirghqxl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gtpdqacfjg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjwvzvktw.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gtuchctnqp.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtalavjbfy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtjlnrvmxz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtyscegfnu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtoacqyunr.html

[G03] 实例属性
来源：http://dali.cdnleiting.top/Article/details/gtrncqocrr.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtbimnopto.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtsskhtfil.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtbllfeech.html

TS:   name: string = "x";
来源：http://dali.xinyue.icu/Article/details/gtfldhrmdi.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gtlwghupbc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.316326.xyz/Article/details/gtfxlwxowm.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gtvuotgmeo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zdqjudy.top/Article/details/gtycyzvmlj.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gtiumdkoqb.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtblycsbvh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtkuagrwif.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtroznsnxw.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtmgehpwuw.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtwglxflui.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtduhugeae.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtxygvuysj.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtrcshskne.html

[G05] 继承
来源：http://dali.gaohongyu789.top/Article/details/gtsinexwkb.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gtbtaqixsd.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gthgzfjwfi.html

JS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtotgrrizg.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtksocoutf.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtvqvuoppl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gtatcmeakc.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gtltguqzbx.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gtusirppbn.html

[G06] 重写方法
来源：http://dali.ehwqpu.com/Article/details/gtccnubtgs.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gtoxkljshr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtqgqkjohj.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtwsrabnnc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtlbjkulor.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtpjbyecyc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gtmxkmvsoa.html

Ruby: def greet; "admin"; end
来源：http://dali.jyoumei.cn/Article/details/gterjxxpar.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gtkpyyktwc.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtxyyymaft.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gtbyqpmdbn.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtohgmaaav.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtklfowgma.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtvgtohaux.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gttmoiezap.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cdnleiting.top/Article/details/gtnbmryhla.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gtwdutuzvb.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gtxqyfwupw.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gtrpmmaysb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gtsuhbvsai.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gtvhbzsimq.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiafmbbzn.html

TS:   static f(): void {}
来源：http://dali.fzhhl.top/Article/details/gtriwvfxgh.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtccstvktm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gtxsogoqgl.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gtrecsamcy.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gtqbamgqll.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gtplyyfzil.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gtkbkyytkk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gtwosckxez.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jianghu66.top/Article/details/gtwscnvfxu.html

TS:   interface Shape { area(): number; }
来源：http://dali.gzhubu.top/Article/details/gtnydywyuk.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtnuakyase.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.snrcjt.cn/Article/details/gtujymoyvv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtuljgnrkp.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gtkpysqraf.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gtikegpaqh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gtbwarultb.html

PHP:  public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtuhjjculo.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtnlhwrgyz.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtmxzunkbd.html

Java: public / protected / private / 默认包级
来源：http://dali.xylfe.cn/Article/details/gtwquvqfrq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pengpengdd.cyou/Article/details/gtsofrojev.html

Ruby: public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gttyyhccbq.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtwybjilox.html

[G11] getter / setter
来源：http://dali.c1oappe.top/Article/details/gtcmvuaymf.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gtlvbposqp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgznqrrg.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqufgqray.html

TS:   get name(): string { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtrkogccyp.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtildpoajc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtopuagzox.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gtybivnniy.html

C#:   public string Name { get; set; }
来源：http://dali.zdqjudy.top/Article/details/gthhbkadvi.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gtyusyqgib.html

Py:   def __str__(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtfrrhaktk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtyakangpj.html

JS:   toString() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyeguyztn.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtgscpbmcv.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfrgambl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gthwvniizc.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gtudojcaed.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gtbwoelqsy.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gtrzghiqgd.html

Py:   isinstance(u, User)
来源：http://dali.zhixingplan.top/Article/details/gtomqrqhqs.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtfjpbmiyf.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtfqkpmkio.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtxmezyklh.html


<!-- 参考信息 -->