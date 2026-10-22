代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nkgoohys.html

Java: String.format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gt2uzxwboqs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2hilnhqzy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2utoszuuf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aibaodan.cn/Article/details/gt2rxpwwbdb.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gt2cesvlfem.html

Py:   s[::-1]
来源：http://dali.ivvv.top/Article/details/gt2pjnerxtz.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gt2qepaypwz.html

JS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2vsekzawz.html

TS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2fkhqwnts.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gt2adgbmuvk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258.top/Article/details/gt2shoacatk.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gt2wkmdvvor.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gt2kdmgowie.html

[E12] 统计某字符出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxttpcgk.html

Py:   s.count("a")
来源：http://dali.shuidangran.top/Article/details/gt2snxmupyh.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gt2uzysmeyk.html

JS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gt2buotlmvo.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gt2degzrxse.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuanzx.com/Article/details/gt2pwgmdlft.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zoinepwr.html

Ruby: s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gt2bemtysyf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuanzhike.top/Article/details/gt2rzlcexnm.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gt2axxwbcfe.html

Py:   for ch in s: print(ch)
来源：http://dali.fzhhl.top/Article/details/gt2bldkzehx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwjzahdb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2idiqfkdh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2somyeeyv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gt2grfecxgl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuanzhike.top/Article/details/gt2dsilutio.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gt2aagbltur.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtcvxkpa.html

[E14] URL 编码与 Base64
来源：http://dali.tanke756.top/Article/details/gt2vivanqqr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenjidiqi.icu/Article/details/gt2oqbpctsd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2xyndvsnt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fzhhl.top/Article/details/gt2ixsifhhu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.redwolf501.top/Article/details/gt2goflecfj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gt2wirpwpyc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gt2qqfcahai.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.birdmap.top/Article/details/gt2msrttvwr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gt2xjzspfem.html

[E15] HTML 转义 / 反转义
来源：http://dali.fzhhl.top/Article/details/gt2rgbiugio.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenzaomai.com/Article/details/gt2nmpfkmwx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pycfn.com/Article/details/gt2fmzdtvzr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gt2nqbrwive.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jyoumei.cn/Article/details/gt2jrugacxf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.vqdsnc.cn/Article/details/gt2gyxtcxyi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fzhhl.top/Article/details/gt2bqtaldnt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sysykeji.top/Article/details/gt2dhtjbpqh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ehwqpu.com/Article/details/gt2ejyjepna.html

[E16] 数字千分位
来源：http://dali.jyoumei.cn/Article/details/gt2llmnnwkz.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gt2mvmpfdyj.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gt2ubizujqd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gt2prdqaumz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gt2fcixhluc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gt2cuzygibr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gaohongyu789.top/Article/details/gt2gurgnjqv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xziqi.cn/Article/details/gt2cbdvndns.html

C#:   1234567.ToString("N0")
来源：http://dali.cqqwz.cn/Article/details/gt2mvymzkpc.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gt2linvpgbm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gt2ljyrulkn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywxfbfzu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gt2sdflsema.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gt2rtthimbx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gt2wcckpdhz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258888.top/Article/details/gt2otgnhigk.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjrmhsy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gt2pflumsxe.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gt2ivgusnkt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhixingplan.top/Article/details/gt2hrkglajo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gt2nggyqvzs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2cazwowrf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2tjgkpwwe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2knhljehs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gt2udlhlzxv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ehwqpu.com/Article/details/gt2hlgenbpm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hfpthk.cn/Article/details/gt2hvopmchm.html

[E19] 多行文本按行拆分
来源：http://dali.yonumen.top/Article/details/gt2fsnpscqc.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqzgmgzi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2efkfmeou.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gt2llcgacig.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gt2zhovkvav.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gt2zuudxnol.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gt2gsermvbu.html

Ruby: s.lines
来源：http://dali.bjfxy.top/Article/details/gt2cdorndnc.html

C#:   s.Split('\n')
来源：http://dali.guannengcc.top/Article/details/gt2vtgtxqpy.html

[E20] 判断字符串是否为空
来源：http://dali.zhixingplan.top/Article/details/gt2avnxjgyh.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gt2ilpztnhr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gt2uobyxnip.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gt2lhojujus.html

TS:   if (s === "") {}
来源：http://dali.daria6918.cn/Article/details/gt2gkjcoxqr.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gt2zndkgurs.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gt2lxpgvbuv.html

Ruby: if s.empty?
来源：http://dali.mhx1999.top/Article/details/gt2eatatmfn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2jqimmkfb.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gt2nhgnxmoy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gt2vdmiuojf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2dgurutjw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrerjplu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2vipzlvxx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2edybuqxw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gt2ftdelsmm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2nyyvdxop.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2weptcvtq.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gt2tzwlrvxs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhixingplan.top/Article/details/gt2vlgvxjsc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2amaxdsvr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2bvjgwamg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2ceixworc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gt2terihzaf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.havefunace.top/Article/details/gt2amdcsjvc.html

Ruby: s.bytesize;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2qyyjjnqj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangdashe.top/Article/details/gt2sumghqaj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2hsgteppj.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gt2awhawykb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ugywtprs.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gt2nehsupzf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gt2uidanqud.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2mcxwhcco.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gt2xgvxxvqr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gt2byhdoxdm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2tldjbqeq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gt2pumljjqh.html

Ruby: File.read("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2hfruqhpy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2ywfstmwi.html

[F02] 逐行读取文件
来源：http://dali.hywenlv.cn/Article/details/gt2nvkqptee.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gogol.net.cn/Article/details/gt2hezagaru.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gt2tbjdocuy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cisjzksr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gt2sosreyhn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gt2mpjbcptw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxinkj.top/Article/details/gt2aorxuuti.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yueranfly.top/Article/details/gt2fgwupqgw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hcofghfg.html

[F03] 写入文件（覆盖）
来源：http://dali.hnxiangtu.top/Article/details/gt2pmazwsio.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gt2aypyhwaj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gt2fqjqtymt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gt2knlnpdqa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gt2mjntgeov.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.meibo888.top/Article/details/gt2qavehxjp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmakksgn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gt2edseczwn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gt2pfnneyak.html

[F04] 追加写入文件
来源：http://dali.cucudq.cn/Article/details/gt2yznwezys.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2jbdzbkdu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gt2efapmeix.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gt2pooticaf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gt2gieiyzwo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jiagoushi.top/Article/details/gt2baohjvoq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2mikayyao.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuanzhike.top/Article/details/gt2mklmcwua.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj202588.top/Article/details/gt2jewfhqml.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gt2wjzhzkde.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvogbsm.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2sguatklv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2bxztoxbg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2jctpzmtw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2qksywlvs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gt2omhldbyb.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2lxpvltqr.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2qfhgesrk.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gt2froesnja.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2xowujxve.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2uyqzwuao.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvqclkuv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2bqsajofv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2slfquqrd.html

Go:   os.Remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2wncjerwk.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2vsejlcgp.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2gcmqllgd.html

[F07] 创建目录（含多级）
来源：http://dali.hywenlv.cn/Article/details/gt2aqlmeniy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fiokygmw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cioustns.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gt2tbwujkdv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gt2umspxxrd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gt2isdupvsg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jnagptij.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tdtbxlfx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.bjfxy.top/Article/details/gt2qyzsnqdq.html

[F08] 遍历目录
来源：http://dali.bjfxy.top/Article/details/gt2leqxykzw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gt2srjelmee.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guowangkeji.top/Article/details/gt2qcsgualk.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gt2oxzteush.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2humstmci.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gt2guecysuw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258888.top/Article/details/gt2ydtdktyy.html

Ruby: Dir.children("dir")
来源：http://dali.xinyue.icu/Article/details/gt2wnbmpfnw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2esbqulpp.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfqghecz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2zliamtqw.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2iiflurob.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvioldtm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2tmlijnnj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vsckqeys.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gt2domrljcz.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jsofirmi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gogol.net.cn/Article/details/gt2acqvdcvv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gt2ykhwaneo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2wnbjsuax.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2tsyjjybl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2vzelvosr.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2dopunjdp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkzownle.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2efrhfdvn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2mtcxfuvp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbrhcmqn.html

[F11] 复制与移动文件
来源：http://dali.0kj1m.cn/Article/details/gt2hqqcmtiz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2salnouhj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gt2xqazjihd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2untzijzh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2edavgabh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldqpsiud.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.haohaochexian.top/Article/details/gt2ztucndth.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2ukoiuuqm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xantkmkp.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gt2idfwyfps.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfgmxewe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gt2zoqogpdm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gt2bpbjttsz.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gt2tfvmovop.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gzhubu.top/Article/details/gt2dudliefi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gt2pajvpcrv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.iojbl.cn/Article/details/gt2yysafjbd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdgjojbs.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2akddzqoc.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gt2pewofmog.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2hlubcpoh.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gt2kxpkrekz.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gt2fdzxcxpx.html

PHP:  class User {}
来源：http://dali.yueranfly.top/Article/details/gt2ioejkdqn.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2hpsvwfrf.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gt2zetccelw.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2rkdxmyjv.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gt2eopvffkj.html

Ruby: class User; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2fmurlfgo.html

C#:   class User {}
来源：http://dali.yuxming.cn/Article/details/gt2kmbntfhw.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gt2qxbmzhuz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ehwqpu.com/Article/details/gt2dvjrartz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2mevqlncq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2elxkamqv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rndiylfz.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gt2hhoknorc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenzaomai.com/Article/details/gt2hzbdlmcx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2ngnepkyl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2vesqwgab.html

[G03] 实例属性
来源：http://dali.nanxinkj.top/Article/details/gt2zrsimwxf.html

Py:   self.name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmdjvorn.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2mlseucrw.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2fdwdrvgz.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gt2oonvcohb.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gt2onzwmhoo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gt2tgewttme.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2tcgyarax.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2jporyvlc.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gt2pwqylngl.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gt2hcqssenp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2uzkpwldm.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbkvcrkj.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2bajbuhbk.html

Java: String greet() { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2mxrbqzob.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gt2urfeeuwb.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gt2mniyyslh.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fhneljwh.html

[G05] 继承
来源：http://dali.jianghu66.top/Article/details/gt2rfwrfnmh.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gt2xdifztdk.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2wdevzpqg.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2oilbjooa.html

TS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2tcylpehl.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2okdomjcy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gt2ebbcisib.html

Ruby: class Admin < User; end
来源：http://dali.dianchejie.cn/Article/details/gt2ffjbtckt.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gt2yjglqptx.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gt2goeciphc.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gt2upmwqhyi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ujatyhqq.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2jcgtngww.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2xdebeqnw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2weftjbco.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gt2etsokfkh.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gt2plmxjldn.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gt2vkiwjqaf.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gt2voottxhu.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gt2wvzxlhwl.html

PHP:  parent::greet();
来源：http://dali.yj20258.top/Article/details/gt2nmxvbysi.html

JS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2jlvvhefh.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2zcmhenmj.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2nzvckgiu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gt2ybogvmir.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gt2xknypwlp.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gt2lnnfvxzz.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gt2ydrypxjp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gt2dfaawkbu.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2eqiuqump.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2odotdiwn.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gt2yeoxzffg.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2yughudds.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gt2ruynjpcz.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gt2jklqseff.html

C#:   public static void F() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2jxlnbcak.html

[G09] 接口 / 抽象类
来源：http://dali.daria6918.cn/Article/details/gt2djdkkwnr.html


<!-- 参考信息 -->