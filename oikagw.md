代发 wailian999

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rysbjvez.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jyiqinch.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gt2xilsnrji.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gt2xdsiblgp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gt2mkdgtndx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ydzc1.top/Article/details/gt2hrtwvlwa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2zfvmrxsf.html

[D26] 数组转字符串
来源：http://dali.havefunace.top/Article/details/gt2eslmmukt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuanzx.com/Article/details/gt2bgonffaw.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxdaasvw.html

JS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2ycdpuwgq.html

TS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gt2jsoljdzk.html

Java: String.join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gt2gxtkuvtm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gt2ftutdbdf.html

Ruby: arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gt2fbqlqrje.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2krderjhz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tftmuhsu.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gt2vvafdjpi.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2llvfvtlu.html

[E01] 拼接字符串
来源：http://dali.xziqi.cn/Article/details/gt2ihpesmaq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cashguo.top/Article/details/gt2dxbxmlco.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gt2itkbvyti.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gt2nlndkdsm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gt2kvmubbzv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.316326.xyz/Article/details/gt2ycbignhr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iklennsk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gt2ivryiema.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2ikoacbcu.html

[E02] 重复字符串
来源：http://dali.nanxinkj.top/Article/details/gt2xzkvjnen.html

Py:   "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gt2nuvhzanl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xziqi.cn/Article/details/gt2orhlnoud.html

JS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gt2jqxeruoy.html

TS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gt2jenikjit.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2laueguyu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.snrcjt.cn/Article/details/gt2vtkfcixt.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gt2zqrfcxoj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cheryme.top/Article/details/gt2jbokhqag.html

[E03] 截取子串
来源：http://dali.cucudq.cn/Article/details/gt2ujtbogyb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shuidangran.top/Article/details/gt2bkykfeel.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2cxkogxyb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gt2nxzwpcwl.html

TS:   s.slice(1, 4)
来源：http://dali.ybcxt.top/Article/details/gt2rgujkoox.html

Java: s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpngzgqq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gt2kchdbhkt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qypbtfns.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gt2kpuziqco.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytvfmubd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gt2txrpnvnt.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258888.top/Article/details/gt2utuhihsp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.redwolf501.top/Article/details/gt2otvvjyqj.html

TS:   s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gt2rxtluuce.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2rlnihcrh.html

Go:   strings.Index(s, "x")
来源：http://dali.xuanzx.com/Article/details/gt2gndfdmgf.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2skvmzdtj.html

C#:   s.IndexOf("x")
来源：http://dali.pycfn.com/Article/details/gt2izhqqwfq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cdnleiting.top/Article/details/gt2vanxqmev.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2yzzjkbtf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.iojbl.cn/Article/details/gt2ujghrund.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gt2oqclqgkk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.andypj.xyz/Article/details/gt2ulvypdgc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gt2lccxirnv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cheryme.top/Article/details/gt2lckcxhvb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.bjfxy.top/Article/details/gt2sksuyyez.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2oulobrcc.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gt2gthqewcg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2nvyjflzt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gt2avwvegrp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2lrrlgkil.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2pqsbxbkk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2qyxrywdn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2vvnfwief.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2pkpyqhcu.html

C#:   s.Replace("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2onpulwsi.html

[E07] 按分隔符拆分
来源：http://dali.9152youxi.cn/Article/details/gt2swhkslws.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gt2lvppwhdo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2fitlnyvk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daxiang520.top/Article/details/gt2phdojzqm.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gt2icrklavr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.quarkkingdee.top/Article/details/gt2hsfuxgxr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2urrcxclk.html

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gt2ggbnfivt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sfrwgunz.html

[E08] 数组按分隔符合并
来源：http://dali.dashuyun.cn/Article/details/gt2zexusqmk.html

Py:   ",".join(items)
来源：http://dali.snrcjt.cn/Article/details/gt2jikxgyem.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gt2gzauitmh.html

JS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gt2wgvvjlan.html

TS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gt2tajbbdxr.html

Java: String.join(",", items)
来源：http://dali.smart0.xyz/Article/details/gt2xznckvyp.html

Go:   strings.Join(items, ",")
来源：http://dali.nwbrower.top/Article/details/gt2yfjbqdlu.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xenthema.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2goijsnqc.html

[E09] 去除所有空白字符
来源：http://dali.svipenyu.cn/Article/details/gt2bnuibuxn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ivvv.top/Article/details/gt2zqnfdqnm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2vdnhbbvk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zrvbzyad.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gt2fidvzeyu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gt2wovfectw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ivvv.top/Article/details/gt2rqcvcesy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.birdmap.top/Article/details/gt2dcvazltp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gt2qqcevrng.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gt2hhzzvgff.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2vacngchc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gt2huynjqnu.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljwbmfuf.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2jecpvqcx.html

Java: String.format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gt2ctxcmwfq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gt2vptsskbu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gt2nnjudrjq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pycfn.com/Article/details/gt2aesiagsw.html

[E11] 反转字符串
来源：http://dali.jyoumei.cn/Article/details/gt2qwdrzuua.html

Py:   s[::-1]
来源：http://dali.iojbl.cn/Article/details/gt2xueiafec.html

PHP:  strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gt2fwdohwlb.html

JS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cjhvrdkm.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2xlafvimb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2ywrutshi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gt2fxuwgylk.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gt2ubeszhki.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gt2hqfepfuy.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gt2spwhzwqz.html

Py:   s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2rbbjmlyh.html

PHP:  substr_count($s, "a");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpdrasty.html

JS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gt2nrxhbcyp.html

TS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gt2tdqbicxs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gt2slmijoyq.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gt2jxemphhy.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gt2qwumiwbb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tanke756.top/Article/details/gt2agfuyihk.html

[E13] 逐字符遍历
来源：http://dali.316326.xyz/Article/details/gt2qmxtdqgi.html

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gt2ytlioycj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ppjwa.cn/Article/details/gt2eglevirh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gt2cgyjxwjl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2jbqaoswu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gt2kktmfuqc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gt2kbshtpib.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gt2peladhsk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2uffqqosc.html

[E14] URL 编码与 Base64
来源：http://dali.sysykeji.top/Article/details/gt2rlavoiai.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xinyue.icu/Article/details/gt2fomziebg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.bjfxy.top/Article/details/gt2hdlnvsix.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgufenzy.top/Article/details/gt2lmpnuxqb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xziqi.cn/Article/details/gt2ymlhlzdi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tianlin.xyz/Article/details/gt2ptvolvmh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gogol.net.cn/Article/details/gt2dgcanxca.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gt2ejbqfvfm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2kqfwrxlr.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhixingplan.top/Article/details/gt2dtwjonsg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yvedp.cn/Article/details/gt2ftzunkms.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gt2zourcgeg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhengqikj.top/Article/details/gt2tpnwmnxx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2udqaglnx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gt2klqfcdlh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gt2wiqcxlnr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvqjiuip.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvuejwab.html

[E16] 数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gt2rfspwzjw.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zeodhwwr.html

PHP:  number_format(1234567);
来源：http://dali.birdmap.top/Article/details/gt2iggsrhqw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2mnbuptcz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gt2kmsyzvjt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cucudq.cn/Article/details/gt2fjaqvqcg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258.top/Article/details/gt2zwfnswlf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gotoacloud.top/Article/details/gt2lcdnxwyq.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2teoxmfsx.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxmiitpn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gt2nnjlqrxa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgfzy.top/Article/details/gt2jowguede.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gt2ijnmhyoa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gt2ufmdnepf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.smart0.xyz/Article/details/gt2nafqxstu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gt2nzrparhg.html

Ruby: s.capitalize
来源：http://dali.redwolf501.top/Article/details/gt2drhfdazu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xylfe.cn/Article/details/gt2ehuowxct.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gt2joaporlm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqmringa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gt2axpazwfz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2viwotjod.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2xuffomzm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2thnoxemj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jfoairuy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cashguo.top/Article/details/gt2ckqftknv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gt2pryovbeq.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gt2jgcicatx.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vflqmnti.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shuidangran.top/Article/details/gt2cybjdrgx.html

JS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gt2ochajlvm.html

TS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gt2huyddcjp.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iklzgoxl.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuxming.cn/Article/details/gt2lernyidw.html

Ruby: s.lines
来源：http://dali.jiagoushi.top/Article/details/gt2jnogzlqm.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjvybjha.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gt2icwssvge.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gt2dhfkizrl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gt2hbzkhzxa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gt2jjbvyrhg.html

TS:   if (s === "") {}
来源：http://dali.tian-w.cn/Article/details/gt2midubppg.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gt2daznomll.html

Go:   if s == "" {}
来源：http://dali.hnxiangtu.top/Article/details/gt2gokkfuqr.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gt2lcobebba.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pycfn.com/Article/details/gt2mrlypyoj.html

[E21] 超长截断加省略号
来源：http://dali.xinyue.icu/Article/details/gt2flqimmwx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gt2tfsfksrm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gt2nchpkyga.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2yhqufkba.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2ezqdmcbr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2eqvvelmw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigfzy.top/Article/details/gt2zxlqbtbb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zjwaqxva.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2esxsoacn.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gt2wtwkvhly.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guowangkeji.top/Article/details/gt2jpfzgvyw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2uwcubilt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gt2anidefod.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gt2ouovdiat.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gt2ihuvzdmo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ydzc1.top/Article/details/gt2cvdlbhxu.html

Ruby: s.bytesize;  s.length
来源：http://dali.birdmap.top/Article/details/gt2rfdpahub.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gt2xracimsn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2sjcsbvjf.html

F. 文件与目录
来源：http://dali.shzxlz.cn/Article/details/gt2pbcxvbdw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2hzqmnjxi.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gt2fcavdoub.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gt2dhuzrfkh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxlxhvbk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gt2xzcqtsmd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gt2gsatjbpp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2fmgitwbm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.snrcjt.cn/Article/details/gt2yjergdfr.html

Ruby: File.read("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2pryfyfrj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2fbyauhly.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxjiqbxl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtlbggaa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gt2kehphgji.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2lhpukbtz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2ouhjanlo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnbesxnr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2prwspkri.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gt2zacyghyn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gt2sieowerm.html

[F03] 写入文件（覆盖）
来源：http://dali.birdmap.top/Article/details/gt2rmodnpyo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ruryrkvb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxliywof.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2zbvwopmu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2pzdvfvbg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gt2ooeduisc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.vqdsnc.cn/Article/details/gt2wwssyvyc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.svipenyu.cn/Article/details/gt2wrxizuyx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gt2rmbbmgoq.html

[F04] 追加写入文件
来源：http://dali.smart0.xyz/Article/details/gt2puvrvqdf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gt2ysdahapn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gt2ilcygouv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gt2gnklvkhn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2uzuxwkkf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gt2easwawwd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gt2efkkqbmj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gt2ektmiutp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gt2sxyfsdsq.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gt2tsovbjkv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gt2jgrnpour.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aqecgtgq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2wdeavuns.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2mfuwdkfs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2hqzopdcj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258888.top/Article/details/gt2jpnirkae.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2panafvvy.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2wrfcqgay.html

[F06] 删除文件
来源：http://dali.dashuyun.cn/Article/details/gt2ejjdtnnn.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2zbosqlke.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtprnbzs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2wighembu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2bpqthknn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2ccubjyuu.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2qdxtzwjs.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2snccvinh.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2iykmbcdx.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gt2dwpwpqyx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gt2otujvaat.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tanke756.top/Article/details/gt2pvasoadf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gt2ljaqbanf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqibvieg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gt2klxgwlqn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gt2kiqctzwp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gt2vhivtfqi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hongshengwenyu.top/Article/details/gt2bnschzcw.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gt2xfrnczli.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2puulivru.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gt2uvtwjbgu.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ltedkykt.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gt2blvmrerw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gt2grbkxugj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2drenwfpg.html

Ruby: Dir.children("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2ufvxnmue.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtopwbky.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gt2bvbzmqge.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2mvkqkhoo.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2fnkooyhc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gt2yadttqcg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gt2blbqsbeh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2equmiuut.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gt2lxpjwhre.html

Ruby: File.size("a.txt")
来源：http://dali.sweek.top/Article/details/gt2efdqryfa.html


<!-- 参考信息 -->