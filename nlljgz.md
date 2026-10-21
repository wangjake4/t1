代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ybcxt.top/Article/details/gtesxqimqh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hammf.cn/Article/details/gtgnyexlwh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.snrcjt.cn/Article/details/gtktnzlsxc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.havefunace.top/Article/details/gtsjdtwjhf.html

[E02] 重复字符串
来源：http://dali.hysaishi.cn/Article/details/gtbzluboxz.html

Py:   "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gtwgzuzhii.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzkyzukm.html

JS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gthcjnrvfw.html

TS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmahwalw.html

Java: "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtebqbalpq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhoulong.xyz/Article/details/gtrmkhejdd.html

Ruby: "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtnqfqkbmf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cheryme.top/Article/details/gtrpawzdkz.html

[E03] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtklqvneiq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnxiangtu.top/Article/details/gtatiwyjrz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtgpipbfwq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtkyppmdug.html

TS:   s.slice(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtnrzlhpjh.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtyylxaego.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gtrcvqmdff.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ehwqpu.com/Article/details/gtdvicajgk.html

C#:   s.Substring(1, 3)
来源：http://dali.xylfe.cn/Article/details/gtklfvbrpy.html

[E04] 查找子串位置
来源：http://dali.fzhhl.top/Article/details/gtlsivqhuy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gtnwyjcklf.html

PHP:  strpos($s, "x");
来源：http://dali.yonumen.top/Article/details/gtgqdjgnhx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ivvv.top/Article/details/gtxrxwiagy.html

TS:   s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gtktqcgzun.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsyfmron.html

Go:   strings.Index(s, "x")
来源：http://dali.ivvv.top/Article/details/gttyviseop.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtuqwkxusx.html

C#:   s.IndexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtnjifwizt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cashguo.top/Article/details/gtzkcclivu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtadwhbbcd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnxiangtu.top/Article/details/gtngelyhws.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtupwoprfc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ybcxt.top/Article/details/gtxiwwjcxl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtyyjuwqpm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhongyouzk.top/Article/details/gtyslbmsmd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gtnpctkwqv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtuyjkjqvw.html

[E06] 替换子串
来源：http://dali.yvedp.cn/Article/details/gtfbxkmqii.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gteigbushd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gotoacloud.top/Article/details/gtmflhrebh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtihctkphd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtfbgooorp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtkvsjbvcf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gtbvicbwzk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtsrjgrgwt.html

C#:   s.Replace("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtztjpuctg.html

[E07] 按分隔符拆分
来源：http://dali.daxiang520.top/Article/details/gtlbyssmzx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gtdtxdafbd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jianghu66.top/Article/details/gtvzihtbcd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gtfofdszpo.html

TS:   s.split(",")
来源：http://dali.sufxvd.cn/Article/details/gtgdiazerc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yueranfly.top/Article/details/gtaubgqyvk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtswjxnpmf.html

Ruby: s.split(",");  s.split
来源：http://dali.mhx1999.top/Article/details/gtdytsdruo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258.top/Article/details/gtlacciviu.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gtkwprjcyx.html

Py:   ",".join(items)
来源：http://dali.yuanzhike.top/Article/details/gtxtvsabhz.html

PHP:  implode(",", $items);
来源：http://dali.aibaodan.cn/Article/details/gtgpcotcma.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtqpyugseo.html

TS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtlithtamw.html

Java: String.join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtihlhbjxf.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gtlroktrnb.html

Ruby: items.join(",")
来源：http://dali.316326.xyz/Article/details/gtdjjhjcae.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtthnmdohp.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gtkkdmbtvv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gtuinfzyqv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cheryme.top/Article/details/gtxdtlwyzu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtawkfojka.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtrhhhkvvc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtofvjwidi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ppjwa.cn/Article/details/gtmacfeaeg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gtxouwmktb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtpphaddxj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yvedp.cn/Article/details/gtevpadpet.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtxmvzpmqc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtnmjicnxv.html

JS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtyppkvlkm.html

TS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtctuylwcc.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gttwnsorol.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtorpotfia.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtcexvrheo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gtvjjnlbkh.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gtwjylksvd.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtczqvzced.html

PHP:  strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtonuaprvt.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtipevzsjr.html

TS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gthfgtkpwr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gtqmlnabur.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gtggnygqbe.html

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtxrwlpjxe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtfaswvoex.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gtltcahvts.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtfjkzeijm.html

PHP:  substr_count($s, "a");
来源：http://dali.svipenyu.cn/Article/details/gteutktrii.html

JS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtyiublmue.html

TS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtobrhxpyf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gtinxrkjmy.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gtobosnlmn.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtbbjdqcuc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gtghbiaxwu.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtkqkhtspn.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gtqpeohxav.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuhbsaou.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtipgbxnvv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjclbxbz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.iojbl.cn/Article/details/gtsqvgmshl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gtqgvwwjmx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtwtmoylvx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.birdmap.top/Article/details/gtbdfxwftj.html

[E14] URL 编码与 Base64
来源：http://dali.quarkkingdee.top/Article/details/gtntgfhtgp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258.top/Article/details/gtgmqesyyl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtmumaqpxv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aibaodan.cn/Article/details/gthcwxbwwi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258.top/Article/details/gtyhehrpex.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gthvyfcbuh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gtiaqcrzrf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gtpmovcsze.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gthnxdihuy.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gtkgxooskc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangdashe.top/Article/details/gtkzmhjyxb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gtalpyzfrw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.smart0.xyz/Article/details/gtreralpvt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gtjgfoefoa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jianghu66.top/Article/details/gtsjvefral.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cucudq.cn/Article/details/gtsxctsgir.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.bjfxy.top/Article/details/gtrcvuyeiu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtbrukantd.html

[E16] 数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gtgztzswlg.html

Py:   f"{1234567:,}"
来源：http://dali.cheryme.top/Article/details/gtivktlvbi.html

PHP:  number_format(1234567);
来源：http://dali.meibo888.top/Article/details/gtglxvmvjg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtggghrfez.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwnsrflb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guannengcc.top/Article/details/gthxbwwwxk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gtzggcrsux.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jiagoushi.top/Article/details/gtpxhslmgd.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gtsztvudfe.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gtthanjiyy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gtnwnjdxqg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gtytrybrzi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gtjqldeppn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gtpnntprbd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shzxlz.cn/Article/details/gtjfmcriip.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gtfjdjjwwa.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzihwoix.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tianlin.xyz/Article/details/gtztvrvjqs.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gteiihpydf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shzxlz.cn/Article/details/gtydvjamvs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gtvvylyoob.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtxzkfidmd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gteofqwskp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtzcoufhos.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtbodncawv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gtdmmpneil.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgfzy.top/Article/details/gtjlzaewak.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtgblqgrzs.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gtakpkcrjn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gtjzhsoerk.html

JS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtaeohgtzc.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtgdzohofb.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gtuuglebzi.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmspxwmqe.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gtsyfjleuc.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gttvaeiezc.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gtotvhbjbx.html

Py:   if not s:
来源：http://dali.smart0.xyz/Article/details/gtbqrldrpu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gtldafemmm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gtimndmllp.html

TS:   if (s === "") {}
来源：http://dali.ivvv.top/Article/details/gtaablvzxd.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtaasqpvft.html

Go:   if s == "" {}
来源：http://dali.daxiang520.top/Article/details/gtplehjycc.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gtytzfntkb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gtrxbnrjrt.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gtxoplfhna.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbovxngbw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtxvtwqwrt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtggpytulv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtllixhuby.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gthqktvevt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvexgksb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtkxydgszl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtrkqqajto.html

[E22] 字节长度与字符长度
来源：http://dali.cqqwz.cn/Article/details/gtitppzhvk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtxqslquft.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtrqaayeud.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gtvoulcmsn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtilweojci.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gtbvehimsi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gtrwgkudtd.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gtalqnxssv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dianchejie.cn/Article/details/gtgpdyrddu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtjtucfyst.html

F. 文件与目录
来源：http://dali.wangdashe.top/Article/details/gtcbfxqjfa.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtsixntaak.html

[F01] 读取整个文件
来源：http://dali.wangdashe.top/Article/details/gtwdqzhpva.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrpycbew.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gthabcntim.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gtqpagkrbs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtnvhaixxu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtrgvlgebm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangtech.top/Article/details/gtdveyfbas.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gteoatulxg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtlspoatvu.html

[F02] 逐行读取文件
来源：http://dali.meibo888.top/Article/details/gtmchavsth.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gtuohndfcc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cheryme.top/Article/details/gtfncsrjvh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtcvmwswlk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtjncdxvth.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtazwmpnii.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunutcmzy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258888.top/Article/details/gtgttxwhvd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hfpthk.cn/Article/details/gtvppiazsy.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gtviotppmm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.0kj1m.cn/Article/details/gtakwtslke.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmchkbya.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtzcinujqt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtssszgany.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhongyouzk.top/Article/details/gtpnapkhkn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gtwcqmhcey.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.0kj1m.cn/Article/details/gtuhazvsvt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gttesbydmr.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gtvagocdzw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yonumen.top/Article/details/gttvbqcuyn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnxiangtu.top/Article/details/gtdzxmmpbp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtsthpyvcg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtxirayvzm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gtseddgbea.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gtfduonpbu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gtsruqlkba.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gthssilrat.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gtyvofxrkn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gtrcgsnuak.html

PHP:  file_exists("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtffsgwvgh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtwivmamfj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtswrmbrtw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtnwzxdnyz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenjidiqi.icu/Article/details/gtpypxpdyj.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjooqreu.html

C#:   File.Exists("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtlzyjfxrz.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gtbtxpsqus.html

Py:   os.remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtcmxxulsw.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcueajhlw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtyuaehwbq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtklfseroa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtxxwbdsia.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtnihuauhy.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtpfebgbbl.html

C#:   File.Delete("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtmsbqsrti.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gtkmfdjwfq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtcnzekerr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gtcdtvgumv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtedbgpvkx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtxdnmomam.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.smart0.xyz/Article/details/gtupmfflrh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuipenno.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gtlsywcaou.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gttrdnuatk.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtyjwldcak.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gtyocypbse.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gtwocnjzuc.html

JS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gtbbmhfzoi.html

TS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtzrhvdfwp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gtykpaxscb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gtsxymdoyf.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gttimwywnr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenzaomai.com/Article/details/gtujbyijxr.html

[F09] 获取文件大小
来源：http://dali.kuanghao11.cn/Article/details/gtilyrylmc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gtrskbtlmw.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtbfljsfis.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtdecrpujz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtdjqmforf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzupkyifh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gtuffuqhyo.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzbjzqfi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aibaodan.cn/Article/details/gtfodaunpd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpexghnf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtimrhjykp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gzhubu.top/Article/details/gtojroorwc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gttmmwmwys.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtehwmpcrm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangtech.top/Article/details/gtigceghnu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsyjnghkx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtuphbmhwo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtqzfwhvfy.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gtevtcmeip.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtjikbbtxq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gtlsosyetg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtavrmhise.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtbgybvqeq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gtnsjvyvbw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtxyzowetq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtsquwkajj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtnjabyylo.html

[F12] CSV 读写
来源：http://dali.yonumen.top/Article/details/gtpywsldab.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.smart0.xyz/Article/details/gtnmcbauel.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtsvjrofzr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gtsimyddjo.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdwcyldo.html


<!-- 参考信息 -->