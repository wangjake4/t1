代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gt2saiqbhjp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gt2mbqasosf.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gt2xujgnozi.html

Py:   ",".join(items)
来源：http://dali.xylfe.cn/Article/details/gt2nscuzlge.html

PHP:  implode(",", $items);
来源：http://dali.xziqi.cn/Article/details/gt2tuldbupm.html

JS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujjiczsc.html

TS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gt2bncdrclf.html

Java: String.join(",", items)
来源：http://dali.c1oappe.top/Article/details/gt2svsaeihb.html

Go:   strings.Join(items, ",")
来源：http://dali.daria6918.cn/Article/details/gt2sanefvbd.html

Ruby: items.join(",")
来源：http://dali.xylfe.cn/Article/details/gt2cozrvjbh.html

C#:   string.Join(",", items)
来源：http://dali.mhx1999.top/Article/details/gt2jxnuafhw.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gt2pzszwutq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yvedp.cn/Article/details/gt2qansfstb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbjnznsd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gt2shtipnym.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iehlxvfj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gt2fpzutmde.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgufenzy.top/Article/details/gt2bjsiltzx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258888.top/Article/details/gt2wfwwtfyi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuanzx.com/Article/details/gt2sbzvogab.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sweek.top/Article/details/gt2nomggkpf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gt2bxxjcodb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gt2bbukfasd.html

JS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2xtsdbpvg.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2yowvtgvv.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2dwvdetsx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ocjhsxqz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gt2rlizfucx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yangfankeji.com/Article/details/gt2nragvebt.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gt2sitrqgjc.html

Py:   s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gt2waecwihp.html

PHP:  strrev($s);
来源：http://dali.gzhubu.top/Article/details/gt2uzfvpehs.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2ywhwpinx.html

TS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhkzncpb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ehwqpu.com/Article/details/gt2xuppgwva.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gt2fnvdmbll.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2fuqizdwm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gt2kkyzoesv.html

[E12] 统计某字符出现次数
来源：http://dali.ybcxt.top/Article/details/gt2skcqypkz.html

Py:   s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gt2gvjmefbd.html

PHP:  substr_count($s, "a");
来源：http://dali.xylfe.cn/Article/details/gt2nhnehlji.html

JS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gt2rosmbctr.html

TS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gt2eavmwpqw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfjplwag.html

Go:   strings.Count(s, "a")
来源：http://dali.yangfankeji.com/Article/details/gt2ooygothp.html

Ruby: s.count("a")
来源：http://dali.iojbl.cn/Article/details/gt2zsnkuwln.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gt2kutljsco.html

[E13] 逐字符遍历
来源：http://dali.hfpthk.cn/Article/details/gt2ovxdysrk.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfjgthtd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxinkj.top/Article/details/gt2rqbfwtvo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxkaefmd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2zckknnsw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2nlldiheq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gt2azgcnxjf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ouiihpkc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2mkxrvnrn.html

[E14] URL 编码与 Base64
来源：http://dali.316326.xyz/Article/details/gt2hgvjlnas.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gt2apustwyg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gzhubu.top/Article/details/gt2msqwaqtg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rotlsray.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2owjkkdow.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sadxuffc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jiagoushi.top/Article/details/gt2cyuupfsm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.svipenyu.cn/Article/details/gt2zjiszldr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2fyetyrix.html

[E15] HTML 转义 / 反转义
来源：http://dali.ydzc1.top/Article/details/gt2wvhyfcgz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gt2tdtqpbve.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2duobvzrb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ivvv.top/Article/details/gt2iahuvwxe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sweek.top/Article/details/gt2mjyfvzqf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gt2hwehxszk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gt2nviqytjo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gt2czesowly.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gt2dqyqxses.html

[E16] 数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gt2bentfuku.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gt2qckvifoa.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmzehdqc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwzixlyb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2lahretmu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gt2iwqvgtpd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.bjfxy.top/Article/details/gt2vivqeiul.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pycfn.com/Article/details/gt2tewvprsv.html

C#:   1234567.ToString("N0")
来源：http://dali.zhixingplan.top/Article/details/gt2zmqoqvea.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gt2jezumbau.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.bjfxy.top/Article/details/gt2wffuhmmq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bcparylj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gt2opgykscb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2fczeiipv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hammf.cn/Article/details/gt2cwfttiqz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2sazbmkcv.html

Ruby: s.capitalize
来源：http://dali.sxryk.cn/Article/details/gt2gutvebjz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ivvv.top/Article/details/gt2pgzjpqna.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gt2hkzxvejp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cmnmlfcp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmlexihb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2faazoxlc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2hthyjfsk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2nokubjah.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2xhrvcslh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gt2klnrfkze.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zbvkxsmx.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gt2hnzfpjnh.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gt2jxtxfsmo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gt2dklxfdld.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgoyenuz.html

TS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gt2hrbcxdup.html

Java: s.lines().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2esckfavu.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gt2ecqiwgzb.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxkkosu.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gt2yrzeqeyr.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gt2kswnyaua.html

Py:   if not s:
来源：http://dali.zdqjudy.top/Article/details/gt2klhmwyno.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gt2wmlazige.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gt2mmeymndu.html

TS:   if (s === "") {}
来源：http://dali.yuanzhike.top/Article/details/gt2qhoaysrw.html

Java: if (s.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gt2dqalsnon.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gt2mpyqrpcu.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gt2wbvcslra.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yonumen.top/Article/details/gt2hihveahd.html

[E21] 超长截断加省略号
来源：http://dali.jiagoushi.top/Article/details/gt2cudunitg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.snrcjt.cn/Article/details/gt2slpvunox.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wtfiawtj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2xfpaidcj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2pfcphcyn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwtcyaay.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gt2xzsppnro.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2ruufsern.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmvtwpon.html

[E22] 字节长度与字符长度
来源：http://dali.zhixingplan.top/Article/details/gt2xllncruc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuanzx.com/Article/details/gt2zwohmbch.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2zhrapgoz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gt2rfafddqr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqgqnzyy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2rqydqfqk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thpyazud.html

Ruby: s.bytesize;  s.length
来源：http://dali.yonumen.top/Article/details/gt2anjjwrhn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigufen.top/Article/details/gt2jncilpfu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2lrqoevto.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gt2pdiwvxgf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ixuowsgo.html

[F01] 读取整个文件
来源：http://dali.daxiang520.top/Article/details/gt2dcrnsuok.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gt2mmxycveq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2oinpyesq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.0kj1m.cn/Article/details/gt2ttxcgtha.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gt2qkwopjnj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2wpjnccom.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gt2pfcutuxp.html

Ruby: File.read("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2cswgniji.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2lhrkarcb.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gt2bpwgacfv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tianlin.xyz/Article/details/gt2xbvydznl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.havefunace.top/Article/details/gt2urskvayq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gt2zllvddgy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gt2mjigffan.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gt2idgwymvw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gt2yqfhiikz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daria6918.cn/Article/details/gt2farczocy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gt2uottuzwt.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gt2modkogpw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258888.top/Article/details/gt2jdfnzsum.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gt2kxhluocj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2gzjtzarw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gt2wgpkucuy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gt2wpelndhy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gt2fvquzrwl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dianchejie.cn/Article/details/gt2nklppcxr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gt2ppqdxvxl.html

[F04] 追加写入文件
来源：http://dali.yanxiufei.cn/Article/details/gt2csontygn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2pvbkpnvc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.vqdsnc.cn/Article/details/gt2tyvecceq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gt2yefwtrpa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gt2qabhprnt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gt2ranwcsav.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gt2qumbcvdj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gt2nvyjjyfk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gt2lvbrgitl.html

[F05] 判断文件或目录是否存在
来源：http://dali.daxiang520.top/Article/details/gt2pukiznxz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gt2vipttgcu.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2taecwseu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2mriylkhw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2zzdhkbwe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2ofyzoirw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gt2rsktrdim.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2wmmfrouw.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2vdnxkmrf.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gt2yhmjefrm.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2zbsiwlzn.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2vvplsbzz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2fmtfigee.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dxhelfzu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2zghfzvas.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbhuixaj.html

Ruby: File.delete("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wuopdexo.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2fqyhtkcc.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gt2lfczwtis.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gt2iprwxehr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zdqjudy.top/Article/details/gt2qvnussdc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmreyppe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gt2pguiqnyl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gt2aljogvzx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jiagoushi.top/Article/details/gt2gvjnompw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gt2puxlfhsg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2wikmfsrc.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eymvwqho.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gt2aeujrssw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gt2aykzvqaz.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gt2odjakoyk.html

TS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2qxnnbsaz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gt2giwbkvkr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2lcypkioy.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhbsocwu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2ldqehwbl.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gt2yukgopma.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2fbdyymii.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2rbxyatsp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gt2ucsslszw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gt2jxdcxxdm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2fvzqymhl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfvmvaec.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2enomteak.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gt2xaqspgmq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gt2ijurgztq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2ynknijyp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2atqzmnnf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2drllwwlr.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2nropawyp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tian-w.cn/Article/details/gt2pqgbsosf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2tnxtdqaz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2zzekoily.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2oldigwuv.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gt2mdtjnlqr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2szdcsfna.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2rmlhcppn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2dckdnvnu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2dgqptdrr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrmchnr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gt2ixyfyxix.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2fjdjvvni.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.bjfxy.top/Article/details/gt2zwpuslmw.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gt2qafznigi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gt2uxdjwure.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yueranfly.top/Article/details/gt2qvcwdhxy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gt2uzgzvwyn.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gt2tsnqrnbn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pengpengdd.cyou/Article/details/gt2wgenmvij.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guowangkeji.top/Article/details/gt2tsrxhlsf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnqzz.top/Article/details/gt2ednviron.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gt2rqaklmen.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2spezwyan.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gt2meuxtcwy.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2qqvyjfeu.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwwscxya.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gt2ajfqyvfs.html

PHP:  class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxldkytp.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gt2oqiqxbuo.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gt2dpptfysx.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2clijkvau.html

Go:   type User struct { Name string }
来源：http://dali.gzhubu.top/Article/details/gt2xjuhzzrd.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gt2nfoxrdqb.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2djmrvbwr.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmwfgyif.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnqzz.top/Article/details/gt2oyyvxnat.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cqqwz.cn/Article/details/gt2wnggkvui.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2ygvcmkrz.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gt2yrknzsym.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlfrdgho.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvmltcwy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gt2wvtkibbg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gt2twmthrfg.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gt2jgmyamon.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2szgsaymn.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gt2yvkzmdkd.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gt2gshrxsqm.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2wmjfujoq.html

Java: private String name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jsotrhsf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.quarkkingdee.top/Article/details/gt2btkohafc.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gt2gvokrsax.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yongpay.top/Article/details/gt2agkomyje.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gt2balijqah.html

Py:   def greet(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gt2qhozoavt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gt2msdascpq.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukpywvcl.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2pywmnxcg.html

Java: String greet() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2lzgqsztn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gt2akhvrllc.html

Ruby: def greet; @name; end
来源：http://dali.ppjwa.cn/Article/details/gt2txdzexnt.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2uuqlvnre.html

[G05] 继承
来源：http://dali.316326.xyz/Article/details/gt2jgvnxbzt.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gt2ihmmykex.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2zzcepacr.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2sbqqziaq.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2aqtimzca.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmbtrxkd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gt2mvhaatea.html

Ruby: class Admin < User; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxzsgvhh.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gt2slvucrdw.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gt2ktathuhh.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gt2avvvxnke.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2jdwgndaa.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2pdljunff.html


<!-- 参考信息 -->