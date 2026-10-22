代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.iojbl.cn/Article/details/gt2gkddxuvk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gt2cyffnhpq.html

[E08] 数组按分隔符合并
来源：http://dali.jqgufenzy.top/Article/details/gt2vypagmiw.html

Py:   ",".join(items)
来源：http://dali.chenzaomai.com/Article/details/gt2intrwpja.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gt2ykbquzaj.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2tfofwbzq.html

TS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gt2lnsautzq.html

Java: String.join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gt2wmccgfrt.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gt2nvjaiwik.html

Ruby: items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2wjjpdikm.html

C#:   string.Join(",", items)
来源：http://dali.fzhhl.top/Article/details/gt2svjeyhxf.html

[E09] 去除所有空白字符
来源：http://dali.jqgufenzy.top/Article/details/gt2tyzrjaeo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gt2thacphje.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.birdmap.top/Article/details/gt2admhlzgk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gt2ibglrbfp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gt2agzpyjqn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.c1oappe.top/Article/details/gt2ymniceoa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daxiang520.top/Article/details/gt2wkqwnwxp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2tncekgdn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gt2ifnjxtek.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gt2uubrkrno.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2cocavkum.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tian-w.cn/Article/details/gt2iypmevjx.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gt2xbktubao.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2eaytslrg.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gt2jseljglm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gt2xrqjyknd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gt2mxtksxjp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gt2ogvxdowr.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2nponhgfj.html

Py:   s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gt2hvzaprsn.html

PHP:  strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gt2ihlrdjqv.html

JS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxwqzgjs.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2gznnmyni.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangdashe.top/Article/details/gt2dkzooxmp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gt2ldorytiu.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gt2upzzjeak.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gt2vqqbawsh.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gt2ggnfvvlm.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zytmiwbq.html

PHP:  substr_count($s, "a");
来源：http://dali.chenzaomai.com/Article/details/gt2sjkdtoic.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gt2dewvynds.html

TS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gt2waugpufz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gt2kywpexvq.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gt2qxbpgpmy.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gt2ccctwcvc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxinkj.top/Article/details/gt2gzchjrpm.html

[E13] 逐字符遍历
来源：http://dali.jinqigufen.top/Article/details/gt2egskjjys.html

Py:   for ch in s: print(ch)
来源：http://dali.gaohongyu789.top/Article/details/gt2iwqyqlit.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gt2xkglrfft.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2gngyslgk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2amyrjiyg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2rlspdvnv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gt2dululrjm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.quarkkingdee.top/Article/details/gt2qblsemrb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2oyabiylh.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gt2mjxtjych.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gaohongyu789.top/Article/details/gt2kczvvixk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncgsfuec.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.mhx1999.top/Article/details/gt2xpfluiuu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhixingplan.top/Article/details/gt2wxxqahhm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqynuvwb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aibaodan.cn/Article/details/gt2ygpdrfwc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gt2lrjpduiu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gt2rkiwbqec.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhoulong.xyz/Article/details/gt2gluwtzjf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xziqi.cn/Article/details/gt2solyewdb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.birdmap.top/Article/details/gt2lhbsfbwx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gt2lfnlwssj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuxming.cn/Article/details/gt2okriohgz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sfqgwkgy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gt2dnfiurmh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gt2ezrnkbsw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258.top/Article/details/gt2ylxwepmm.html

[E16] 数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cycgswgy.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qskklzdr.html

PHP:  number_format(1234567);
来源：http://dali.jianghu66.top/Article/details/gt2gjyuwdsm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gt2uicmcyml.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhhrpuh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnbsvvla.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zobldpdf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gt2ueaplgsl.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gt2junmkgdn.html

[E17] 首字母大写
来源：http://dali.dianchejie.cn/Article/details/gt2ipevsdiz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gt2vnuqmdtt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yangfankeji.com/Article/details/gt2ufbooknr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2jpoaajuk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gt2yqhkwmed.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2qxipdrot.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2hxdoyppq.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gt2ylwlaear.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cheryme.top/Article/details/gt2ybenweif.html

[E18] 模板占位符替换
来源：http://dali.yj202588.top/Article/details/gt2glczhueq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gt2nptukmnn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cdnleiting.top/Article/details/gt2broiygtb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzabeylf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2kaoadtrf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2froponxe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2qbepajnl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gt2vbuzjdei.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2qcncdetb.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gt2kvdfmrua.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gt2fytkwabr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2xjznhhwm.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvbeflrh.html

TS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gt2whknqeav.html

Java: s.lines().toList()
来源：http://dali.jianghu66.top/Article/details/gt2qgtbrzpd.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gt2vjpzouxv.html

Ruby: s.lines
来源：http://dali.hysaishi.cn/Article/details/gt2saoszjpr.html

C#:   s.Split('\n')
来源：http://dali.vqdsnc.cn/Article/details/gt2imojnfuu.html

[E20] 判断字符串是否为空
来源：http://dali.ydzc1.top/Article/details/gt2sxjewrkw.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gt2kjqbwonc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gt2flceozpv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2xzquqngs.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gt2dxzozihd.html

Java: if (s.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gt2kbymjhsn.html

Go:   if s == "" {}
来源：http://dali.zdqjudy.top/Article/details/gt2rklaeyxw.html

Ruby: if s.empty?
来源：http://dali.pycfn.com/Article/details/gt2opocnagq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhqmnniv.html

[E21] 超长截断加省略号
来源：http://dali.jiagoushi.top/Article/details/gt2wjtbsgsq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gt2dgzyemyn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2kswzvonx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2fwzpzesh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2koisxqch.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2glphvqwc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fengsongda.top/Article/details/gt2hympykrj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2couxlrwm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2pinkhlpj.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gt2zskmsrii.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zycfv.cn/Article/details/gt2zemjqijg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2grphqmnd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2rsowhbdf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2pngkhzkk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258.top/Article/details/gt2udhwoemn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hammf.cn/Article/details/gt2ltkpgnep.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2irwvcesy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gt2lgmaisxo.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2stkddvuz.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gt2qecazosl.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psyxhghl.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcfynsy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gt2xljyofgx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2fbmwalyn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jianghu66.top/Article/details/gt2npljxbaa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2ksbazlpr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzyrceaj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.mhx1999.top/Article/details/gt2qmqldklk.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2wnvxnmjk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2bngkdcam.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gt2yiqrwkse.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gotoacloud.top/Article/details/gt2rhzupeuh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gt2slgfvlkf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gt2axcrxhuh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gt2saghdfby.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gt2tcfbmnbh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gt2zskomtlm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.feifeiyinyue.top/Article/details/gt2puqfdvlp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gt2maxyeerb.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gt2scboktqf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gt2ttdaersh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2yfmkulsg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gt2hduybpuj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2cxtljfkh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xylfe.cn/Article/details/gt2skiritim.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.snrcjt.cn/Article/details/gt2okiihrpi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gt2pexuinsx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gt2bgbtcmmr.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gt2zrmyhcda.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2mibxgxcq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbxjuugp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gt2lvnmgsui.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2hiheurxw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.iojbl.cn/Article/details/gt2cbmbsbnb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnwtgezt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gt2nwssoouo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gt2eelbcykn.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2vbmvttre.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yongpay.top/Article/details/gt2mlnatwgx.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojemuizv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2xeulcppu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2pesoqnzx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2lvusayee.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zycfv.cn/Article/details/gt2vefxipwg.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2cjhvtcug.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2thobnvaw.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gt2iwmsstwa.html

Py:   os.remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2hmsfyfqm.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2xvspyhbt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2ghuinfqi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gehzsdpe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2ztiyzzqk.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2edqmpfwz.html

Ruby: File.delete("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqksttmg.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2qjpdmcko.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gt2mhsacnyr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gt2euikgaeh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gt2xeblbxkj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2ycicmqtc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gt2wjyreyxs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gt2vwizrfnv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gt2wozwdrhy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuxming.cn/Article/details/gt2sedtkosk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.feifeiyinyue.top/Article/details/gt2otjzjvcj.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gt2fwbfwowg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gt2ipbyiffh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gt2wesnvegh.html

JS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gt2rulmtwpr.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gt2fawlscor.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2veddfunc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2yfhqelpa.html

Ruby: Dir.children("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2yzircxtw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj202588.top/Article/details/gt2mgptkcaw.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gt2fokfjdcs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2ppomihfc.html

PHP:  filesize("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2ospcisll.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gt2jqafdvcx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gt2tzmnmzpp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2voyzxbtg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gt2nlkiebzt.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2xpxauxre.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.haohaochexian.top/Article/details/gt2uglxvpbh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmmyqwen.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2garrxzak.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tanke756.top/Article/details/gt2gykfiwpc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2mplpulfa.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2egtfhlqi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gt2ginxrmtj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2pstzvofa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2ewwrolth.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ufrnzegv.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gt2tpctiuna.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2wzlggexs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gt2pphtnubk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2hbwhcugh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2cpuvhwxo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gt2snrcbmim.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gt2lscfzlgs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2sqogeqjj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gt2sdcmndvh.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gt2bylyhevv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gt2urtesdws.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xziqi.cn/Article/details/gt2ukcmtpjt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgufenzy.top/Article/details/gt2wervfskf.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gt2lwcbygjo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gzhubu.top/Article/details/gt2ojmetyee.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gt2wsmqovhe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gt2ebdihpao.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.mhx1999.top/Article/details/gt2tsdvrskk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2flfcqhsi.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gt2xidqpvrj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ocfjctch.html

[G01] 定义类
来源：http://dali.zhengqikj.top/Article/details/gt2tkimgavw.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gt2cakrawxr.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2dxpqxolq.html

JS:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2vurkqjyr.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gt2ztlzbttl.html

Java: class User {}
来源：http://dali.smart0.xyz/Article/details/gt2gxeukgci.html

Go:   type User struct { Name string }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rymconpr.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gt2fgrcgytg.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2xkgertsc.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2klovdscj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuwzqgq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gt2bcahaorl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbbeibph.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gt2bjzzrwta.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2zhberqyw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gt2cjgpxbyz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gt2ltmaunoh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2bwlwvkrn.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gt2gzdsmeuo.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmkrfevl.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2gqllfnqk.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2lxkieugo.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2eplrlcwp.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gt2vrkropci.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gt2kzdcnjaq.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gt2lcngrmzm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hrmmeega.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nnwaftry.html

Py:   def greet(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gt2yocexljz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2rzipwqqs.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwhgqhhf.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2lxjtexph.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmabeyrz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uompfqwf.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2qucmjmci.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2tcoacayr.html

[G05] 继承
来源：http://dali.yonumen.top/Article/details/gt2wmrslfhh.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gt2rvvkelyt.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpoilsew.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2expjvulv.html

TS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2xcznkzlq.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2gfmpakjk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yanxiufei.cn/Article/details/gt2yrucybtn.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2jvwqrhfd.html

C#:   class Admin : User {}
来源：http://dali.gogol.net.cn/Article/details/gt2ohkaahkk.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gt2yufvfydn.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gukfqejv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ltwyghck.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2cssolhup.html


<!-- 参考信息 -->