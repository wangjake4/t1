代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gt2yqcdorhj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigufen.top/Article/details/gt2ykvlkoql.html

[D25] Set 集合去重与交并差
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oshbqpol.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jaalllbe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.bjfxy.top/Article/details/gt2vfnnwzzv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ydzc1.top/Article/details/gt2lmqtepzh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfpeoyeh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2cqqcwuvx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gt2tuxkcrio.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.bjfxy.top/Article/details/gt2wdwcjkpi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gt2vaufbgit.html

[D26] 数组转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2fbhnslif.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2advjsedu.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2yjnwjmrf.html

JS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gt2wufwkazf.html

TS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2yijhkrln.html

Java: String.join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gt2lavgbkxw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hammf.cn/Article/details/gt2mbecigvl.html

Ruby: arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2afmfaoyh.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gt2fcisrbcm.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2jfasntzl.html

E. 字符串处理
来源：http://dali.tian-w.cn/Article/details/gt2ooeqaepc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2avivxuqv.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2risuolzl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gt2seroslug.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2yjenewmd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2firdygpg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2zeletlvb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jyoumei.cn/Article/details/gt2fpiodfsc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gt2tsmmqgsi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gt2pspbtzal.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2odauyxhl.html

[E02] 重复字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2snxbbwbu.html

Py:   "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gt2opzzpxdp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2outwuetr.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gt2pcgtopxr.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gt2abkicyql.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucvpyneo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gt2dqduuore.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtonmiye.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gt2rorvwbof.html

[E03] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gt2dpjulslt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hfpthk.cn/Article/details/gt2gsrvqnns.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2fftvglvy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gt2zvjlkcis.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gt2xlekusrz.html

Java: s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gt2rxwvmhgj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.andypj.xyz/Article/details/gt2zsirgwex.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gt2hiznojvv.html

C#:   s.Substring(1, 3)
来源：http://dali.dashuyun.cn/Article/details/gt2kuyoehch.html

[E04] 查找子串位置
来源：http://dali.yuanzhike.top/Article/details/gt2fvrajnvw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tanke756.top/Article/details/gt2sjjzgiaw.html

PHP:  strpos($s, "x");
来源：http://dali.yuxming.cn/Article/details/gt2czvtuyfn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnxiangtu.top/Article/details/gt2gdshcidi.html

TS:   s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gt2gswjlwbn.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gt2tnosdmyz.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxinkj.top/Article/details/gt2gapmdgjk.html

Ruby: s.index("x")
来源：http://dali.havefunace.top/Article/details/gt2afzdnxll.html

C#:   s.IndexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gt2fnlvyeon.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yongpay.top/Article/details/gt2yfmsrekd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daxiang520.top/Article/details/gt2kszbkwis.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daria6918.cn/Article/details/gt2vvopvxec.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gt2upbuxufi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gt2cgqkwuxf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffendiga.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2joyzetqt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gt2xvwwdxry.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2hjrjuvgz.html

[E06] 替换子串
来源：http://dali.hongshengwenyu.top/Article/details/gt2poqrdprg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gt2ujbhgjjx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gt2hjmbwmcm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2faaorwev.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2ymajiwqj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2mgdvlzsf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ckvionbr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2hwyuhekx.html

C#:   s.Replace("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2izmjtmap.html

[E07] 按分隔符拆分
来源：http://dali.yangfankeji.com/Article/details/gt2tavootxh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.316326.xyz/Article/details/gt2gebqbwmv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2ecsrbmzo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmwzigcu.html

TS:   s.split(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qojuecik.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cheryme.top/Article/details/gt2mmxeggnq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tianlin.xyz/Article/details/gt2qdagywpt.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gt2owlhzuon.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cheryme.top/Article/details/gt2mpaiolsp.html

[E08] 数组按分隔符合并
来源：http://dali.jqgufenzy.top/Article/details/gt2mwnwzbdy.html

Py:   ",".join(items)
来源：http://dali.316326.xyz/Article/details/gt2aovfajcv.html

PHP:  implode(",", $items);
来源：http://dali.hongshengwenyu.top/Article/details/gt2akpogxec.html

JS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gt2pdgkbvei.html

TS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gt2rlzjnwch.html

Java: String.join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gt2hwzjedrw.html

Go:   strings.Join(items, ",")
来源：http://dali.jianghu66.top/Article/details/gt2ecxwzrsr.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gt2pypqblgu.html

C#:   string.Join(",", items)
来源：http://dali.fzhhl.top/Article/details/gt2cldudxsi.html

[E09] 去除所有空白字符
来源：http://dali.316326.xyz/Article/details/gt2jxxqvcii.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.smart0.xyz/Article/details/gt2mfooltcd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2fkwptaja.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gt2vsqjlrvg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qbgmuisp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gt2zabyatlh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.quarkkingdee.top/Article/details/gt2eqhfjclo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gt2dwzqvspk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gt2jjyzhnbx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnqzz.top/Article/details/gt2rbicfeoh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2ciehrytr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hysaishi.cn/Article/details/gt2qcohheup.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhqftkrz.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2rcckqlla.html

Java: String.format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gt2riupynng.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gt2hwrdhpht.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2dxdohcbq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gt2qsnlfmes.html

[E11] 反转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2peihoecs.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gt2veaseqqz.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gt2qqvispbn.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2ykwurloa.html

TS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2dptnnjzj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zdqjudy.top/Article/details/gt2wjdwwopm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2aozqoaow.html

Ruby: s.reverse
来源：http://dali.shuidangran.top/Article/details/gt2fhreblit.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gt2clfoqpij.html

[E12] 统计某字符出现次数
来源：http://dali.guowangkeji.top/Article/details/gt2icajhuyj.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gt2sqfozmdk.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gt2tnoqmlih.html

JS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gt2ldpybvow.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gt2dcdyhxgs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gt2adpbzcov.html

Go:   strings.Count(s, "a")
来源：http://dali.cucudq.cn/Article/details/gt2bnksiidw.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gt2rxfshmzj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gt2dfwnngdr.html

[E13] 逐字符遍历
来源：http://dali.hammf.cn/Article/details/gt2wtmhyceb.html

Py:   for ch in s: print(ch)
来源：http://dali.zhixingplan.top/Article/details/gt2xicaamnq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gt2mylgdozp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gt2aynhcnec.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2xukwtaho.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2qjfnskyl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ydzc1.top/Article/details/gt2nniwoxds.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhoulong.xyz/Article/details/gt2rmxcqlzv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwrradks.html

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2flmowrty.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hywenlv.cn/Article/details/gt2gpqkymgj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gt2dtqesupo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ehwqpu.com/Article/details/gt2xnextiby.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gt2szczjhff.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2mbwkhvuq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnxiangtu.top/Article/details/gt2vxsqnwpn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gt2otgjftcq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2pgonvmkp.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gt2ezmiylho.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gt2oavhcqea.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenlongwang.top/Article/details/gt2dsjnusgm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258.top/Article/details/gt2omoyffvj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gt2npcqruct.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxinkj.top/Article/details/gt2bgsleyvp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gt2zfkoihfa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gt2yuabzxlx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gt2mwhkytwm.html

[E16] 数字千分位
来源：http://dali.gzhubu.top/Article/details/gt2cvuzoigy.html

Py:   f"{1234567:,}"
来源：http://dali.guowangkeji.top/Article/details/gt2socuhzom.html

PHP:  number_format(1234567);
来源：http://dali.pycfn.com/Article/details/gt2jbenuxfa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gt2ljsmjmbj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gt2xbklegzl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nwbrower.top/Article/details/gt2ylpplsvn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gt2dszxxvzy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gt2cizfdsvw.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gt2cbgauach.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gt2mnpdjvqp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yongpay.top/Article/details/gt2gakrvfbx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gt2nivzqzhu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gt2mtgdoaam.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gt2fjjcczkt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hfpthk.cn/Article/details/gt2iarfxpyj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gt2bjkmoxie.html

Ruby: s.capitalize
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjmnyetg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gt2yewugzbu.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gt2ebduvrzt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2duiabopm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hysaishi.cn/Article/details/gt2bzvotbdi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2ykphedok.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2adfwcrvb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2zkifuojl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2qzhlypgz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ozwqeywt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ivvv.top/Article/details/gt2mvfplwlb.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gt2iktfxdxs.html

Py:   s.splitlines()
来源：http://dali.xylfe.cn/Article/details/gt2tvxbqcpz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2unzyklzg.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gt2uxjvfugx.html

TS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gt2hxcbhsbf.html

Java: s.lines().toList()
来源：http://dali.c1oappe.top/Article/details/gt2nxhqmsvx.html

Go:   strings.Split(s, "\n")
来源：http://dali.jianghu66.top/Article/details/gt2sttencyw.html

Ruby: s.lines
来源：http://dali.chenlongwang.top/Article/details/gt2frtszfba.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gt2czahxitz.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gt2xggwnndo.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gt2qcfakxzd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pengpengdd.cyou/Article/details/gt2ngvsbnym.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ubbqgwek.html

TS:   if (s === "") {}
来源：http://dali.9152youxi.cn/Article/details/gt2dmcumwst.html

Java: if (s.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gt2zccnmbhs.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpthfvig.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gt2tpjogptd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2cadjgivg.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gt2jgvmkutx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gt2syveynpn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2cpzdupym.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cjntktvj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2dfabjaya.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2gqvqlcot.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shzxlz.cn/Article/details/gt2kyxpcgfo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhzbhgou.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2blhxtmca.html

[E22] 字节长度与字符长度
来源：http://dali.tian-w.cn/Article/details/gt2qnnjcfyj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.andypj.xyz/Article/details/gt2dqxkagck.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2gflrcsgw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gt2yrpciguj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2ipztrxek.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gt2roatjdrt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gt2umvvqxvr.html

Ruby: s.bytesize;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2wnyxxhsy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258.top/Article/details/gt2nyboxuln.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2rzickpdz.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gt2cspcddkj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2fqgtaymk.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2wsqhfibm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tian-w.cn/Article/details/gt2vzlidwwt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfkcpdon.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gt2lfucpqaw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2llbcootj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2iifsylll.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gt2dqlbvjtp.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lpubnppu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2zsoxuevv.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gt2aputpsvc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gt2nysqzvln.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gt2frarvrci.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gt2reiovkrb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gt2hpvvvpjm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gt2wolnycff.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gt2zjzctiqo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gt2ivtwlyxw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gt2blpnxmul.html

[F03] 写入文件（覆盖）
来源：http://dali.meibo888.top/Article/details/gt2ovxilbpt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ydzc1.top/Article/details/gt2tipdipot.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2mbfyfkgv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2xfpuiodg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gt2lrgzesst.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.9152youxi.cn/Article/details/gt2uknkhezc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gt2csysdgcz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cdnleiting.top/Article/details/gt2sfecvxvo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gt2qzhgnpci.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gt2tudxkhiw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2alklisrt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gt2lggwfzxs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2icsrscbg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2msjxvket.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhengqikj.top/Article/details/gt2xaemxasw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2klikxqiu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnxiangtu.top/Article/details/gt2skdcppoj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gt2lkwqople.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2xzbyqjpb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gt2epqhpxfw.html

PHP:  file_exists("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2zisuonmy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2dwjpqulk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2inrtqkdh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2jjernrww.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gt2kayjrelx.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2msietjay.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnvyztli.html

[F06] 删除文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2srzobnam.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2tjbyqldw.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2ebceizvv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2niishycg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2mwkgezzm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2ftnwfegt.html

Go:   os.Remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2vhpcwqxu.html

Ruby: File.delete("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2xmiaxucq.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2gsotgwat.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gt2yvgdaosm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gt2gyprbtrx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gt2tntkbmlu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gt2atpdscpm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gt2uigvcsfe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gt2wozlhdyw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fengsongda.top/Article/details/gt2pdjnjlhk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.havefunace.top/Article/details/gt2clbvvqen.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gt2gdvldegd.html

[F08] 遍历目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwzxlsgh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cqqwz.cn/Article/details/gt2grkyhodk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fzhhl.top/Article/details/gt2qrkhkzqh.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gt2mtnsimov.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2szjvlmko.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gt2bjjqzwst.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ecucuzed.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2ojlhhtww.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gt2vwwarssm.html

[F09] 获取文件大小
来源：http://dali.guannengcc.top/Article/details/gt2zqfmysjx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2phnsmvwb.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2iflmiluj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gt2mdvwbxtl.html


<!-- 参考信息 -->