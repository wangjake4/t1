代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gt2oaorktqr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuanzx.com/Article/details/gt2xlsuaxql.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gt2mvtditdu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnbjgxve.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.quarkkingdee.top/Article/details/gt2rkbllbec.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zycfv.cn/Article/details/gt2guhrjxjh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gt2svibneyg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2vothbcye.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gt2cvrvegsi.html

Py:   "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gt2fldebppy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fyrizfla.html

JS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2ajabhehq.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2oqzqswkg.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2kwssqfvi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yfngybiq.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gt2dweyaclr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yanxiufei.cn/Article/details/gt2vxnrkjjq.html

[E03] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gt2hyizgmjc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sxryk.cn/Article/details/gt2hfzaaduh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gt2rsaypxtk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnfyqobb.html

TS:   s.slice(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vnjdgnle.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2povvlwlm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dashuyun.cn/Article/details/gt2mwugaabo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jihnjkcv.html

C#:   s.Substring(1, 3)
来源：http://dali.xinyue.icu/Article/details/gt2hlktmjqj.html

[E04] 查找子串位置
来源：http://dali.svipenyu.cn/Article/details/gt2kbdxfxgo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sysykeji.top/Article/details/gt2ufftqiaq.html

PHP:  strpos($s, "x");
来源：http://dali.9152youxi.cn/Article/details/gt2lyhccsnp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xziqi.cn/Article/details/gt2osrvbkpn.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qaydbrry.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gt2ouulweqj.html

Go:   strings.Index(s, "x")
来源：http://dali.zhongyouzk.top/Article/details/gt2fdrqxyfj.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gt2jrdwuixm.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gt2oieeaprb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gotoacloud.top/Article/details/gt2iqljnojg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xylfe.cn/Article/details/gt2djburmgj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenjidiqi.icu/Article/details/gt2esfnhaqr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2ktwuivls.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sysykeji.top/Article/details/gt2cdajrpyd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2lnlgxydp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kectwbvs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yvedp.cn/Article/details/gt2irglzlog.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gt2lcnpjacy.html

[E06] 替换子串
来源：http://dali.gaohongyu789.top/Article/details/gt2ltckpfli.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gt2qhjzmohw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.316326.xyz/Article/details/gt2rgshbpqm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2fvoixegp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2pqrfmian.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2xkemkuqr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gt2kidyvhel.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2kuaxmryy.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2iucffwyw.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrisndpg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ivvv.top/Article/details/gt2avnwlzcr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2rpnrlgka.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gt2mdyjwebm.html

TS:   s.split(",")
来源：http://dali.hammf.cn/Article/details/gt2awtwxoqj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shuidangran.top/Article/details/gt2melalwbz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gotoacloud.top/Article/details/gt2ftwdkvhv.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gt2fvmwsfzg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dashuyun.cn/Article/details/gt2edzzxsop.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gt2aosozkda.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pktlximx.html

PHP:  implode(",", $items);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rwqddkfa.html

JS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gt2rvdflrtj.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2tmaiwtsd.html

Java: String.join(",", items)
来源：http://dali.fengsongda.top/Article/details/gt2uroioytf.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gt2vqxdiwmn.html

Ruby: items.join(",")
来源：http://dali.hammf.cn/Article/details/gt2itjkfdqm.html

C#:   string.Join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gt2dokxzemt.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gt2hsvnsohq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gt2sihswvcl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2wzjlsaaz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gt2nzxtheid.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmiidgjv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xziqi.cn/Article/details/gt2vstzjfil.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gt2vcdnrswy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yongpay.top/Article/details/gt2bzabdkxg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gt2ftftzxjr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gt2qvpdhzbe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2htkvwvtv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xinyue.icu/Article/details/gt2ytsqchfj.html

JS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gt2rsrkskpo.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gykvxucn.html

Java: String.format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2yajayzxf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2gcnarnks.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2jjjcwzeq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sweek.top/Article/details/gt2aptnjxun.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gt2xaconupd.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gt2nhyzqerd.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gt2jbuuacst.html

JS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2nioaymmy.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2liulpuzn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.mhx1999.top/Article/details/gt2vjvfbxjr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gt2afqptppx.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gt2ioyktbig.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gt2ulpszish.html

[E12] 统计某字符出现次数
来源：http://dali.cdnleiting.top/Article/details/gt2raqhcmkv.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cuxjvvhc.html

PHP:  substr_count($s, "a");
来源：http://dali.daria6918.cn/Article/details/gt2elrmnnxa.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gt2bxzthwno.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gt2xjrmnvbm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gt2wyodztvd.html

Go:   strings.Count(s, "a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzzsngjf.html

Ruby: s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2spxtellv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dashuyun.cn/Article/details/gt2xrzehwoh.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gt2oplgswzq.html

Py:   for ch in s: print(ch)
来源：http://dali.zhengqikj.top/Article/details/gt2jdfjjsay.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hammf.cn/Article/details/gt2olffsyjz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gt2eighulra.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vgkirsak.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2cgsatzcd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gt2laimjzma.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xylfe.cn/Article/details/gt2rvyhedsh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2eklelifg.html

[E14] URL 编码与 Base64
来源：http://dali.meibo888.top/Article/details/gt2bhqdbtdu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2byxmlvkw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gt2irvdmont.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shangyingyoupin.top/Article/details/gt2riuunfbt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfctlece.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2vjsotfaw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.haohaochexian.top/Article/details/gt2odgkbxel.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxuanxn.top/Article/details/gt2kxadzsuy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gt2dyscfcmj.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gt2bfzlbmpt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shzxlz.cn/Article/details/gt2kfdgbfhj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jiagoushi.top/Article/details/gt2yythwrdd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.c1oappe.top/Article/details/gt2dhyhumuo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xinyue.icu/Article/details/gt2ludifmwl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ppjwa.cn/Article/details/gt2jzmovwar.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.9152youxi.cn/Article/details/gt2saoydsmd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppfntsyj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2yeitneoc.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gt2vcispdql.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gt2juhvkapn.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gt2agdqnehf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gt2athvbeim.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gt2fxhcsnkp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgnsvrt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xziqi.cn/Article/details/gt2hhgmlbmc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gt2xzpzrzpn.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gt2qhbvdjgn.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gt2xezksmbk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenlongwang.top/Article/details/gt2cynatqhg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bspoldgn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gt2cixxhttd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gt2jwaonelg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gt2analkyny.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2bsgwqftw.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gt2mdbuxiyb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shangyingyoupin.top/Article/details/gt2agodlpca.html

[E18] 模板占位符替换
来源：http://dali.hywenlv.cn/Article/details/gt2fhihozhx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangdashe.top/Article/details/gt2basdnnek.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gt2givikbzw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2pyesofqs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxzpprsg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2xoizowkg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2tvdxmhiq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gt2qhlxbzav.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenlongwang.top/Article/details/gt2tkhocisi.html

[E19] 多行文本按行拆分
来源：http://dali.tianlin.xyz/Article/details/gt2wvopdjek.html

Py:   s.splitlines()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ojppwsps.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2msezdtor.html

JS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gt2pypmnzar.html

TS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gt2rjifouuk.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gt2iptanzto.html

Go:   strings.Split(s, "\n")
来源：http://dali.guowangkeji.top/Article/details/gt2jhruqufx.html

Ruby: s.lines
来源：http://dali.quarkkingdee.top/Article/details/gt2rxrygnxh.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gt2oqevhahz.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gt2kcdhekfs.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gt2wgwguiht.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yueranfly.top/Article/details/gt2imlkoscc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guowangkeji.top/Article/details/gt2mqldemnn.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gt2mdtgvjfy.html

Java: if (s.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gt2adblxvkm.html

Go:   if s == "" {}
来源：http://dali.daria6918.cn/Article/details/gt2qhaqarru.html

Ruby: if s.empty?
来源：http://dali.shzxlz.cn/Article/details/gt2kyhboqox.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gt2xidligrc.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gt2eftnqnwt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2onifpmne.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2uqcjrwqz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2bxmiyepw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2itwkbdxa.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2aakwxqxr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jianghu66.top/Article/details/gt2vgorkept.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2nzccuzjm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2nvglrdnh.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gt2uywdbovp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yvedp.cn/Article/details/gt2kwgdmzot.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gt2jzcrrnun.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gt2cwzzrhxd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gt2rtcmeqrw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gt2wvimrlxx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shzxlz.cn/Article/details/gt2qjuteosa.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigufen.top/Article/details/gt2fwehyipf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.andypj.xyz/Article/details/gt2ubmrwemx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2euqucdog.html

F. 文件与目录
来源：http://dali.yongpay.top/Article/details/gt2wgpkostu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2rluhnfbg.html

[F01] 读取整个文件
来源：http://dali.yuanzhike.top/Article/details/gt2xqxlnxyi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gt2rjyagndh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wkrybgst.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gt2tyzcoimx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2kypzvnlg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2gblhfovr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gt2sqowalmv.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2lwycleom.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2kwrsfrkh.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gt2rnyerqfr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhengqikj.top/Article/details/gt2fkfmaufc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ydzc1.top/Article/details/gt2rzxfkbta.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2nrrtaudv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gt2kcmbccyy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2enorgsgy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gt2pbnycbos.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzruyegr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gt2hwhqymye.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pekinktl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2livsaztn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2sbfjqapk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gt2zojkghgp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2drthjxnp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2khghfxel.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gt2lnyhbicp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gt2foflcwnd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2gmsqkbfx.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2hidfijxh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2iodhrmmy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangdashe.top/Article/details/gt2mpxvlqla.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwrkxbyi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gt2ybmuzfof.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gt2itneslwi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jyoumei.cn/Article/details/gt2zjyntsli.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.kuanghao11.cn/Article/details/gt2vkvxnped.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqgnpljg.html

[F05] 判断文件或目录是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2tvzjfsuk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gt2skcdcfsl.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2qafcvgyn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2xjkeqajj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vevzgskt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2lalctjvu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gt2ydrklakh.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2abhjmkkq.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2yumlowkf.html

[F06] 删除文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2twfojxgq.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2wzswdkso.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2jpnnfiyc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2yofrdsun.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2pofwnrku.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2qlmulnou.html

Go:   os.Remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2wnehfnkl.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gcpscmmm.html

C#:   File.Delete("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2nrjetmme.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gt2qdtexvld.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2lglyiuos.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2ltarswtl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gt2klfocpwa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2weawaeve.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tanke756.top/Article/details/gt2ixclyiih.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gt2nfcyeaby.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gt2lyimbhhb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gt2noaupjsp.html

[F08] 遍历目录
来源：http://dali.yj20258.top/Article/details/gt2lhwykjha.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qylavusc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gt2gmpmkziy.html

JS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gt2sexzpjzy.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2vjdgkkau.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gt2ptcriyzc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gt2ldpdfvew.html

Ruby: Dir.children("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2qgvlnjgq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ckouywdf.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gt2rjinssys.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2wrfipwsk.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2ksmntdqp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gt2makvopck.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gt2qkkzmuvz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2hfhszxxb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gt2vfidplyg.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2zuoqmecd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gt2wnzuahfe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigufen.top/Article/details/gt2lnmzqfjd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2cihesyeq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2dzbescac.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2mfxtleit.html

TS:   path.extname("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2pozawemq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gt2kpbdrkrp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2teaewvwz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2khbbbpsk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2qaqukqmn.html

[F11] 复制与移动文件
来源：http://dali.nanxuanxn.top/Article/details/gt2ebislpxp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2uuealnxc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gt2hymxqlwa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxewkshh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2ibmueawr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sysykeji.top/Article/details/gt2zagcrula.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gt2cwznprsw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhrpgixz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yongpay.top/Article/details/gt2ejchppod.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gt2bkpbcygb.html


<!-- 参考信息 -->