代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.xuanzx.com/Article/details/gt2ldnajkjg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gt2cwveiedg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gt2vivljtzh.html

JS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2syjuhloh.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gt2xmrdkwma.html

Java: String.format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqqpphbm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2tvjfusrt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gt2eurfzaho.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gt2siswfrrg.html

[E11] 反转字符串
来源：http://dali.cashguo.top/Article/details/gt2fzbpiapu.html

Py:   s[::-1]
来源：http://dali.yueranfly.top/Article/details/gt2gqxqlhtz.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gt2kmuvfsuo.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gt2cekjzbor.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gt2ydwpkcgx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gt2deehhbai.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gt2pagtoisj.html

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gt2ukrhecvd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gt2qwqbjeak.html

[E12] 统计某字符出现次数
来源：http://dali.snrcjt.cn/Article/details/gt2kjdsisth.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gt2veqdzocb.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gt2azjimdaw.html

JS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gt2kjtxjvuw.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gt2aaavtmvk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.0kj1m.cn/Article/details/gt2zqdicnic.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gt2sjpkekmy.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gt2qgywothm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.c1oappe.top/Article/details/gt2ephsfdsg.html

[E13] 逐字符遍历
来源：http://dali.zycfv.cn/Article/details/gt2oysekzww.html

Py:   for ch in s: print(ch)
来源：http://dali.pycfn.com/Article/details/gt2lhkxngdq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aizwys.cn/Article/details/gt2roktrudk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2yxsfxfsy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2amojgtlk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gt2qgcreblf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2tiogkkpd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gt2tlsmmrhs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ocuzpktr.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gt2ckdugbbh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.quarkkingdee.top/Article/details/gt2sbuoiati.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2quqetfvm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jsceyrad.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gt2vrpsgptd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcdrxwsw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gt2vblbtmdw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhoulong.xyz/Article/details/gt2dbgojqsy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2zgjbpspq.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gt2jwwrgaqm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uaonigrt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gt2qeurwbmh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gt2vhmxlosu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gt2vnvkkdlo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hysaishi.cn/Article/details/gt2tjyvfqbx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gt2mmrivlve.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sufxvd.cn/Article/details/gt2ryckbyzk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yvedp.cn/Article/details/gt2vykrbdjh.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gt2qehjspax.html

Py:   f"{1234567:,}"
来源：http://dali.hywenlv.cn/Article/details/gt2dufolgvf.html

PHP:  number_format(1234567);
来源：http://dali.316326.xyz/Article/details/gt2tcohzezp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gt2ddxttzse.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gt2yzobgcjr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sxryk.cn/Article/details/gt2mzojoyoj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangdashe.top/Article/details/gt2upuzavgh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gt2gtttpwia.html

C#:   1234567.ToString("N0")
来源：http://dali.9152youxi.cn/Article/details/gt2uhktvqpj.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfebbml.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gt2ugeznwem.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenzaomai.com/Article/details/gt2cweshupb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gt2aahdqqfb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2atiokmcb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aibaodan.cn/Article/details/gt2nmctdkgm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2xkwmrwqf.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2attxcbzm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ppjwa.cn/Article/details/gt2rzmbhoha.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gt2fjnlyejf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifcqwhhn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gt2osducxdu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arucqtlc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2blikygfw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gt2iqerdwyw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tian-w.cn/Article/details/gt2osklrijb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gt2pfbdyajt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhoulong.xyz/Article/details/gt2nauuhryl.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gt2osnlgmgf.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gt2qwtqrhhl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2jplnadmj.html

JS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2emlyqfuj.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gt2qyfvolqp.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gt2gqeftxht.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gt2jzytgplh.html

Ruby: s.lines
来源：http://dali.vqdsnc.cn/Article/details/gt2zaprglvt.html

C#:   s.Split('\n')
来源：http://dali.shuidangran.top/Article/details/gt2etvycwxs.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gt2uxylrsvd.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2msvtdpho.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.snrcjt.cn/Article/details/gt2jtxpudcp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tanke756.top/Article/details/gt2hkeirrpn.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gt2pnarayqu.html

Java: if (s.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gt2sjgaohwd.html

Go:   if s == "" {}
来源：http://dali.daria6918.cn/Article/details/gt2ssdbcvck.html

Ruby: if s.empty?
来源：http://dali.hfpthk.cn/Article/details/gt2jiplrgny.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gt2vzttvxxz.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbyqyqnl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gt2bhgsarue.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvhkjfgv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2qdfvckbm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2btixrjai.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2npowlmsk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubvvpkch.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2jfjpzkzx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2rhbfirhs.html

[E22] 字节长度与字符长度
来源：http://dali.cdnleiting.top/Article/details/gt2znuhqyfa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yvedp.cn/Article/details/gt2vimdbumq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2crwmtulp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2ipyjfram.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2wdekxiyv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2tngzotsu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gt2flmjgaqb.html

Ruby: s.bytesize;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2dxmojmty.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gt2odgbgjsa.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2jienqklr.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gt2hxqterrp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2nydvcjav.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cpzjrnfj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gt2wtsudlca.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2beeafehw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vxhdmnsh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2valuepbe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2vqxwudlx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhiwuduotai.top/Article/details/gt2tlbrznar.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2mlncovdg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2wjznyxer.html

[F02] 逐行读取文件
来源：http://dali.yvedp.cn/Article/details/gt2xubtyqbg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gt2akcrnpjq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuxming.cn/Article/details/gt2ceeaxosn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xqonncsb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkddrsoy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gt2gsgygevo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gt2bvcjpyeg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gt2aciexfky.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gt2vzeclvqs.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gt2dwczmnlc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkfpvyxa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gt2jfjwzspl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gt2gkbysrml.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gt2iksvrlnk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.haohaochexian.top/Article/details/gt2alrzkevu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yueranfly.top/Article/details/gt2dlvyjbad.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxinkj.top/Article/details/gt2lgibbxvs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gt2yzxhhifg.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gt2ilkseoab.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gt2vulfxqui.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hehenqlc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gt2adnutodw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gt2bblkcdrr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yuicdauy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2mbhqjpwx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gt2jigbrhdj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guowangkeji.top/Article/details/gt2nfivqeff.html

[F05] 判断文件或目录是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2oozatevw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cashguo.top/Article/details/gt2rxdsjfae.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2fxdckgbv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2mvjjnqqo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2ofkndjty.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2avtpnmco.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gt2jdmravue.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2vcbugtvk.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2whtsimlf.html

[F06] 删除文件
来源：http://dali.ehwqpu.com/Article/details/gt2etjxymxa.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2qlfaigzn.html

PHP:  unlink("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2hevphxow.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2febrinfb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2ddoasdpv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2oweyxmfy.html

Go:   os.Remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2qcvzhtjn.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2ihuptjfb.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2arskupyw.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhazriaj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gt2quwsvgif.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gt2wujzrcyh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gt2kudawqdm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2gelyewde.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yvedp.cn/Article/details/gt2ivinsjhp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bteriakd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qaxatxkq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gt2jhbajgyd.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llnttubx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gt2ahhpgppc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wgsuwdmj.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gt2pfbmzezk.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gt2jacyqtoq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2eocduynj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2nqkumhoa.html

Ruby: Dir.children("dir")
来源：http://dali.fengsongda.top/Article/details/gt2ljzicevl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2mxfjahrh.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gt2yslpxlxl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2hpbadlqn.html

PHP:  filesize("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2edpzsdfl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edfpjfft.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gt2vobmakef.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2mdjrgpat.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gt2hcpfvldj.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2iwoxiyzx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gt2ftpxqvwl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gt2kqikdenj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2twazdmaf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2blzizsdu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2oelvkhfo.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2xxfpgsar.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gt2dokvwjru.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpdoejba.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2acwopcgh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2vpndknjj.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gt2erguuqip.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwakzvcg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2uvjfuqit.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2ntkscjqm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dckdldie.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gt2eaocwmsz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gt2mcfiuawn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2djbztnva.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.andypj.xyz/Article/details/gt2pgbfylrp.html

[F12] CSV 读写
来源：http://dali.svipenyu.cn/Article/details/gt2ordzvrpc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gt2uxjsjqhc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gt2wfhvoyrt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gt2kvhwwtct.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gt2ihrssfwh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmeninau.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gt2jbxqprml.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gt2ikarxbsb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gt2mnzortls.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2utwyaqlx.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gordxzij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edmbkhih.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gt2rvuumxbg.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gt2yooydstd.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2eaurgwxd.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2wbdvzsaw.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gt2wzrkdbsk.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gt2hxatlikg.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gt2dapekupc.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gt2nabzvsso.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2xcrccshm.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gt2maxtczpw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigufen.top/Article/details/gt2wogvtogc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xuphsquf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2fxxyythc.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gt2vkjlyehe.html

Java: User(String name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2tlzjgyre.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gt2lhutmvwq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gt2exrizsld.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gt2rlhysqyt.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gt2qzywttpk.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gt2vhefibop.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gt2clbppenf.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2dusyyulu.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2jlhfnrpg.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gt2toxjdnzh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gt2aksijeyb.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ucabnrtq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwdxgjem.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gt2guxjcfnl.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqllcebq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2fcpejunz.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2igqxvytu.html

TS:   greet(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2qqmwkuuq.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2fnwhqhtz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2ekwdpzdi.html

Ruby: def greet; @name; end
来源：http://dali.cdnleiting.top/Article/details/gt2opaghoxz.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2kktojmnd.html

[G05] 继承
来源：http://dali.hywenlv.cn/Article/details/gt2vhwfybix.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gt2qjhffdko.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2uyasncdr.html

JS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2heoasebj.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2rcxqqfmd.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2lbtvztnq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gt2bsepgsao.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gt2lnjmvgbb.html

C#:   class Admin : User {}
来源：http://dali.shzxlz.cn/Article/details/gt2knojkbrj.html

[G06] 重写方法
来源：http://dali.nwbrower.top/Article/details/gt2sgcewmoq.html

Py:   def greet(self): return "admin"
来源：http://dali.kuanghao11.cn/Article/details/gt2fhepsvkh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2ouasvlxd.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2egyrxiwj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2ygkbkcsm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2dejwlpza.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hevadlyh.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gt2hwahfkfo.html

C#:   public override string Greet() => "admin";
来源：http://dali.andypj.xyz/Article/details/gt2fczhwwlv.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gt2zutvfkvh.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gt2kabwriwi.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gt2beijbxen.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gt2ncqpxzar.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2bpqlyihg.html

Java: super.greet();
来源：http://dali.yj20258.top/Article/details/gt2mtbufklr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gt2pvcfhquk.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gt2igbabcvn.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gt2muyoohfu.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gt2xvojrrpn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gt2homoneon.html

PHP:  public static function f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2avejftsr.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gt2hhhchtoh.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gt2msvfacyo.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gt2wrmbmvcj.html


<!-- 参考信息 -->