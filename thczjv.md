代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gt2qmqnlzly.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.haohaochexian.top/Article/details/gt2ajpvmhrw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivcfyezv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258.top/Article/details/gt2eyxqfccn.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gt2cubscguh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gt2qwjibzym.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.birdmap.top/Article/details/gt2rgfrocyo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2alinxsun.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2ppbgdnvp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2wcvckest.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yonumen.top/Article/details/gt2ffriflrt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gt2rklzvxyg.html

C#:   s.Replace("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2viqtrdgy.html

[E07] 按分隔符拆分
来源：http://dali.yonumen.top/Article/details/gt2adtkcpyw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ivvv.top/Article/details/gt2itmiqexz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2irtluysf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gt2wxpezuig.html

TS:   s.split(",")
来源：http://dali.yueranfly.top/Article/details/gt2czgxyrha.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guannengcc.top/Article/details/gt2ljilnuwa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.snrcjt.cn/Article/details/gt2myxglxti.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gt2zfxcejcl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ounjafpc.html

[E08] 数组按分隔符合并
来源：http://dali.andypj.xyz/Article/details/gt2qrvwjgqq.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gt2vcwcallw.html

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gt2hrjfaxim.html

JS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2jfljqdot.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gt2xvbzplvu.html

Java: String.join(",", items)
来源：http://dali.havefunace.top/Article/details/gt2rxyeodmp.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gt2thiqivfo.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2mzwinqrm.html

C#:   string.Join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gt2zmelryuz.html

[E09] 去除所有空白字符
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uohlvxfj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tian-w.cn/Article/details/gt2azbkwtzi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2waqgsqen.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxllmwfx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2zdutqxos.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiswudx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnqzz.top/Article/details/gt2pysgqrjy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gt2daawcqel.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gt2ocefspyv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uihykzak.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2gtjphcge.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcufsabn.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2opyaflwv.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gt2legpxcqa.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gt2yiwymivl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gt2acceteba.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2nethgxcj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yanxiufei.cn/Article/details/gt2zxoyztjn.html

[E11] 反转字符串
来源：http://dali.havefunace.top/Article/details/gt2fexyullc.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gt2gslqsuyz.html

PHP:  strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gt2xxhizugw.html

JS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2qlvaqbsa.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2luklfpeb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gt2gpvvhfpo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gt2vgiarnou.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gt2nnfedppp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gt2mhyomdbe.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gt2geqbssls.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gt2hjwvwaan.html

PHP:  substr_count($s, "a");
来源：http://dali.snrcjt.cn/Article/details/gt2wbwskjpv.html

JS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gt2bsooexxk.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gt2pgbxjkyq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gt2hzjkdiwv.html

Go:   strings.Count(s, "a")
来源：http://dali.tanke756.top/Article/details/gt2bnkpfycj.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gt2fhaoknyj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gt2sctekxgh.html

[E13] 逐字符遍历
来源：http://dali.zhixingplan.top/Article/details/gt2fsqncost.html

Py:   for ch in s: print(ch)
来源：http://dali.mhx1999.top/Article/details/gt2bwrrcvhr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gt2wnwaqatz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2yuyzqrnt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2brwpysli.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2tdnzxffp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sweek.top/Article/details/gt2krlxetwf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gt2jzdghhdp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2qdhckmvx.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xypdjdkp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jyoumei.cn/Article/details/gt2krcazldv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cashguo.top/Article/details/gt2qtoekxmi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flrzygrd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yangfankeji.com/Article/details/gt2aloakuxw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sweek.top/Article/details/gt2sdpfedud.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gt2bbaeuqry.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.snrcjt.cn/Article/details/gt2inxjurux.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gt2cydjlpat.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuanzx.com/Article/details/gt2ycjpixwm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dashuyun.cn/Article/details/gt2vgspclyw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yvedp.cn/Article/details/gt2sjecrrhh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gt2gsmebrkn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gt2twnfkaex.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258888.top/Article/details/gt2yhgrhhyv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2phaxsixe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rgsalnjy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gt2rnzqkaot.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gt2athovmau.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gt2wzrdnpvn.html

PHP:  number_format(1234567);
来源：http://dali.vqdsnc.cn/Article/details/gt2zbfgdlzh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gt2cisbiqbg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qseyqcpg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gt2vfcddbxj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shzxlz.cn/Article/details/gt2gqpftrdg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258.top/Article/details/gt2tlchlnbp.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujvzukud.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gt2vakaxnty.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cheryme.top/Article/details/gt2ubknqpdn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gt2djqdltex.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gt2idqwtzmb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gt2pgjgvkvh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gt2vtuvvaxv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gt2bbulglfw.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gt2nlgvdonm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shuidangran.top/Article/details/gt2ebupsvgk.html

[E18] 模板占位符替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ideyhfcd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzynljga.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dashuyun.cn/Article/details/gt2rpxelleb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2wtqlakmh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2objdiakk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2qaeirbin.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2ollhiwfy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yanxiufei.cn/Article/details/gt2esrxqhri.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnqajfus.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gt2cbitbpyt.html

Py:   s.splitlines()
来源：http://dali.zhengqikj.top/Article/details/gt2rayyirnk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2feodcuds.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gt2qudcwsdg.html

TS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gt2dlxhzfbc.html

Java: s.lines().toList()
来源：http://dali.yj202588.top/Article/details/gt2yeotsprq.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnqzz.top/Article/details/gt2dpfzhqsl.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gt2jeovcize.html

C#:   s.Split('\n')
来源：http://dali.fzhhl.top/Article/details/gt2dkiyofam.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gt2danmmoax.html

Py:   if not s:
来源：http://dali.daxiang520.top/Article/details/gt2fwpzhvsx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gt2lriwofra.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gt2foyrjhrc.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gt2xmutecbu.html

Java: if (s.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2zoqsvjwj.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gt2ryscjysr.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eaiosula.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daxiang520.top/Article/details/gt2nznsdlrn.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gt2dizeixyt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yanxiufei.cn/Article/details/gt2pfqtuhta.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2xxodjzoy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2nueolyft.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2xotwkxfr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2hucrxore.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fzhhl.top/Article/details/gt2mfwjhaxu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2czgizgwa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2plkrbvvj.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gt2lyzynoik.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnqzz.top/Article/details/gt2blftwjgd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2fprconle.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2ssvvfwex.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2pscecsfy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gt2rhlvatfs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2usnjeqhz.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2smddhvnw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.0kj1m.cn/Article/details/gt2bxerondg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2sgnyaxys.html

F. 文件与目录
来源：http://dali.shzxlz.cn/Article/details/gt2fxannucr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2dnuohfzh.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gt2clqvtpsn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aizwys.cn/Article/details/gt2scfselkj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2gyfxxtrr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhujscdu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2pjoxdjuh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2oqaoneut.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sufxvd.cn/Article/details/gt2ssamorff.html

Ruby: File.read("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2qfcetrfv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2uyszotbi.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gt2ubhjmpsy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258.top/Article/details/gt2wgrposfc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ppjwa.cn/Article/details/gt2vyazjrtw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gt2zpytclbp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmgxnpnw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gt2asfelwca.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.quarkkingdee.top/Article/details/gt2lfyolwjj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gt2ytrqfoah.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.redwolf501.top/Article/details/gt2jbavmuxw.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gt2ejrtfcrp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigufen.top/Article/details/gt2jkxatshz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gt2sbqmlwzw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gt2bqedcwmr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2yumwpzbv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwfrpyq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gt2ivgkiqdc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2btiwioyd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gt2rskockyy.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gt2gxwqfkte.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jglnbuzo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tianlin.xyz/Article/details/gt2skuyfooj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gt2ozjbvefn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2eitudwgg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xziqi.cn/Article/details/gt2mzvzgnfe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2dissjzqg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gt2ikflwner.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.feifeiyinyue.top/Article/details/gt2jsdhjamk.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnqzz.top/Article/details/gt2omseksot.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gt2jiheyqyl.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2pmwkvjfj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2ifwcjupv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2algibeww.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2pkvdsysv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gt2frzoszqs.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2zawphazo.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2qmemfnrd.html

[F06] 删除文件
来源：http://dali.c1oappe.top/Article/details/gt2ahbanvvv.html

Py:   os.remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2puzscguo.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2djwytwqg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2jwewaddx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2awcijddf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2afpomgsj.html

Go:   os.Remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2gusdyoca.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2dgwgvbtu.html

C#:   File.Delete("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2qselgdng.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vufeynac.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gt2uqzruelz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hysaishi.cn/Article/details/gt2vklcbgfc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gt2wmnrcouy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gt2fhqvumkk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuxming.cn/Article/details/gt2fuzkjhoy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gt2gbmcelwj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gt2bvmnlgdu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbjjxklh.html

[F08] 遍历目录
来源：http://dali.guowangkeji.top/Article/details/gt2giimykhr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gt2gldzllwn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gt2zmbybfri.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gt2bvgvrycr.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gt2zyknmccc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gt2sqccokaj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daria6918.cn/Article/details/gt2tfldqpmq.html

Ruby: Dir.children("dir")
来源：http://dali.yongpay.top/Article/details/gt2gspfjfsx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gt2mbgwlsif.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gt2ancwsjgw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2rjvhexrg.html

PHP:  filesize("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2tvrhunkx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gt2uajgbczn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gt2bolcmbuw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2iiivhnry.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gt2supwsqbk.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2rwmydyfc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yonumen.top/Article/details/gt2jtnjfjuc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gt2ngtsddpa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2iubcmlwp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2tvijbslh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2zkacvtdh.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2knfiaffx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gt2kxopquxz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cqqkekbf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2fokqdvmn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2obcdznzl.html

[F11] 复制与移动文件
来源：http://dali.c1oappe.top/Article/details/gt2gmrssrtf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2cpzrnxsi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qzmubqip.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2djszjphp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2vtjblkvb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2qyrplyof.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.feifeiyinyue.top/Article/details/gt2vlsqdrfj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2vqhlxisr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2enjlredr.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gt2ecwhfwyu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gt2bmedsmus.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gt2vbboqzpv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yueranfly.top/Article/details/gt2hcioptee.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gt2hwixocib.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gt2wsobchrt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gt2stpfjlqn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gt2zggcyrha.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xyckdoqi.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2nfenntpi.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gt2siilycez.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ruelrszs.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gt2hdodxpyj.html

Py:   class User: pass
来源：http://dali.guannengcc.top/Article/details/gt2djozmpsr.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gt2wjdmmcls.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2akfivjrt.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vfmcxhqm.html

Java: class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2jxlqyxct.html

Go:   type User struct { Name string }
来源：http://dali.gotoacloud.top/Article/details/gt2xujnehtq.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gt2dvirpotf.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2laglusav.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gt2mbezseds.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gt2xhqmvfzk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ybcxt.top/Article/details/gt2dlaugtpx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tbnpljns.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gt2arzqbdtt.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2olbqyrjm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ybcxt.top/Article/details/gt2tovbgqzk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2qlvkwqcc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gt2hkfleyvu.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gt2noqsyguj.html

Py:   self.name = "x"
来源：http://dali.xinyue.icu/Article/details/gt2yrjcxpfi.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2nsnjvdre.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2fkbdzxjv.html

TS:   name: string = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2reiadqdu.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gt2pdunzyyw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gt2gxhmgktp.html

Ruby: @name = "x"
来源：http://dali.cashguo.top/Article/details/gt2bcnhimew.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2fwqjyqxl.html

[G04] 定义方法
来源：http://dali.jinqigfzy.top/Article/details/gt2gnraucxn.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gt2zjnjmvmw.html


<!-- 参考信息 -->