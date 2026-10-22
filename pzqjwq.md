代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.birdmap.top/Article/details/gt2zbnzmgqe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2dwltavac.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ehluxhnw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258.top/Article/details/gt2dwgyfdik.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gt2fboizuex.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nshwzemm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cqqwz.cn/Article/details/gt2djhlwnmy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gt2ldwtgqzp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.bjfxy.top/Article/details/gt2eszfljwj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2awqvpqmt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gt2daokbwmo.html

JS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2lxqyrbpo.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ffzjlace.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gt2zgdtdell.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gt2qaeqzubt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2eszcivkx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gt2ceqlucsw.html

[E11] 反转字符串
来源：http://dali.ybcxt.top/Article/details/gt2zfoqhgxt.html

Py:   s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gt2fkevzcor.html

PHP:  strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gt2ghtjydvu.html

JS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2wryeetqf.html

TS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2nsnzszoo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gzhubu.top/Article/details/gt2jgvamqml.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gt2freaulbg.html

Ruby: s.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2jxftqfwm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aslihuaf.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gt2ysfeutpl.html

Py:   s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gt2cpcpwsmq.html

PHP:  substr_count($s, "a");
来源：http://dali.daria6918.cn/Article/details/gt2mfcytiyo.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gt2lslpjnky.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gt2awcryysw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gt2mqjnaxod.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gt2nzarigem.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2ydakmwar.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zycfv.cn/Article/details/gt2piutffgx.html

[E13] 逐字符遍历
来源：http://dali.hysaishi.cn/Article/details/gt2htutibal.html

Py:   for ch in s: print(ch)
来源：http://dali.yongpay.top/Article/details/gt2sqfiszxz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgfzy.top/Article/details/gt2astishko.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2hzlnxduf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gt2rhubndra.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2llkrvxwl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gt2haplzmec.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzqfftlo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2iusjejth.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gt2hcxmxxfx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gt2fktsubjj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gt2rpvzagdg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fzhhl.top/Article/details/gt2lpmoxnpl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gt2rzxbqntq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gt2rflnouoz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nwbrower.top/Article/details/gt2cfgekjgj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gt2fcpdplfz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.iojbl.cn/Article/details/gt2fjvzdvhl.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gt2wuhhblkh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gt2tfbgfmox.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2ricnnalu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ybcxt.top/Article/details/gt2aaaxnlbq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xinyue.icu/Article/details/gt2inzjbexm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhixingplan.top/Article/details/gt2dfnulfqs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xylfe.cn/Article/details/gt2rtojjzwh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gt2moylpjsv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj202588.top/Article/details/gt2pzjewtrj.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gt2ggwshxxn.html

Py:   f"{1234567:,}"
来源：http://dali.yuxming.cn/Article/details/gt2jwmvvuru.html

PHP:  number_format(1234567);
来源：http://dali.hnxiangtu.top/Article/details/gt2apfxbytm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gt2gqxetwuz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gt2hwrtuzuw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gt2cdfajbyt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nwbrower.top/Article/details/gt2funcaove.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.smart0.xyz/Article/details/gt2ljcfznrx.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gt2ceqeovvz.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gt2lfyiyaqe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fengsongda.top/Article/details/gt2ayfiodai.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuanzx.com/Article/details/gt2gqagbcee.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gt2jbdyjspm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gt2hdufolvk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gt2hczoqegy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gt2mkiiqezl.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gt2psrgnyyv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gt2cplnawig.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gt2vrdkkvdf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnxiangtu.top/Article/details/gt2cyyvvyso.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2epzeddvc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2jdpndrla.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lpvdvsat.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gt2hpepsfwe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2ztgqnefh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gt2bwexbohj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jiagoushi.top/Article/details/gt2benzrcus.html

[E19] 多行文本按行拆分
来源：http://dali.aizwys.cn/Article/details/gt2sczxrmnb.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gt2efkvskjb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkejjfso.html

JS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gt2fehpppgu.html

TS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gt2ezyauzpd.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gt2nwqpfugw.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2zvoklrza.html

Ruby: s.lines
来源：http://dali.iojbl.cn/Article/details/gt2sqkvgdtm.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gt2bmsbfmap.html

[E20] 判断字符串是否为空
来源：http://dali.hysaishi.cn/Article/details/gt2ugrmizpj.html

Py:   if not s:
来源：http://dali.pycfn.com/Article/details/gt2ogmszutf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gt2dvfotzlh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hammf.cn/Article/details/gt2vazgqznt.html

TS:   if (s === "") {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqnnlwuy.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osaualof.html

Go:   if s == "" {}
来源：http://dali.havefunace.top/Article/details/gt2micgfgys.html

Ruby: if s.empty?
来源：http://dali.hnxiangtu.top/Article/details/gt2htsqhqde.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.c1oappe.top/Article/details/gt2tjfnmbxd.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gt2tavtckyq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gt2evfzxsgo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2vwqrjcco.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2lkhaucyv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2bxvrkmsr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2nrkwduwl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gt2aqyjxyhr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2dyiqtvtl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2rraeaolr.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oclnsesw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gt2evirrdcx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2xdarrnbq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2uwbwrzjz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrhxujut.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.havefunace.top/Article/details/gt2uvgacjmu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cqqwz.cn/Article/details/gt2ahqzhxfd.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gt2cjkcffaq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jiagoushi.top/Article/details/gt2ywexgvzd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2kbvqcpuc.html

F. 文件与目录
来源：http://dali.dashuyun.cn/Article/details/gt2izqijbux.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2dpzvridl.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2gsfpcrei.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hfpthk.cn/Article/details/gt2yjylkfjn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2oiikjslj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gt2wazuufna.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gt2yowaojoa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2fciidhvb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gt2puhgcatq.html

Ruby: File.read("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajqntvhr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2erljcdow.html

[F02] 逐行读取文件
来源：http://dali.andypj.xyz/Article/details/gt2xfupqfeg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gt2qvgcjcdo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gt2hxgarydl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gt2jsktrvuo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2gtomveqe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gt2qpwxffhm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gt2dhwrwoiv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gt2kznfuoaq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jiagoushi.top/Article/details/gt2fdgyfijr.html

[F03] 写入文件（覆盖）
来源：http://dali.zdqjudy.top/Article/details/gt2esvpddas.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cheryme.top/Article/details/gt2cjmsrqsg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2rxhjgrrn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gt2wilcuwjl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gt2wdsbvsed.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gt2cvvhpbxn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gt2bqzpdhqm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cucudq.cn/Article/details/gt2gwtyqyzs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gt2fmszgxhp.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwzfvkhq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gt2iokfkshu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gt2ktnrdugx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gt2csipmvjp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gt2hmtcjiwv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gt2eeozzdxv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sxryk.cn/Article/details/gt2soueymqw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gt2onhegvwa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gt2dcltxxgu.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2zaxkievk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gt2miolsmiw.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2ydjmtpwy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2kenulvey.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2wyefscav.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tywyafaz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sysykeji.top/Article/details/gt2xvgpdcjs.html

Ruby: File.exist?("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2zbwupqbh.html

C#:   File.Exists("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2fkbhspiq.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gt2nhdqikvl.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ydugfjpp.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvfoutiv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqnyltzk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2guzginlg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2jdybujxv.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2kjtxwngm.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2xlmfycyg.html

C#:   File.Delete("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2rmbexvmv.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gt2wposwnhq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gt2xkcadlgu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gaohongyu789.top/Article/details/gt2yllcknnb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gt2uavfzgsy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2vvrhaqle.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxinkj.top/Article/details/gt2ttohyyxe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gt2zgqtvlka.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jyoumei.cn/Article/details/gt2cvfmtsmt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gt2dovjxrmm.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gt2qsbfosep.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gt2hqikseue.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gt2takpfymk.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gt2ybdyucvy.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzikzoii.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gt2kwxibjxy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyarzqbr.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2pbibfuao.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2sokcznrs.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gt2anhysfhv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2vjuwoylk.html

PHP:  filesize("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2dlkclpec.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aoqxthys.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gt2tfhpmggd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2earxtavf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuanzhike.top/Article/details/gt2tyhkzzjy.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2izmbpgkw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umdmkxwv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gt2ttoepmed.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2hqmixzlr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2qtqohnfc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2srvdjlfz.html

TS:   path.extname("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ovyggkgp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gt2ifvkabdc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2dnxkzppy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2jjkahupe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2owpagpks.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gt2arqrqrnn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2lxxkpzbz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gt2ugbjtltk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2tiorknfy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2eleptrhq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daria6918.cn/Article/details/gt2pvppgsud.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gt2zjrkkcjx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2uftkaifc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenzaomai.com/Article/details/gt2ggqlmhbq.html

[F12] CSV 读写
来源：http://dali.cucudq.cn/Article/details/gt2byqngawu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ybcxt.top/Article/details/gt2wwnmbegr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mscegrpy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gt2xxzihmjr.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gt2klrpvwcz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gzhubu.top/Article/details/gt2adbzebyj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gt2nduzfhtf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gt2blpcbiij.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qviaueej.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2zwdndryd.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gt2obippjad.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2pelijwtj.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gt2wsgvjorz.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gt2lbjjugjy.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2hgeawxew.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2hlpqnvfv.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gt2wdvsyybu.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ibfyhvwu.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gt2myyryqlm.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gt2ndxnleqd.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bezgtqsr.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kielisbu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuanzhike.top/Article/details/gt2mrpnxtra.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gt2ifpkjvec.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2lgmwtlls.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gt2nxjgrueq.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2hzllulwj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gt2tcwfarrg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwlkkvyy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2bvmxbwgo.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gt2bazlnkaz.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gt2zdeybpql.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehnpkwuw.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2kwtkdqwf.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2vlniowim.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gt2jrgolsqt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gt2ntcqemoi.html

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2kfssyggs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2nxncatpx.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gt2beiefwud.html

Py:   def greet(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gt2fpgqxvhb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2puanqkpo.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2unrkrfxp.html

TS:   greet(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2vppkaxsy.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2udnreppf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2ebzorskl.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qazdbllt.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gt2iqpzhxqd.html

[G05] 继承
来源：http://dali.jiagoushi.top/Article/details/gt2buqyjmbp.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gt2wvleuvyg.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xryhejrm.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2boyqluso.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2csbfhwjm.html

Java: class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2gskylfgw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gt2fzpitupd.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gt2hfptdssd.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gt2fokczzxs.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gt2hgqfprbo.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gt2xjcfmaud.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2gwdryqfh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2fuiwzzpx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2ygjqmney.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hsjqllpa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gt2laydpaax.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gt2orrndlny.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gt2etravkpf.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gt2uzousgfs.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gt2hvuanblm.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gt2izkzgsth.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2iswaawli.html

TS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2gkfzotau.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2pmywpqgo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gt2nwttspbe.html


<!-- 参考信息 -->