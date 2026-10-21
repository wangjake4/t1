代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtiurrfuge.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gtbrvrezgh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gtbehqxkjm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.birdmap.top/Article/details/gtiqdkrtcf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtysrsidme.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtlpnrkkiy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gtizqdsfas.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tianlin.xyz/Article/details/gtbgzeimal.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.svipenyu.cn/Article/details/gtrikjmbbe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhiwuduotai.top/Article/details/gterwyrscj.html

[E16] 数字千分位
来源：http://dali.sxryk.cn/Article/details/gttftprkaj.html

Py:   f"{1234567:,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtkvpluhmk.html

PHP:  number_format(1234567);
来源：http://dali.nwbrower.top/Article/details/gtctrcjrbu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtwmfoowmn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtfbzaybrd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gtmbxkdghk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gtkledsbve.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daria6918.cn/Article/details/gttgmnlczz.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gtdpcfwcwo.html

[E17] 首字母大写
来源：http://dali.xuetiantiany.cn/Article/details/gtdlifcnmv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jianghu66.top/Article/details/gtdbkgovya.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gtorhdefos.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtjtlnxsuw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtupohokif.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gtwwcqywvu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigufen.top/Article/details/gthhjwwrpk.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gthalapfha.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gtmugzdmwh.html

[E18] 模板占位符替换
来源：http://dali.yongpay.top/Article/details/gtdagbjiky.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gaohongyu789.top/Article/details/gtfvndaemo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuanzhike.top/Article/details/gtczgmlyfz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtkerjdptw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtmyqdutng.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtfenxpbzy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gtvlbilflt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigfzy.top/Article/details/gtquqpkmhx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gtjkcxqspz.html

[E19] 多行文本按行拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtcxtpkfzp.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gtfzzqmkph.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtapjvupxw.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtweqztxzw.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteoaymcbt.html

Java: s.lines().toList()
来源：http://dali.birdmap.top/Article/details/gtczfebqka.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtcgyapgpz.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtyowimvvm.html

C#:   s.Split('\n')
来源：http://dali.pycfn.com/Article/details/gtpxcyyepq.html

[E20] 判断字符串是否为空
来源：http://dali.hongshengwenyu.top/Article/details/gttxzoosqu.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gtgvelluwn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxinkj.top/Article/details/gtguowfkvc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gtrzpvhhpr.html

TS:   if (s === "") {}
来源：http://dali.cashguo.top/Article/details/gtydquldpo.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtireojbww.html

Go:   if s == "" {}
来源：http://dali.tanke756.top/Article/details/gtdzshidoq.html

Ruby: if s.empty?
来源：http://dali.jianghu66.top/Article/details/gtgsjfohvj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258888.top/Article/details/gtatjmtnir.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gtpbghnlxx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gtomaqerdi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtjnakytgg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtplalmduz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtzchuzpvf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtjmerlivw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tanke756.top/Article/details/gttrixyzer.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtubpyspnz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gttnixlnnb.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtlkizxjfr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gttpdrkojm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtleypdgzd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtfuvoaakc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtgyqgyewn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtjnljlgxg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gtnekbphww.html

Ruby: s.bytesize;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtldvyyqib.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gtnsxxvjpl.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtrcjtcrfc.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gturuguraa.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtkqnjcdmy.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gttskuydik.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gtszqinckl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258.top/Article/details/gtunwynqbt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ybcxt.top/Article/details/gtkggexgrb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtnfetfbbi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtmfnnsgzg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sxryk.cn/Article/details/gtlofvkwxo.html

Ruby: File.read("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtdabfjrls.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtuyqgplmc.html

[F02] 逐行读取文件
来源：http://dali.birdmap.top/Article/details/gtxutmrsaz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gthblzdgag.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gtnmiccsdw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtgbgsekbw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gttzzbdkio.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtgxcajexj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gtlsoryykt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttanumdln.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.svipenyu.cn/Article/details/gtnrryzmnx.html

[F03] 写入文件（覆盖）
来源：http://dali.ydzc1.top/Article/details/gtvevpzvia.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gtudgkrqpl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtyfcjbtew.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gtkvmaardc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gteglalgha.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtxidftmde.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gtztrzdtxj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.smart0.xyz/Article/details/gtgzdhkwhb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtrnjuhbxn.html

[F04] 追加写入文件
来源：http://dali.cucudq.cn/Article/details/gtbadqanoe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.birdmap.top/Article/details/gtecikcyje.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gtueulylmo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtxgmfmqee.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gthiditnyz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.quarkkingdee.top/Article/details/gteruuuxsf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gtqmjxrybi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shuidangran.top/Article/details/gtjcknspes.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gtvcbbkwad.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtxfozrujl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtvykcails.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtwggbzomf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtcepdjati.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtrcavcfrq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtsxvqmgrr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gtugqooajt.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtbkuhfaye.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtevuivybd.html

[F06] 删除文件
来源：http://dali.gogol.net.cn/Article/details/gtoljjpyln.html

Py:   os.remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtybzvdvkn.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtqgvbwkkh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtgjhckosi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtgssmynyz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtdvmosiyu.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtityfarjw.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtayzsvvzg.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtychelvuv.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gtowobellk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtnbargvfh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gtjvcsqtfe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtbdepviwy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gtdqgbawin.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmjhaaol.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhixingplan.top/Article/details/gtevownzfm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gtnhwmyabw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gtllcsqmmt.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gtebbbzxlc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.vqdsnc.cn/Article/details/gtqftbeurv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shzxlz.cn/Article/details/gtbbeeogjb.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtkljeltux.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtmpcopmrp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtjwcbqmxt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tanke756.top/Article/details/gtzdsenjsm.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gtxyopmddn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenzaomai.com/Article/details/gtuhylrryw.html

[F09] 获取文件大小
来源：http://dali.hysaishi.cn/Article/details/gtreriuuqe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtcqfhhssy.html

PHP:  filesize("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtxwoqamtj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtkikcfipw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtrbpmhypi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtxhwxiquo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gtasonxzuw.html

Ruby: File.size("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtfxgahqer.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cheryme.top/Article/details/gtnoqhwjei.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gtdybntlrc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtxiuconvd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gtxcipryvd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtwnynoagv.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtonbcofpb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtvhgjgcah.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtvkmcoqzr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtbnqryjto.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtjiqbpphj.html

[F11] 复制与移动文件
来源：http://dali.gotoacloud.top/Article/details/gtimxwjgdm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtsefpakzk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gtgsbchwft.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtlyxccshm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtoyujlijw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmkegvto.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuxming.cn/Article/details/gthfqciegb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtgpqhjdqk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.0kj1m.cn/Article/details/gtntvwlstr.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gtbvmmmwwm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgufenzy.top/Article/details/gtrnividcl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gtgehthidv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gtkpcykwqk.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gtvqfaddzl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gtcmetijdr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtptvcchfa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtqcpvywpq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nwbrower.top/Article/details/gtnwcuvjsl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtvuevazrb.html

G. 面向对象
来源：http://dali.xuanzx.com/Article/details/gtomxfqmnc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthfadvofc.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gtctgtukha.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtwhgprrej.html

PHP:  class User {}
来源：http://dali.jinqigufen.top/Article/details/gtpxfphpyx.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtpfrqyvib.html

TS:   class User { name: string = ""; }
来源：http://dali.yanxiufei.cn/Article/details/gtqicrgtdf.html

Java: class User {}
来源：http://dali.zhengqikj.top/Article/details/gtaqlherye.html

Go:   type User struct { Name string }
来源：http://dali.aizwys.cn/Article/details/gtahssvysh.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gtynvmtvys.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtxwnmwuny.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gtpajxtuco.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gtppidslmv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gtswxgycwa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtstylxxqj.html

TS:   constructor(public name: string) {}
来源：http://dali.yonumen.top/Article/details/gtlbtiojdc.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gtyhfmnxpv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj202588.top/Article/details/gtexoxgjnp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gtcjvtggyw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtehjsvsnf.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtgygonqzr.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtilubtilh.html

PHP:  public string $name = "x";
来源：http://dali.shuidangran.top/Article/details/gtbuvtxqqq.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gtkheeoxwt.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gtcyvlhcyl.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gtqszfrivf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.haohaochexian.top/Article/details/gtukngtrzt.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gthmpugiat.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gtbhzzjibo.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gtpsztrlxu.html

Py:   def greet(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gtykcjfgzp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtxjbaurrl.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtvqpvmqni.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtkvzcxcvp.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxucdqrtq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtuonsxqkh.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwebjreh.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtrdqdvulb.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gtdtdqodur.html

Py:   class Admin(User): pass
来源：http://dali.hywenlv.cn/Article/details/gtdecwqhlm.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gthiskzcjw.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtstuxkghy.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtzzqvndhd.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtolfcaicu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gttkezdfsx.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtotfgxeqa.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gtnkxtkqjh.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gtsaosenop.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gtxkxppsll.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gturcyhbef.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxjfadvcg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgnuxntp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlgeausxc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtbswnlqjp.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypabmnzn.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gtoovbvxni.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gtevrsuttn.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gtdmoqjdpe.html

PHP:  parent::greet();
来源：http://dali.yvedp.cn/Article/details/gtoxltjpvg.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtkyeqwpww.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjollmxhy.html

Java: super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmbstlgi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gtmhrtbwjg.html

Ruby: super
来源：http://dali.feifeiyinyue.top/Article/details/gtxdfkfrzs.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gtprzemmpp.html

[G08] 静态方法与属性
来源：http://dali.jiagoushi.top/Article/details/gtgxymybzp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gtpubutnih.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtgkzsdase.html

JS:   static f() {}
来源：http://dali.iojbl.cn/Article/details/gtyocxatkr.html

TS:   static f(): void {}
来源：http://dali.aibaodan.cn/Article/details/gtlcygrotn.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gtcbsqvvqm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gtzeobaplq.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gtupduacnr.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gtbswqpqvc.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gthmbtzclz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gtfclzzalv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gtthdxtkvh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gtyqskcoqa.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gtzcomkxsd.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gtaacfrxzi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gtpbljlcni.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gtsgjzooez.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gtspaksuba.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtpkxhtzll.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gtwjojkvnn.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtapoepiyk.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gtwslqkgxd.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtwltloaki.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gtfmtljubx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.0kj1m.cn/Article/details/gtvtvrdmsd.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtzvolqezc.html

C#:   public / protected / private / internal
来源：http://dali.yonumen.top/Article/details/gtudrlsnqm.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnozgoipo.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gtfaipikpa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gttldkfoif.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtmhascmow.html

TS:   get name(): string { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtdirqxbln.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtieusrdsr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtkbvmfvgg.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtkcqwshgk.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gtxcthlfck.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazqjxdca.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtzhrxsvik.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtedibrutb.html

JS:   toString() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtyokvkzuv.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtpxykcxhy.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtaccvehzt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpcmzdzy.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtvlnvbgno.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gtkmgffnjl.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gtwcroxnbe.html

Py:   isinstance(u, User)
来源：http://dali.fengsongda.top/Article/details/gtzzprhsax.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gticwhbetu.html

JS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtzepmphtv.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtzphwxrjm.html


<!-- 参考信息 -->