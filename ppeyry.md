代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.zhoulong.xyz/Article/details/gt2uqvufvta.html

JS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gt2siphlixx.html

TS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gt2lasisilz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jiagoushi.top/Article/details/gt2cygrbbdw.html

Go:   strings.Count(s, "a")
来源：http://dali.zycfv.cn/Article/details/gt2yuqinkpw.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2atlvgaiu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gt2xxwxpjqb.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gt2zlfhdfjt.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gt2axleqlmu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqzowkru.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwenbkfz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gt2duzcahfp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2oetplzsd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gt2nztjgbln.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigfzy.top/Article/details/gt2pfgsiwsy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2wjjswmul.html

[E14] URL 编码与 Base64
来源：http://dali.dashuyun.cn/Article/details/gt2riudtxjn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gt2foidjtzn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mopwnsrh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gt2qasowxwj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenzaomai.com/Article/details/gt2kxwhlwig.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wluavtyt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zeecuzck.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gt2echisusn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gt2szsvmsnl.html

[E15] HTML 转义 / 反转义
来源：http://dali.tianlin.xyz/Article/details/gt2yrchsxjw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigufen.top/Article/details/gt2zfvvkwpj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gt2ljvnxvfs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2sllbxhwt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zdqjudy.top/Article/details/gt2galhskca.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guowangkeji.top/Article/details/gt2termpijc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gt2xlympqfr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2llddxhql.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sufxvd.cn/Article/details/gt2riiznjby.html

[E16] 数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gt2eeyecpvt.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigufen.top/Article/details/gt2oyubfcdp.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gt2gmswjrlm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gt2owzvselx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gt2lowuhyvu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cheryme.top/Article/details/gt2phgkbokm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.quarkkingdee.top/Article/details/gt2xnniktjd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.c1oappe.top/Article/details/gt2evfxqhyt.html

C#:   1234567.ToString("N0")
来源：http://dali.havefunace.top/Article/details/gt2rtyfbfqh.html

[E17] 首字母大写
来源：http://dali.tanke756.top/Article/details/gt2cbszmuxm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xrlkqrpu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gt2mqetlhhu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gt2cwnhupqq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gt2scumynme.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dashuyun.cn/Article/details/gt2ubskjdvp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2ucepyjqn.html

Ruby: s.capitalize
来源：http://dali.shangyingyoupin.top/Article/details/gt2qufwnifp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gt2himuuqer.html

[E18] 模板占位符替换
来源：http://dali.kuanghao11.cn/Article/details/gt2vflritpf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gt2bjmcyyib.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.vqdsnc.cn/Article/details/gt2snztuadx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2wqsywpmz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2otvytbzw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzqsthui.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2fhhxckvs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jyoumei.cn/Article/details/gt2ocoifsuf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gt2mkvqcyud.html

[E19] 多行文本按行拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2scysvhgh.html

Py:   s.splitlines()
来源：http://dali.svipenyu.cn/Article/details/gt2vrpdozwj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yongpay.top/Article/details/gt2mgtlcfuy.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gt2lwdptxgs.html

TS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gt2ngtkqtpw.html

Java: s.lines().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqknucbz.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rgmknynv.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gt2mnatynmg.html

C#:   s.Split('\n')
来源：http://dali.dashuyun.cn/Article/details/gt2sxcglzbo.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gt2dircahfb.html

Py:   if not s:
来源：http://dali.vqdsnc.cn/Article/details/gt2zwrgdbsg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhiwuduotai.top/Article/details/gt2ainywufu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gt2vauzppnl.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2lkijljym.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gt2bwcgcpkg.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gt2bpaadodt.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlmavooc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2irehvmbf.html

[E21] 超长截断加省略号
来源：http://dali.jianghu66.top/Article/details/gt2icdbsqvc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gt2vcqvirvx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2xxyqzxms.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2hmircgjl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2jnebzefz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2csopvlel.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigufen.top/Article/details/gt2lrixnylo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2ircljaip.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2wprrxipk.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2fzijmvgi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2mtkkowgv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2jtmrwlne.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2inipimoi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2lpuqynxy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gt2jlkrhrmn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nwbrower.top/Article/details/gt2mejnwkrg.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gt2dfxkyumj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gt2hueatoyj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2bfylruhp.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gt2wkccdieg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2mgpnmwbz.html

[F01] 读取整个文件
来源：http://dali.hysaishi.cn/Article/details/gt2lzzwipfl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gt2nbsruxdd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2vpmyxmvl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgfzy.top/Article/details/gt2cfcynvzl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gt2isopygkj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2wlfnblfs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hywenlv.cn/Article/details/gt2xoztbyxg.html

Ruby: File.read("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2jhyjxwwj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2pkpqprta.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gt2urvdzyhm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zycfv.cn/Article/details/gt2roxcecwk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tianlin.xyz/Article/details/gt2qwnfcwyz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gt2yniamhzu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gt2oyhmoodt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwwgwxxa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258888.top/Article/details/gt2okplurps.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gt2jkwqvxit.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gt2sjfcnowa.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gt2qvactihm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gt2psllzfxn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gt2fwhurgmh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gt2qwxeyncz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gt2ojoulmzi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxtaohlc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shzxlz.cn/Article/details/gt2rrzxsqyw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.iojbl.cn/Article/details/gt2joklqcae.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gt2kxcynjwq.html

[F04] 追加写入文件
来源：http://dali.cheryme.top/Article/details/gt2sluaycci.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuxming.cn/Article/details/gt2trtbwbtl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gt2mipbaioe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2jblcmtcf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2agskdhbn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gt2fictnnnp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2slyhdrxy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gt2dvwmmqht.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gt2ejrmzugh.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybniifja.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.mhx1999.top/Article/details/gt2imiuveyg.html

PHP:  file_exists("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2kxnydstp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2mjfaigui.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2bjpdpiku.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2holikuyd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atgtbtuq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2fmvubdgm.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2igcdycgl.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gt2yiyjudwd.html

Py:   os.remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vontzjeh.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vlmvorqh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2ziolawmw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2njvxzxvf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2etfggfyn.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2tuijxejw.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2lcliysng.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ydmaltuu.html

[F07] 创建目录（含多级）
来源：http://dali.cucudq.cn/Article/details/gt2svvobolk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gt2pdglweiu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.0kj1m.cn/Article/details/gt2rvippesu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gt2qiscxwip.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gt2tnafnxab.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gt2cgxapsje.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gt2ynwrvwxa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gt2iskhntxo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hfpthk.cn/Article/details/gt2regwomhf.html

[F08] 遍历目录
来源：http://dali.yj20258.top/Article/details/gt2tmpaphnu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ydzc1.top/Article/details/gt2rglsfabt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gt2gqjtmjtn.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zifqkttm.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2ymvyxvhc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2xdgxudku.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2sibeelnp.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2ugfkbhba.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2watxyiqa.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gt2tgrgzhnt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2gefddwok.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2kkinvifn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gt2qvvpzfyr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gt2ivwyjdsn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2qqdorffu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ptnumyht.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojgwihms.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gt2ouqivbwi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shangyingyoupin.top/Article/details/gt2wihqrvqb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2rraezyza.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2gzcmsqiw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2uqzypojs.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2dsyeslbb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xkggomda.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2qcupbesp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2jmzladqw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2cgzrzszf.html

[F11] 复制与移动文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwvnupzq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2gfhjoogo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gt2twpovlif.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2njrefpkf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2suwvjuey.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sweek.top/Article/details/gt2gafdrcqy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ydzc1.top/Article/details/gt2vdltuclb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2pvewfytb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gt2aguziexq.html

[F12] CSV 读写
来源：http://dali.guowangkeji.top/Article/details/gt2sidchnod.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dztgcwxc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gt2vamesmzq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gt2xjagvofc.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gt2phzysobu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gt2jdsjyfqj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gt2agwvhpiy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gt2oggvreen.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ngitbuse.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2tovsklfv.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gt2kzbclwfv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2lcljmhml.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gt2kkuxhitk.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gt2qcafskun.html

PHP:  class User {}
来源：http://dali.xylfe.cn/Article/details/gt2dlpnzxnd.html

JS:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2vweosvnj.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gt2bbdbkvjn.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2akspywvs.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gt2rmitjjei.html

Ruby: class User; end
来源：http://dali.yueranfly.top/Article/details/gt2mvqednmg.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbhwakox.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gt2dfqutgus.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.316326.xyz/Article/details/gt2wsewufdd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gt2vnqlyepa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2lfseydug.html

TS:   constructor(public name: string) {}
来源：http://dali.wangdashe.top/Article/details/gt2tttgspmh.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2jbomathd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gt2hhnorveh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gt2twsujxex.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2kqgaawbb.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gt2pjxgvprb.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gt2vwyencxe.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gt2lbaphdno.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2blbgptgg.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2ebxaytxu.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gt2sackznms.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gt2lrfwvzgj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrgdkrp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2ktlhnxxt.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gt2kjnmdkib.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jdocuiqh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2kwmhoyqj.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2tjfxjhcl.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2gjybxlbo.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2kejrkthu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2otlmkkbf.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2jqpwpnrk.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2rkaqpkjg.html

[G05] 继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2wffgqexq.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gt2tkvxpsnk.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgjuhwze.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svlvtqty.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2xepvbgme.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fuovwniy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gt2zhzomwme.html

Ruby: class Admin < User; end
来源：http://dali.jlsjyb.cn/Article/details/gt2oszxkrzl.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gt2kgwcjddc.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gt2wdigswbh.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gt2guxytzdb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2vuuqireq.html

JS:   greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2cdatfheu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2totofwey.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2nkthbvdf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gt2riremcjl.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gt2hqzoekcm.html

C#:   public override string Greet() => "admin";
来源：http://dali.cqqwz.cn/Article/details/gt2nrcgpiqp.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gt2pyeglgjw.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gt2sbcdmiyk.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gt2owzrbjap.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gt2aeufwfvq.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gt2jyyytydz.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2cyzoukdq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gt2mgjaarlr.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gt2likzriff.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gt2ocmmecco.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gt2uxvtafbb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nwbrower.top/Article/details/gt2kjivnxtt.html

PHP:  public static function f() {}
来源：http://dali.hysaishi.cn/Article/details/gt2drszjqnc.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rsfrisis.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gt2iokxwnlr.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2eyahbjpy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gt2faibyjjq.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gt2dwbzwjwt.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gt2ndgpulms.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gt2sejtajvo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gt2uunhbijg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2baeaniui.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gt2tlddywor.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gt2tzdzpllv.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gt2xbbnqgpk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gt2guvtuowq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txvphmub.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jauebspb.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gt2wtoggwft.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkcvatcj.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2ydktfmtj.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gt2yifbfvxu.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2amicbbkc.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gt2wkiybrgt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gt2nmxsducf.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2jckghlgc.html


<!-- 参考信息 -->