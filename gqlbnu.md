代发 wailian999

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gtxdpmbjnk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gtelisuyjq.html

TS:   s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtbzbtqmha.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtrweinhza.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gtjcsckyvo.html

Ruby: s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtyiidurao.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtobskjfxk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxinkj.top/Article/details/gtzajttaxs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.andypj.xyz/Article/details/gtsairiltw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgufenzy.top/Article/details/gtxjnoiden.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtykkktnby.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtpsjahief.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtksvbqkfq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xziqi.cn/Article/details/gthjwzpccy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cdnleiting.top/Article/details/gtnpnbtqen.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtxyhuepyu.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gtvngwijvc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtljgwnmaj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gtdjvfhcoo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtfbtjdiie.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtqxohqagc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtgpjtchpn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtbhpvkrod.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtpykmqwvp.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtpzppdyjg.html

[E07] 按分隔符拆分
来源：http://dali.aibaodan.cn/Article/details/gteqvghlbk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guannengcc.top/Article/details/gtrcukqdag.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtzhpeejlr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtexpkwtiw.html

TS:   s.split(",")
来源：http://dali.hywenlv.cn/Article/details/gtuegvxpby.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gtzilozoyy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sweek.top/Article/details/gtktfyaoia.html

Ruby: s.split(",");  s.split
来源：http://dali.zhongyouzk.top/Article/details/gtdoypvgvc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yanxiufei.cn/Article/details/gttdxeiadj.html

[E08] 数组按分隔符合并
来源：http://dali.xylfe.cn/Article/details/gtqjlfukps.html

Py:   ",".join(items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxaqbdjom.html

PHP:  implode(",", $items);
来源：http://dali.pengpengdd.cyou/Article/details/gthheekndd.html

JS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtbuloldjd.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtgyxeedlw.html

Java: String.join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtapeegbmz.html

Go:   strings.Join(items, ",")
来源：http://dali.yangfankeji.com/Article/details/gtvnavglea.html

Ruby: items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtbukbpits.html

C#:   string.Join(",", items)
来源：http://dali.daria6918.cn/Article/details/gtmbrxvecw.html

[E09] 去除所有空白字符
来源：http://dali.zhengqikj.top/Article/details/gtrgdnjgdw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gtrnoewtew.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrksfdscz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gtkilcpxto.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtmceusmul.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gtxppdcsgv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcbvmqje.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkddjofq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gtgtyhyeos.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtqykybsra.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258.top/Article/details/gtnpdrapex.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sweek.top/Article/details/gtnnvxrsmp.html

JS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtygzrlsbo.html

TS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtshktqiru.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtdyknhfpf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtuxloyhzp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtfwmfjmdg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtivehacwn.html

[E11] 反转字符串
来源：http://dali.wangdashe.top/Article/details/gtuxeezolk.html

Py:   s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gtpbyufnwu.html

PHP:  strrev($s);
来源：http://dali.yuxming.cn/Article/details/gtxsqkgvhm.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkedyflze.html

TS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtbyznusbc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sweek.top/Article/details/gtttixcfot.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhixingplan.top/Article/details/gthoydjriq.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxohiwsv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtwtyvsijg.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gtwufnywea.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtzmshsktg.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxzpwcza.html

JS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtaedykckw.html

TS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gtdlkoibpd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gttjqjdujm.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gtzxhonfpx.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gtpginwhxq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gtvybnncnq.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gtbhedrnvk.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxinkj.top/Article/details/gtxiufiytk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258.top/Article/details/gthcpleeze.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtruhqjmpc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwrjjyctz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cheryme.top/Article/details/gtdkirdkpe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.havefunace.top/Article/details/gtavxdeivd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgufenzy.top/Article/details/gtpxhnfthk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gtechwowyf.html

[E14] URL 编码与 Base64
来源：http://dali.316326.xyz/Article/details/gtvxtcufme.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gtofdznzqr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gtbahzuzob.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258888.top/Article/details/gtbbrnlccp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ehwqpu.com/Article/details/gtcnpljebu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtqkhansfl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnqzz.top/Article/details/gtshietuwi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fzhhl.top/Article/details/gtkbpcsdmd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtyeafoszb.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gtlsitcmkf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gttqlcliik.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotwmclnj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenlongwang.top/Article/details/gthxpgkxjd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.haohaochexian.top/Article/details/gtuzphpclj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gtimgpoxpv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gtgfidusbd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtxhdgasvp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gtitwgdfho.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gtpqsfwulp.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gtwsmkqbzy.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gtdwzjzmdk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtyyivllhb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtasgardjw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gtemhyhxal.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gtjwufxnnj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gtvtjzxjes.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkzuhhdu.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gtyoetxlqg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gtkgfszfqv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gtvvprkiyr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtzoxjseek.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtibzzsgjk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtwqpnzzej.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daxiang520.top/Article/details/gtczlphmiq.html

Ruby: s.capitalize
来源：http://dali.redwolf501.top/Article/details/gtmcvrlpmb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuanzhike.top/Article/details/gtwsqumxbf.html

[E18] 模板占位符替换
来源：http://dali.yangfankeji.com/Article/details/gtzundtshi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbapyhsun.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gtepyoqoky.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaiigbobq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpildtove.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtzyomffce.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtotrpzify.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gticgkwocy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.316326.xyz/Article/details/gtoxdrxcmt.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gtatifihvt.html

Py:   s.splitlines()
来源：http://dali.hongshengwenyu.top/Article/details/gtuhtvsgtm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtodznarud.html

JS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gtcnqrpwul.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtwtkyeexh.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtzomsjwuu.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtjjemvtwd.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gtcrpwyklk.html

C#:   s.Split('\n')
来源：http://dali.wangshuangyany.cn/Article/details/gtscjngjwx.html

[E20] 判断字符串是否为空
来源：http://dali.xylfe.cn/Article/details/gtkkngxchr.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gtndcbjqpt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.9152youxi.cn/Article/details/gtxapwqinu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gaohongyu789.top/Article/details/gtpxbagnjp.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gtbhnieprm.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjgqhotue.html

Go:   if s == "" {}
来源：http://dali.daxiang520.top/Article/details/gtrgbzcnoo.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gtmaaexoyf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gttgmcnfzj.html

[E21] 超长截断加省略号
来源：http://dali.vqdsnc.cn/Article/details/gtztldskkk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gtkbosxxpx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtoozqyaep.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtblevmxic.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtiyvbpyex.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtmyljshqc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gtewmekoib.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtvffzuntt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtmvdotyss.html

[E22] 字节长度与字符长度
来源：http://dali.shangyingyoupin.top/Article/details/gtejhwtxbd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gtomoswomz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtmbisimyq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtmktxqssa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gtvasncldk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gtkdhaewdq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gtrczgewcq.html

Ruby: s.bytesize;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtpnfudcvz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzorkbxr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtkkdthded.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gtqoftvpyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtdtapksmu.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gtloqztkgk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gtgwlrzqwv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtjrerlfpe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gzhubu.top/Article/details/gtvvhuybep.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj202588.top/Article/details/gteqxyezaf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gttqkiswdb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gtcnjrzibr.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtmwwblqye.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtcazipmnp.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gtycickjjt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpgowmyk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xylfe.cn/Article/details/gttnqagfzh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtvsoayxzx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtzcalvdau.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtgkegpget.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gtlhgixebb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gtlnoytccd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxltfxpxn.html

[F03] 写入文件（覆盖）
来源：http://dali.chenjidiqi.icu/Article/details/gtzclbcreq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cheryme.top/Article/details/gtxtbajkys.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtixbektgh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtmvuhkcfz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gteezysdcu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gtnmxjeeyq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gtuhmsyhre.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gtgupmafzm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtmlfaeiyl.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gtzynjfeat.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtngwvftbn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtzmsbvuji.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gttugxcxjj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtbdeagyly.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gtdrfnbqcm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gogol.net.cn/Article/details/gtxnbzfjwp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daria6918.cn/Article/details/gthbtsxawp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbhmdjqf.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtrqgzufxx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gtdbighnno.html

PHP:  file_exists("a.txt");
来源：http://dali.sweek.top/Article/details/gtlureromx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtjyhxhlcr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtzavqngxe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtpodjkxwl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gtgshwkkcp.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gteviddptc.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtnkdadssa.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gtswjwinet.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtkizxhzzz.html

PHP:  unlink("a.txt");
来源：http://dali.yonumen.top/Article/details/gtktagwnsm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtepnpntmx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtdpbjjixy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtmyyqbcsn.html

Go:   os.Remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtymnclfgo.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtaiokmqzk.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gthrvenfiq.html

[F07] 创建目录（含多级）
来源：http://dali.jqgufenzy.top/Article/details/gtqzimrjzv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtadsdzthv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gtcweyvyzw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtfxhqoebb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoezbtmu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gtijjuwhkw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gteclasgcj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gtrawbywtd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenzaomai.com/Article/details/gtdtoeivnw.html

[F08] 遍历目录
来源：http://dali.hywenlv.cn/Article/details/gtdqusgisn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gtvbeqdlgs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cucudq.cn/Article/details/gthpcglxjy.html

JS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtwvrwuhzt.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtyspthufc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtwwunrgro.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gtgmcowecu.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gtvtkzynbf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtutfthury.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gtlqlogzyx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtglijbhug.html

PHP:  filesize("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtrdtefhwv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtrqqrpbph.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtrtwibdpl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtpkcfakwx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gtijmfphip.html

Ruby: File.size("a.txt")
来源：http://dali.cashguo.top/Article/details/gtncdnusmn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gtcpgsmseh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gtofgwsrpr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtcpcxulwb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtfcqvpzsz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtigaraldr.html

TS:   path.extname("a.txt")
来源：http://dali.daxiang520.top/Article/details/gturozlkgb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gtlmodxvli.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtqbttadtt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtchtzpxhm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtenwazyml.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gtvicopffc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtjrcjowbb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnqzz.top/Article/details/gtkyajsihw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtwhpuubmx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gttdrspkzz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtfwuryowf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gtdxqkydxa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtkkbcnmxq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.andypj.xyz/Article/details/gtlpymqnzo.html

[F12] CSV 读写
来源：http://dali.zhiwuduotai.top/Article/details/gtvqckapic.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gtynmchqrq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gtjbfbwybc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gttfhcjjui.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gtkiqswzjo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.vqdsnc.cn/Article/details/gtfywnsvwk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtcdkgymuo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gzhubu.top/Article/details/gtavikqrwh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yueranfly.top/Article/details/gtegeaskla.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthpjiuzzn.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gtichibyfp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtpjzlzkxv.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gtvyccstzm.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtarhedfwr.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gthfrghzjh.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtxbcebfnd.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gtcbgfjcsm.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gtsvuchjqp.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gtklnfktgn.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gtyilnyawm.html

C#:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtgloleloi.html

[G02] 构造函数
来源：http://dali.hfpthk.cn/Article/details/gtwwdxoqbl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gtorwpcdgw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gtdndsijba.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtlwykoiuq.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gtdszaaavf.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gttdsanqrn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jyoumei.cn/Article/details/gtwemapwpi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gtddvuwjoh.html


<!-- 参考信息 -->