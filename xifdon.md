代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gt2yvilvxss.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnqzz.top/Article/details/gt2tezfncim.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gt2luzumuzd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2ewqahkfg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.iojbl.cn/Article/details/gt2wejjpbgn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yonumen.top/Article/details/gt2gyebapwp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.redwolf501.top/Article/details/gt2yqrfppsr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnqzz.top/Article/details/gt2ualmoffu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xinyue.icu/Article/details/gt2dpcavcqq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozalyyqv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tanke756.top/Article/details/gt2zlbniezh.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2xjzqlzwm.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2tquooqql.html

Java: String.format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gt2namozeyv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwozrcbz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gt2gibnfpxu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gt2xsrgqqon.html

[E11] 反转字符串
来源：http://dali.zhixingplan.top/Article/details/gt2bzcbeqet.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gt2eevkveml.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gt2lnaxctvo.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2jndzapdt.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2akbiusmd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gt2ucnnijcz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.havefunace.top/Article/details/gt2vcvwpbwo.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2hfqctzvm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gt2ptrztjxa.html

[E12] 统计某字符出现次数
来源：http://dali.jiagoushi.top/Article/details/gt2ajfltxdh.html

Py:   s.count("a")
来源：http://dali.pycfn.com/Article/details/gt2pxvtxoql.html

PHP:  substr_count($s, "a");
来源：http://dali.zhixingplan.top/Article/details/gt2xrjzfszl.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gt2ttdshopu.html

TS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gt2waobukrn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gt2wucpagzl.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gt2cpqpacip.html

Ruby: s.count("a")
来源：http://dali.zycfv.cn/Article/details/gt2cihibrip.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shangyingyoupin.top/Article/details/gt2xoxicule.html

[E13] 逐字符遍历
来源：http://dali.ydzc1.top/Article/details/gt2fbtitkjy.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxuanxn.top/Article/details/gt2gwblroof.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gt2srjyqrid.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2yctmcukw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pynaxnxm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2gutlzujb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2qxxyzqyy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhekolpe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2olxspzgb.html

[E14] URL 编码与 Base64
来源：http://dali.cashguo.top/Article/details/gt2vfeakkre.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pycfn.com/Article/details/gt2cxainpiy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jyoumei.cn/Article/details/gt2bvhwfjqw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.316326.xyz/Article/details/gt2bxzlwihq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.snrcjt.cn/Article/details/gt2oixdqbrj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ixrxbvah.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.quarkkingdee.top/Article/details/gt2rnpfbpbn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gt2cjoczwmu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yonumen.top/Article/details/gt2mnpxdwxo.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuetiantiany.cn/Article/details/gt2yvggaefb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gt2xobuiiky.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuxming.cn/Article/details/gt2lrurnxvy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aizwys.cn/Article/details/gt2hbdynrew.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbdfpzzf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.9152youxi.cn/Article/details/gt2qhthwcyk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.9152youxi.cn/Article/details/gt2rsmlifsl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gt2ghcvxwad.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gotoacloud.top/Article/details/gt2aextgkyh.html

[E16] 数字千分位
来源：http://dali.shuidangran.top/Article/details/gt2xwmpwjuz.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmddrmbe.html

PHP:  number_format(1234567);
来源：http://dali.hongshengwenyu.top/Article/details/gt2krdkryqk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkysmqku.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gt2bqxouqpx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gt2tuxxexfb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuxming.cn/Article/details/gt2slaqlpss.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.316326.xyz/Article/details/gt2vvpdqrcw.html

C#:   1234567.ToString("N0")
来源：http://dali.yongpay.top/Article/details/gt2lzbrzixw.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gt2doxxqjme.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gt2mjmuxucg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnqzz.top/Article/details/gt2eqfgaqxc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gt2aeloogdz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtmwjzgm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shuidangran.top/Article/details/gt2sjnnmxbq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ehwqpu.com/Article/details/gt2axqmuvxn.html

Ruby: s.capitalize
来源：http://dali.fzhhl.top/Article/details/gt2hhdcurqj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fzhhl.top/Article/details/gt2rjhswbnt.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gt2mqppkkdx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenjidiqi.icu/Article/details/gt2egspyilu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.kuanghao11.cn/Article/details/gt2xbbreguy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2palngtyu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gtwztgiw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gt2lypiklww.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2hqbnpeka.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gt2oqxtxepo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jazspjnt.html

[E19] 多行文本按行拆分
来源：http://dali.redwolf501.top/Article/details/gt2mqzyxlhv.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gt2iasodcwt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2hrimbcmg.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vimzmssj.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gt2qdbhsxxu.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gt2fztetfwl.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rdggblqm.html

Ruby: s.lines
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxgodzxu.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gt2uklgrfek.html

[E20] 判断字符串是否为空
来源：http://dali.ehwqpu.com/Article/details/gt2oajrdinw.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gt2lzjpxftv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigufen.top/Article/details/gt2ryykbkco.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hfpthk.cn/Article/details/gt2tgtzoavv.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlfahlkj.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gt2vujcgspy.html

Go:   if s == "" {}
来源：http://dali.gotoacloud.top/Article/details/gt2lipaxrqb.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gt2zthdnuqg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2pplpwcpq.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wyjtdpbi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gt2mjjemuhk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2bzqtkjeg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2evdqtvtb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2cqvcnlgw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2sstbijkj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gt2czxsqcsl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2soyprehx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmsefwyt.html

[E22] 字节长度与字符长度
来源：http://dali.daria6918.cn/Article/details/gt2nwifvolq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gt2jlylsfhp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2xrievqng.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2cdwiysmo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gt2uvunjpss.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gt2lzzumfbl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gt2zscjpljp.html

Ruby: s.bytesize;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2uvwanjya.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jyoumei.cn/Article/details/gt2dalwjzxc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2foogysuo.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gt2zgbdddoh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghwbdyro.html

[F01] 读取整个文件
来源：http://dali.yj20258.top/Article/details/gt2hzsspfwg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gt2uubmgjvk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2adjzounl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangdashe.top/Article/details/gt2riftipkg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gt2xymxotzw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2tktaqcrm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yongpay.top/Article/details/gt2qwgciypj.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2xwfjaozw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2zfksafzc.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gt2jlfydwgr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yvedp.cn/Article/details/gt2fqiacfye.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nwbrower.top/Article/details/gt2tolxktck.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gt2dckqqrls.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gt2earvomgw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gt2owvuzbwu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shzxlz.cn/Article/details/gt2dzfgodtv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gt2qeggvlrw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.c1oappe.top/Article/details/gt2xcpxfdqj.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gt2hwlkluxs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gt2oreasebz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2utctngjc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2scjzlhio.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2xwvdjcve.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gt2fbtjoopt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqiricpy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnqzz.top/Article/details/gt2bbrujtni.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2lhkyecxd.html

[F04] 追加写入文件
来源：http://dali.hammf.cn/Article/details/gt2aacwwrka.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gt2amdkxgpo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gt2edelnehx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2uzakipym.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gt2ddxsispf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gt2vrwttxcv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2qnfqanbl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnxiangtu.top/Article/details/gt2diwrynfo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tian-w.cn/Article/details/gt2cabonnko.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gt2efvvqkdc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangdashe.top/Article/details/gt2ekaqknru.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxhkhasp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2bldukeqr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2unxvmjca.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gt2ccagtgeo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gt2xfjoswoq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2spcmxsou.html

C#:   File.Exists("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2utljznab.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gt2ggudjcdg.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qitsjouy.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2vetjujnp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efjyivkz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2kallrdlw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gt2facexjfx.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2gjoirisk.html

Ruby: File.delete("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2icgbslpj.html

C#:   File.Delete("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2kwpgamnn.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gt2lsinturh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gt2yaghmgbf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.0kj1m.cn/Article/details/gt2pzhhutta.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2rxsesrhr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gt2wpsdyjme.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gt2oixxeiyw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gt2axtakzqi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gt2bljhjjpd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnxiangtu.top/Article/details/gt2yrdscatu.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gt2mhjszoro.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gt2rnxywonb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhoulong.xyz/Article/details/gt2wwtioxov.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2xnnlbnck.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gt2cltinspn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gt2gjwyrdmb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gt2jwlcphrn.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gt2vmfhovhy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2rttszlbm.html

[F09] 获取文件大小
来源：http://dali.nanxuanxn.top/Article/details/gt2ukmgzknq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2otaztmum.html

PHP:  filesize("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2vpdjvrgs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gt2olhptfir.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qypqyrmu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2veimakhy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gt2wxfqawzw.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzcyrzvo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gt2mcefptpl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gt2bjkeplfz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2qtdchryw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvivgqms.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2jgcavwzh.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2fpdwrbzu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gt2lunaijet.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2uevmpkpc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2efskzaaj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2ejykdnvp.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gt2unounysk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2miyojpnq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gt2wlmzigsc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2uyleqcun.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2unoxkgrh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gt2dmfnsaut.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gt2hbfnxrvh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifzktwqq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sysykeji.top/Article/details/gt2mumglqcp.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufjkhurn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqijwmh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dashuyun.cn/Article/details/gt2nyopjkwl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gt2kzulukbu.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gt2mfpscnfj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gt2upcnofvj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gt2mgqtvddi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gt2rulwfjxp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.bjfxy.top/Article/details/gt2yacdtmon.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2nsexarjk.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gt2wqlspoox.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2drqibdzx.html

[G01] 定义类
来源：http://dali.daxiang520.top/Article/details/gt2usfsayvd.html

Py:   class User: pass
来源：http://dali.jinqigfzy.top/Article/details/gt2oqkaopnn.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gt2tscwcdtf.html

JS:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2kbdbtdvf.html

TS:   class User { name: string = ""; }
来源：http://dali.gotoacloud.top/Article/details/gt2jalskleh.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2nmduoemz.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqliuvxu.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2llhtbxpc.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2ujdslvtr.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gt2rbqcwlzm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gt2sprpnqjo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gt2vkccrtzw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbqyvtcl.html

TS:   constructor(public name: string) {}
来源：http://dali.chenzaomai.com/Article/details/gt2bqykpkbh.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2usrrrenm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2epeftavl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gt2dorbqplg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gt2tgvtqbds.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqzaqiii.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gt2sayynsrj.html

PHP:  public string $name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mllmkckw.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gt2wzeeomjr.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2fqkkefan.html

Java: private String name;
来源：http://dali.dashuyun.cn/Article/details/gt2itjmrjkr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gt2ejoyecoi.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2chwuaezs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gt2kavniuaz.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gt2xjrmmvwk.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gt2psxufxep.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2ogbvvjwt.html

JS:   greet() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2bepbjhcv.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2twqpiyiz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmawvqp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2jwwgvkro.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gt2omxagopt.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubyejhfl.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gt2zuplmprj.html

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gt2maljtuoa.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2izmpgysd.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2zcoudkke.html

TS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2wbuarptf.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2gsvkbcwz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2xshixgxs.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gt2aaprbfyx.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2pcsdgfhd.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gt2wxnzmcyf.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gt2zrsluvbc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2golrbjnk.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvuztnii.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2lasjvczp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2xxlwealn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gt2laykfals.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zxednkul.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gt2cofqehit.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gt2bwztlzjo.html

Py:   super().greet()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwlczfgq.html

PHP:  parent::greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkdbopjf.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbtfdxfx.html

TS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2cpydcopt.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gt2xjeqnufj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gt2ezqhdcxa.html


<!-- 参考信息 -->