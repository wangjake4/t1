代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ybcxt.top/Article/details/gt2fcwjylae.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenzaomai.com/Article/details/gt2ezmdtkni.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2togdbwdz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.smart0.xyz/Article/details/gt2abqbrxmx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guannengcc.top/Article/details/gt2oafuscpw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hywenlv.cn/Article/details/gt2toxpnypb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2yqqedgvu.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gt2llrfmtvv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daxiang520.top/Article/details/gt2mtfgpkyn.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2jkbppxgz.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gt2coricaeu.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2lzctpfwx.html

Java: String.join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gt2tldjpaar.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258888.top/Article/details/gt2umfwosce.html

Ruby: arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gt2sklgbylr.html

C#:   string.Join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gt2quwrcjvj.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2cvqxumvy.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gt2oispoxzi.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2uywmodqw.html

[E01] 拼接字符串
来源：http://dali.ydzc1.top/Article/details/gt2lgamcuek.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljktaeiw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gt2xetzofih.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gt2gijmosah.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mwkfrehj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gt2gjydcadz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yvedp.cn/Article/details/gt2otsnyfnd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cucudq.cn/Article/details/gt2xptylpbv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2yuvdpzze.html

[E02] 重复字符串
来源：http://dali.c1oappe.top/Article/details/gt2pmoczixw.html

Py:   "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gt2xgartjbu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aizwys.cn/Article/details/gt2enajtidi.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tzikmsqk.html

TS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gt2vudultqv.html

Java: "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gt2uyklsmex.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2oxopdska.html

Ruby: "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gt2xzdcetkd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhiwuduotai.top/Article/details/gt2eyxyvkea.html

[E03] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gt2gzrezkqg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gt2pjjhamkg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2wxzieryt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2feymgpod.html

TS:   s.slice(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2rlustwkl.html

Java: s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2nqcvrxey.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hmluqgjh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yvedp.cn/Article/details/gt2zlwtqtbo.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2lqmtxaip.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gt2necchamj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2epmllrnq.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gt2xncbpqqp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gt2wbgrnizt.html

TS:   s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gt2yccerzdb.html

Java: s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gt2whkmtuyh.html

Go:   strings.Index(s, "x")
来源：http://dali.daria6918.cn/Article/details/gt2bcszfnmr.html

Ruby: s.index("x")
来源：http://dali.ybcxt.top/Article/details/gt2lkazxbhq.html

C#:   s.IndexOf("x")
来源：http://dali.pycfn.com/Article/details/gt2eoiwtnlf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.c1oappe.top/Article/details/gt2eesdwamt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cucudq.cn/Article/details/gt2mlybanaz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gt2qeccijej.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aryeerur.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ehwqpu.com/Article/details/gt2wagyqjel.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gt2vsdppfvu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fengsongda.top/Article/details/gt2qzhjrqvm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qztlyhyu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hammf.cn/Article/details/gt2ofwseaok.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahqybjjb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gt2zgiepnev.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gt2vfcsnuak.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2qkajdkvf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2wnqxpoxh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2iewwnyvs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gt2pvdursob.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2kbfsbhmt.html

C#:   s.Replace("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2ttljjixw.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gt2afcgovst.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.meibo888.top/Article/details/gt2ogejebfb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2lktoiijr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2agaslxif.html

TS:   s.split(",")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wfyhujsw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gt2rcbhjcux.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.havefunace.top/Article/details/gt2ucjouvqu.html

Ruby: s.split(",");  s.split
来源：http://dali.nwbrower.top/Article/details/gt2uqzxfyat.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigfzy.top/Article/details/gt2fluwhpkk.html

[E08] 数组按分隔符合并
来源：http://dali.jianghu66.top/Article/details/gt2hhscxjlh.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gt2lqvacfpy.html

PHP:  implode(",", $items);
来源：http://dali.wangdashe.top/Article/details/gt2dggmyzjv.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2kzacovxe.html

TS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzcsnwfb.html

Java: String.join(",", items)
来源：http://dali.xinyue.icu/Article/details/gt2lpuzvvic.html

Go:   strings.Join(items, ",")
来源：http://dali.chenzaomai.com/Article/details/gt2mratcpiv.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gt2idpzflfb.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gt2adckdlcx.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gt2omrfjigo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zdqjudy.top/Article/details/gt2uyztvyaf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2fgpdssio.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ipvchdyd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2zshbzsxa.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gt2hxlxamtu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.mhx1999.top/Article/details/gt2kpiccrmv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2xdpbbzui.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gt2axduflik.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvxbbutv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gt2nxveucbl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sufxvd.cn/Article/details/gt2mxsdwihf.html

JS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2nqtuszyk.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2hyghkzdv.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ddewatkk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2uwezdlzy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gt2uodyybjr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuanzhike.top/Article/details/gt2wottatup.html

[E11] 反转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2mckaavnl.html

Py:   s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcjgqrgn.html

PHP:  strrev($s);
来源：http://dali.aizwys.cn/Article/details/gt2ezjbawmm.html

JS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2frsewbld.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2lxfuwclw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2ixrnmofq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gt2diqxfxsu.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gt2xylmkqtc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gt2qxstvcqp.html

[E12] 统计某字符出现次数
来源：http://dali.yueranfly.top/Article/details/gt2tcfizqpe.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gt2pzzgbjdx.html

PHP:  substr_count($s, "a");
来源：http://dali.xziqi.cn/Article/details/gt2avyuzwmp.html

JS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gt2mgdtrbqb.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gt2fzdqmhfr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xoqaqjhs.html

Go:   strings.Count(s, "a")
来源：http://dali.xuanzx.com/Article/details/gt2wahqrzfn.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gt2xulewsvp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gt2hatrpicg.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gt2fwjiqbmn.html

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gt2hbwcdsyt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odoiiyif.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2vxtjougk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2hnjjezwh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2wkevstiv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gt2wnjevyel.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sysykeji.top/Article/details/gt2zbnxeuvw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gzhubu.top/Article/details/gt2iztyvhra.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gt2nmftvrmi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gt2qrbfbhvy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aibaodan.cn/Article/details/gt2tkghhvby.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hysaishi.cn/Article/details/gt2numkkqtf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gt2dixopaqc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yftwrodc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jlsjyb.cn/Article/details/gt2ztcauzwt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fengsongda.top/Article/details/gt2eqctaiaa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2bwtjompi.html

[E15] HTML 转义 / 反转义
来源：http://dali.gogol.net.cn/Article/details/gt2vtxucixp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gt2lclosbpr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jiagoushi.top/Article/details/gt2zirnyrdl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigufen.top/Article/details/gt2ypxqhrcl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2chizybuo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gt2jjofjlay.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jyoumei.cn/Article/details/gt2hucvwldf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jiagoushi.top/Article/details/gt2dniytkoe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xylfe.cn/Article/details/gt2bztiltha.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gt2cbapmajo.html

Py:   f"{1234567:,}"
来源：http://dali.cdnleiting.top/Article/details/gt2qexwdnex.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lkjtinhj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gt2uaguliaf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gt2nvwusmkx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.c1oappe.top/Article/details/gt2aobfybsw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2objczexr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2rojdlbiw.html

C#:   1234567.ToString("N0")
来源：http://dali.daria6918.cn/Article/details/gt2nktfnhei.html

[E17] 首字母大写
来源：http://dali.andypj.xyz/Article/details/gt2xnyxazrp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gt2tpniehdw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gt2griqojyc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gt2pcykyazi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gt2hgvagket.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhengqikj.top/Article/details/gt2ufctvdxo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2dgqlfllb.html

Ruby: s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gt2smcjovvt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gt2mflyqjwt.html

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gt2izjdvgfc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hfpthk.cn/Article/details/gt2uuusqujh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gt2eohomjit.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2cgebxmvz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkasliro.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2siuazfwb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2xlswlsmp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gt2bfmbtqfs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gt2vnlmdbtf.html

[E19] 多行文本按行拆分
来源：http://dali.kuanghao11.cn/Article/details/gt2qszvigyk.html

Py:   s.splitlines()
来源：http://dali.cdnleiting.top/Article/details/gt2lwmwxksp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jpcwmlgn.html

JS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2arfxgpbf.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gt2rncqpjem.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gt2yllumkiu.html

Go:   strings.Split(s, "\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2upztqtun.html

Ruby: s.lines
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzlqeyxo.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gt2ndokidhw.html

[E20] 判断字符串是否为空
来源：http://dali.jianghu66.top/Article/details/gt2zdcypczg.html

Py:   if not s:
来源：http://dali.chenzaomai.com/Article/details/gt2nzpobtrp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hysaishi.cn/Article/details/gt2lgoojzqi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gt2tbhdsqng.html

TS:   if (s === "") {}
来源：http://dali.aizwys.cn/Article/details/gt2nchjpehh.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gt2towgnpjt.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gt2vpfyermz.html

Ruby: if s.empty?
来源：http://dali.hfpthk.cn/Article/details/gt2gcgpzcit.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gt2zpwlgsek.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gt2cmdjqjpy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guowangkeji.top/Article/details/gt2ctxrfcos.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxcyweqz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2efeqcnyn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2inviseox.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtdokcyj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gt2pawuaojc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwipjvtg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2iikwofcx.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gt2nszadraa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ljabmpgg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2xukldsnp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2cifhstwa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2dmdgddku.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fzhhl.top/Article/details/gt2pivsmfei.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gt2pazakrct.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxinkj.top/Article/details/gt2udjesyce.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigufen.top/Article/details/gt2imacwxic.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2jdhgdjgw.html

F. 文件与目录
来源：http://dali.dashuyun.cn/Article/details/gt2qnejnwpw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2hemonhfq.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gt2xwxxngsu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnqzz.top/Article/details/gt2xbiczicb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2cmkrpwpq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gt2rjcnzuhp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2rfrhamex.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2iweaspri.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fzhhl.top/Article/details/gt2ktwiwbbw.html

Ruby: File.read("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2hjrttxnb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2ydvuzpjh.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2tdkjghns.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenzaomai.com/Article/details/gt2lnhgzozg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigfzy.top/Article/details/gt2mhlqlbqa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thebcsqr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gt2xsyryfoq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gt2aamkenhr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2esvywukk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xziqi.cn/Article/details/gt2buoiysru.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gt2omtzgaiq.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gt2zfyepgia.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gt2knkmfbtl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2abwnpgvs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vffsgkww.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gt2hdmeieni.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.meibo888.top/Article/details/gt2msidwjty.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ekbuqvnc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jlsjyb.cn/Article/details/gt2yhnrldio.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gt2gkrngeom.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gt2cxizpkek.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ybcxt.top/Article/details/gt2nlbynfmu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aibaodan.cn/Article/details/gt2gwbohgig.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2cfvhfvla.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gt2yooauabx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gt2lwdjlqid.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2kmjqdqek.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gt2aylasgpv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gt2uwdzcuid.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gt2wsgsecmp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gt2mqpfclwe.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnptbdju.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2yneomdcz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2abhifgdl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2hmbaheby.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gt2avqxjobx.html

Ruby: File.exist?("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2wpmijyhm.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2ierwxkcb.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gt2oojqpkyc.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2ognnlqzq.html

PHP:  unlink("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2leztwvdr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2bvvojsig.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2hqagtimi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2welohyvt.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2ovgpilya.html

Ruby: File.delete("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2bxdgwuto.html

C#:   File.Delete("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2srrcsuvc.html

[F07] 创建目录（含多级）
来源：http://dali.haohaochexian.top/Article/details/gt2qhyhccsh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gt2uvdniryx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gt2bcypnvig.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gt2rthuzgvj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gt2kmsbdend.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gt2hktgaacq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhongyouzk.top/Article/details/gt2izfdjgra.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ehwqpu.com/Article/details/gt2kqxbdxvo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gt2lcpbtgtp.html

[F08] 遍历目录
来源：http://dali.ppjwa.cn/Article/details/gt2hlgklwrj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gt2dcvnjmzt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuanzx.com/Article/details/gt2soruihwo.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2bnizsdys.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gt2pmfqchzi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gt2dkzhdpqr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2upxogpxe.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tckrilom.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2czejajrq.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gt2pldvjtjf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2hmshuktw.html

PHP:  filesize("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2vcqplppx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gt2mwhhxckm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gt2skxnenjy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2ucahdsak.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gt2setkddon.html

Ruby: File.size("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2zokkcrkm.html


<!-- 参考信息 -->