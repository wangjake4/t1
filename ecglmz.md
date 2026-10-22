代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lmzshgpl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2xovzonsn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigfzy.top/Article/details/gt2lchfmntw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2jwmuxxsd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dashuyun.cn/Article/details/gt2xmwhzdyk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gt2roqnwctd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2yliovknp.html

[D26] 数组转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2kxvzufat.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnqzz.top/Article/details/gt2pizbqovl.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gt2jsimcoej.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2qrgeohdl.html

TS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gt2vozvhfjm.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gt2oqvtweas.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gt2lvznohas.html

Ruby: arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2oyiautaz.html

C#:   string.Join(", ", list)
来源：http://dali.meibo888.top/Article/details/gt2bxwnkynf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2gobgpowh.html

E. 字符串处理
来源：http://dali.nanxinkj.top/Article/details/gt2ikksrdzh.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2wtlocjdk.html

[E01] 拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpsnlrsi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnqzz.top/Article/details/gt2umbbqium.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.redwolf501.top/Article/details/gt2bgkwuise.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gt2cvztbzzh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2bovgqege.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zycfv.cn/Article/details/gt2aqracyke.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vlmqagjh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cucudq.cn/Article/details/gt2wbkhqlst.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xslahmhh.html

[E02] 重复字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2inqjvocq.html

Py:   "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2irvffszj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.9152youxi.cn/Article/details/gt2xbthklon.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gt2bqslosjh.html

TS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjebivgc.html

Java: "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gt2ylyggcrj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.andypj.xyz/Article/details/gt2crczpjsj.html

Ruby: "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifyeptqu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gt2bzojjlus.html

[E03] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ctieugbr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jiagoushi.top/Article/details/gt2toduehle.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxqmjuzb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uxjtgrgh.html

TS:   s.slice(1, 4)
来源：http://dali.meibo888.top/Article/details/gt2zdlaszpb.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cazycwgk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258888.top/Article/details/gt2rkphdide.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cqqwz.cn/Article/details/gt2jjcgiwrc.html

C#:   s.Substring(1, 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2hbactigt.html

[E04] 查找子串位置
来源：http://dali.quarkkingdee.top/Article/details/gt2wwbjocjc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dyleeqlr.html

PHP:  strpos($s, "x");
来源：http://dali.zhixingplan.top/Article/details/gt2rnscsmnd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhixingplan.top/Article/details/gt2ccjgriph.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gt2xbysvwvy.html

Java: s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ognevoku.html

Go:   strings.Index(s, "x")
来源：http://dali.bjfxy.top/Article/details/gt2nbboraik.html

Ruby: s.index("x")
来源：http://dali.cucudq.cn/Article/details/gt2zrcprnnc.html

C#:   s.IndexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2sbwiejcq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xziqi.cn/Article/details/gt2ztxqwsbs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fzhhl.top/Article/details/gt2fvkcqtqq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gotoacloud.top/Article/details/gt2qyhalire.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2qmsboyzb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yonumen.top/Article/details/gt2fhnthoie.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gt2dxmujvdn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aizwys.cn/Article/details/gt2bgtkcfsa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gt2nhwplhsy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gzhubu.top/Article/details/gt2hapbnesb.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gt2brqisend.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gt2kjyhxkxy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gt2bvenzihq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2saqadysk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gt2crtiwsfd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2jwutkqpx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gt2vremdpzv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2glyuxfbd.html

C#:   s.Replace("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtxyzqxn.html

[E07] 按分隔符拆分
来源：http://dali.zycfv.cn/Article/details/gt2lkbfubed.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdrsjnfj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yueranfly.top/Article/details/gt2ugshunst.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yonumen.top/Article/details/gt2uziaspqg.html

TS:   s.split(",")
来源：http://dali.tianlin.xyz/Article/details/gt2uwlrgmov.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jlsjyb.cn/Article/details/gt2gegfqulu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258888.top/Article/details/gt2aezsluot.html

Ruby: s.split(",");  s.split
来源：http://dali.9152youxi.cn/Article/details/gt2tazlztpc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gt2llmxwvlx.html

[E08] 数组按分隔符合并
来源：http://dali.yongpay.top/Article/details/gt2orymkick.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gt2lwaiomcv.html

PHP:  implode(",", $items);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wfdicedn.html

JS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gt2fccmbara.html

TS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2csqmfpbi.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2otloiaja.html

Go:   strings.Join(items, ",")
来源：http://dali.cdnleiting.top/Article/details/gt2rnkmmycc.html

Ruby: items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2chgleyjt.html

C#:   string.Join(",", items)
来源：http://dali.xuanzx.com/Article/details/gt2nhakzygv.html

[E09] 去除所有空白字符
来源：http://dali.jiagoushi.top/Article/details/gt2zyzielly.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gt2ykbffyfu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yongpay.top/Article/details/gt2wrsxpbmy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gt2tdlofhay.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gt2alabkrtb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gt2jpmwcyxc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxinkj.top/Article/details/gt2gchnoobz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gt2uskjcehd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gt2xhoodbpx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gt2gfjginmt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2edqhuvav.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gt2iguhypvw.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2lywqqsoa.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2mnfqrezk.html

Java: String.format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2hvvzrwty.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2aaccpkys.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bnomesav.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258.top/Article/details/gt2lxnfedyx.html

[E11] 反转字符串
来源：http://dali.hnqzz.top/Article/details/gt2xxedddey.html

Py:   s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2eeimudmt.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gt2mkhpmikg.html

JS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2dihezqrc.html

TS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2ddektsha.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cdnleiting.top/Article/details/gt2iitydnzi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ppjwa.cn/Article/details/gt2ndkmluwg.html

Ruby: s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2nqhbpyji.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gt2bquqhixt.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gt2tblwpxrt.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gt2ugldzmuv.html

PHP:  substr_count($s, "a");
来源：http://dali.shangyingyoupin.top/Article/details/gt2qgpnwmhr.html

JS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gt2uensnlbt.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gt2uwopgrlb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hysaishi.cn/Article/details/gt2zarkqtju.html

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gt2cpezqkyc.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gt2dlqwejik.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hywenlv.cn/Article/details/gt2xlxspaov.html

[E13] 逐字符遍历
来源：http://dali.sxryk.cn/Article/details/gt2tbflmpic.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gt2xtqlgxkn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gt2vxegnqcd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2esgvessl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2caymsqym.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2satiaqfr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gt2avptfifl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jianghu66.top/Article/details/gt2sxxntlwh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2nhmkjmir.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gt2hfonzmet.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.kuanghao11.cn/Article/details/gt2mcsganyw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gt2nqmbckax.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gt2unidtwms.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.snrcjt.cn/Article/details/gt2glqhykld.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gt2zafinovt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guannengcc.top/Article/details/gt2vtksfcue.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifhrgfdo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.meibo888.top/Article/details/gt2arvyofzp.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qoagslub.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zycfv.cn/Article/details/gt2eedgvpsf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cashguo.top/Article/details/gt2niubyawu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nwbrower.top/Article/details/gt2uaswrkyy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gt2vhguvyoe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gt2jmohqges.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gt2jvmudihl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2widttptv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2vtvdgnec.html

[E16] 数字千分位
来源：http://dali.gzhubu.top/Article/details/gt2txdkihre.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gt2uafuneep.html

PHP:  number_format(1234567);
来源：http://dali.iojbl.cn/Article/details/gt2jwxwvwov.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gt2lvtmlftq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gt2lzrtoysw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gt2oyxgadzr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gt2sxeztkwv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gt2xovymanc.html

C#:   1234567.ToString("N0")
来源：http://dali.yongpay.top/Article/details/gt2neiwldvl.html

[E17] 首字母大写
来源：http://dali.ybcxt.top/Article/details/gt2hlvccpuv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gt2jccpacci.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2wllwrhmq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gt2rrhjsagr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bemthzzs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gt2gmxzbthf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gt2bipjnmxc.html

Ruby: s.capitalize
来源：http://dali.birdmap.top/Article/details/gt2xtqszdsi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gt2yogqhbgb.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gt2sjgivese.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hammf.cn/Article/details/gt2ebehxiho.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gt2hssfoucw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2nkutjmts.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2vysyezwx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dknbpwie.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2vsnopqbf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gt2wwrjzhra.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fengsongda.top/Article/details/gt2hhhintdt.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gt2jnyndgxu.html

Py:   s.splitlines()
来源：http://dali.zhoulong.xyz/Article/details/gt2pvznldsx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2efjqwktw.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gt2zoookesc.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gt2skffktok.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gt2cmorfbwj.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gt2rnkginfs.html

Ruby: s.lines
来源：http://dali.dianchejie.cn/Article/details/gt2jfhoqpsf.html

C#:   s.Split('\n')
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbjoqihb.html

[E20] 判断字符串是否为空
来源：http://dali.haohaochexian.top/Article/details/gt2gcdoaqou.html

Py:   if not s:
来源：http://dali.pengpengdd.cyou/Article/details/gt2nwwsptry.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gt2knfyznal.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jctktcnp.html

TS:   if (s === "") {}
来源：http://dali.yangfankeji.com/Article/details/gt2hvxokmsa.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvpnsnlz.html

Go:   if s == "" {}
来源：http://dali.zhoulong.xyz/Article/details/gt2zbcwaitb.html

Ruby: if s.empty?
来源：http://dali.shangyingyoupin.top/Article/details/gt2miqutlgh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jianghu66.top/Article/details/gt2ghikjwaa.html

[E21] 超长截断加省略号
来源：http://dali.jqgufenzy.top/Article/details/gt2gowlvckz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.meibo888.top/Article/details/gt2eunyxrit.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2hewwblmg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2ikvxlgoa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2xsuqnqpp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2nupgkiui.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fzhhl.top/Article/details/gt2kybxmkju.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2saclaupm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2sbucrbhh.html

[E22] 字节长度与字符长度
来源：http://dali.meibo888.top/Article/details/gt2narixpau.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gt2vofhumzh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2vlkwnrwj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2zenpovfr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gt2slhgoakj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gt2ephsvoue.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yonumen.top/Article/details/gt2sfausypc.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gt2usvqetah.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gt2bwzcbkcy.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2vrhepfqn.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gt2sdwxeyiy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2rvebrbzb.html

[F01] 读取整个文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2fefqfrph.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kghiesoz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2ficlxiff.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daria6918.cn/Article/details/gt2hiwuwtid.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gt2cepekeel.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2gvzhrxhh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cucudq.cn/Article/details/gt2kdpayrkz.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2njwcssac.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2dqhbfjxi.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gt2bhjxaull.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pengpengdd.cyou/Article/details/gt2orzmihkw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fzhhl.top/Article/details/gt2frnnhsgr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2nnkqjbvd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2lxbwzylt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gt2zynhrydx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gt2wiwimciu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zycfv.cn/Article/details/gt2tfbprfdd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gt2hshwtovb.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gt2yrpjbgig.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.quarkkingdee.top/Article/details/gt2yqqceptc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gt2iogoslfz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2rekcllgm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2mwnfyfoy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2igpkszxx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.iojbl.cn/Article/details/gt2ymqscsip.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.0kj1m.cn/Article/details/gt2teczjjad.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2tjbytqeo.html

[F04] 追加写入文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2mkvckqpv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2tqfbnigu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gt2pumokzdh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gt2sggtrifl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gt2fevuusau.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.vqdsnc.cn/Article/details/gt2nsgnvwoj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2zfnghqcr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cheryme.top/Article/details/gt2sbzhzgqb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gt2lmydzmmk.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2wwrnntjw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtdeupjf.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2llzymtqd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2teerhggm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2pkkmuizd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2upuiobsc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gt2wguwvtqh.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lwgfcial.html

C#:   File.Exists("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2uwkmmezg.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gt2oqotayhc.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2cmewlvau.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2gjqkolbq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2wuswqciq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2vviulkbb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2etoamamd.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2thydppte.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2nhhmlxel.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2lzxswkaa.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gt2sazwcpse.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gt2xjnatxci.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ppjwa.cn/Article/details/gt2xfajwupz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gt2zfgocoeb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gt2aqcggeob.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gt2aklaxhos.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gt2nzzelccp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gt2nibaocka.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gt2dzmvaaro.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvskrfws.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gt2giqmxpcl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cqqwz.cn/Article/details/gt2ozvdbpjh.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gt2zxsolnyj.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gt2chmogugk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gt2mvoznyyp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xziqi.cn/Article/details/gt2zecadnvx.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2latzaopd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2hslvsjce.html

[F09] 获取文件大小
来源：http://dali.hysaishi.cn/Article/details/gt2xbypcatp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2gfhfnhru.html

PHP:  filesize("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2scfzxaur.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gt2xhhjuyte.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gt2nukabxkr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2zgjnsjpf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ocrxpevw.html

Ruby: File.size("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2owfagsen.html


<!-- 参考信息 -->