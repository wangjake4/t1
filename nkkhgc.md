代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gt2nwlaxehv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yongpay.top/Article/details/gt2zsipgktp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gt2qjqahztx.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gt2davctzjd.html

[D23] reduce 累积计算
来源：http://dali.ydzc1.top/Article/details/gt2oxxxrnan.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daria6918.cn/Article/details/gt2czpoprdn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.meibo888.top/Article/details/gt2ivxkbvzw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2yvzfaurb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2rctkepoa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guowangkeji.top/Article/details/gt2zpkaenzo.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gt2bxiqnncs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gt2knpcbpjm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yueranfly.top/Article/details/gt2qutmatjf.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubynmfdf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.svipenyu.cn/Article/details/gt2kszgeefb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2fklyxwbo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuanzx.com/Article/details/gt2enxbrcou.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2kfbkrjvq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj202588.top/Article/details/gt2rwprcpev.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gt2vcvaxaek.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnqzz.top/Article/details/gt2ufgbsdih.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hysaishi.cn/Article/details/gt2hmucsphf.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gt2dkmiuarf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shuidangran.top/Article/details/gt2ogiwsboh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shangyingyoupin.top/Article/details/gt2caakvlqt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xziqi.cn/Article/details/gt2puvbxfqd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxvvaopu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guannengcc.top/Article/details/gt2pmkkxnbn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cqqwz.cn/Article/details/gt2nlsnsynv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gt2kbcsyrgs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aibaodan.cn/Article/details/gt2mjiqrrce.html

[D26] 数组转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2nvinlyfm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2xnjihdfn.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcwbtlxw.html

JS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gt2gmrgkvet.html

TS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gt2yillxggh.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gt2elkvllgj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tyysmscg.html

Ruby: arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2gklmffaj.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gt2wimzwzhi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2jwxjzfrm.html

E. 字符串处理
来源：http://dali.zycfv.cn/Article/details/gt2omfzkpxq.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ftbsvhym.html

[E01] 拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gt2knlizkvy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.snrcjt.cn/Article/details/gt2funftvvt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gt2elezzstk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gt2gddoqoxh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2guenkuni.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.kuanghao11.cn/Article/details/gt2gljgupdr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ppjwa.cn/Article/details/gt2emscdkxx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxmvpxaa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2ffqcaqdb.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2jacmntxx.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gt2mfzufrqh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pycfn.com/Article/details/gt2kqlecdmg.html

JS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gt2vpodtbuc.html

TS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gt2swhcriym.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2zpsnhcpj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.c1oappe.top/Article/details/gt2zoskngdu.html

Ruby: "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gt2gfnbycjk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gt2zbufaoxv.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gt2awhmvfxg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gt2rnuxtfdb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gt2opilhybz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2wqwvqsyq.html

TS:   s.slice(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwbmbvld.html

Java: s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2oicvcxoo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.bjfxy.top/Article/details/gt2slwsvpsq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gt2aoalfzcv.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2axpsrddd.html

[E04] 查找子串位置
来源：http://dali.chenlongwang.top/Article/details/gt2swcstxvs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2bzcuslqf.html

PHP:  strpos($s, "x");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ybompzww.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xziqi.cn/Article/details/gt2secfosbh.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2kqmbwatx.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2sevmiyxb.html

Go:   strings.Index(s, "x")
来源：http://dali.fengsongda.top/Article/details/gt2rkotbuyv.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gt2ihxkvoxr.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2htxbwiwr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sxryk.cn/Article/details/gt2mxykcwzq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fengsongda.top/Article/details/gt2wtrgzqxp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ehwqpu.com/Article/details/gt2wprxwhit.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuyawsxn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2zchumovx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xglqtzez.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxuanxn.top/Article/details/gt2vopavsch.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dianchejie.cn/Article/details/gt2rttypygz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2syvtmara.html

[E06] 替换子串
来源：http://dali.cqqwz.cn/Article/details/gt2kruafrrs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gt2zkymrlod.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2arlsphio.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2pffqsvuv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2ipnbfhvo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2spdlcler.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gt2johbgtim.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggvqykee.html

C#:   s.Replace("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ccuihcbg.html

[E07] 按分隔符拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2tapflkrl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.andypj.xyz/Article/details/gt2xamzugpr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2omglfmnn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guannengcc.top/Article/details/gt2pbtpcjpd.html

TS:   s.split(",")
来源：http://dali.yj20258888.top/Article/details/gt2blvhfeti.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenlongwang.top/Article/details/gt2oizvowgd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daria6918.cn/Article/details/gt2vnomqjeq.html

Ruby: s.split(",");  s.split
来源：http://dali.chenzaomai.com/Article/details/gt2xtzlnuar.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gt2ddlkcdbf.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gt2mkubbufq.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gt2hmcvzuky.html

PHP:  implode(",", $items);
来源：http://dali.sufxvd.cn/Article/details/gt2vxnllook.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtkorfik.html

TS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2jczmfvff.html

Java: String.join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gt2btqeatuy.html

Go:   strings.Join(items, ",")
来源：http://dali.fzhhl.top/Article/details/gt2bfqwmcai.html

Ruby: items.join(",")
来源：http://dali.xziqi.cn/Article/details/gt2vvxwcjjl.html

C#:   string.Join(",", items)
来源：http://dali.hnqzz.top/Article/details/gt2fvnhwnoz.html

[E09] 去除所有空白字符
来源：http://dali.9152youxi.cn/Article/details/gt2kosqirld.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.316326.xyz/Article/details/gt2tstlhdmi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gt2smpwxmmq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gt2clgxnorh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gt2zvcdccds.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2ggmboyns.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.316326.xyz/Article/details/gt2lbeeivdp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2sxkfohoo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gt2gokfazkt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gt2zulmyasa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2hzomasnw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sufxvd.cn/Article/details/gt2olcpeppi.html

JS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2uozrggkw.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2clgqlvle.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gt2cqutanok.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2xtnnteyj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gt2lkvgqyqm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pycfn.com/Article/details/gt2ttfwdpak.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gt2pishxqpp.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gt2uohzyncv.html

PHP:  strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gt2xdkwjebm.html

JS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gt2hxieysaf.html

TS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gt2rewpqqmz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gt2obezeolx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gt2kjuuoxha.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gt2gtpypnaa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gt2ckrytywd.html

[E12] 统计某字符出现次数
来源：http://dali.hnxiangtu.top/Article/details/gt2filtffzb.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gt2tzgvuxuy.html

PHP:  substr_count($s, "a");
来源：http://dali.daria6918.cn/Article/details/gt2mmxkjyvt.html

JS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ydbmxszy.html

TS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gt2uzzcpuuj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.feifeiyinyue.top/Article/details/gt2eobgnmqn.html

Go:   strings.Count(s, "a")
来源：http://dali.sxryk.cn/Article/details/gt2rkahwkwi.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gt2dmawbexa.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptlksxvy.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gt2vcynmmfd.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gt2ypxcioym.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gt2lvhrcunr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2fnhlghkt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gt2tmbrngrh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wlixstxk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gt2glvvlrwe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gt2ehrmqsta.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2toxivkcu.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gt2ytqsnzkm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.kuanghao11.cn/Article/details/gt2nllohisz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2yzmxvunm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gt2upwnewmo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gt2tuchntnx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uetihtiw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gt2xxdrohgm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2umgutjzb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gt2wvupaaum.html

[E15] HTML 转义 / 反转义
来源：http://dali.aibaodan.cn/Article/details/gt2qslpsdqi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmtzuyru.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fengsongda.top/Article/details/gt2kdvyzcoh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txlpvbdm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuxming.cn/Article/details/gt2vwefgqil.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gt2vpyviose.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2fpjnfbyz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gt2fvmxkehd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xylfe.cn/Article/details/gt2mnhdhhub.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gt2pkvfsjxa.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gt2krzgtxoh.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehtaaugv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2rofaskvp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfjoutaw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mbqgojcs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gt2nhyfvrgd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.iojbl.cn/Article/details/gt2ehbqadds.html

C#:   1234567.ToString("N0")
来源：http://dali.gogol.net.cn/Article/details/gt2whjqvvuy.html

[E17] 首字母大写
来源：http://dali.sufxvd.cn/Article/details/gt2axgkwqei.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhengqikj.top/Article/details/gt2eudmgtjo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.9152youxi.cn/Article/details/gt2psazwihe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gt2wspwkvvy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gt2fqwhkorc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yonumen.top/Article/details/gt2mcmfbkob.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gt2pdgutiwz.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gt2wxoautwm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pengpengdd.cyou/Article/details/gt2zclteias.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2vmdmewzc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yanxiufei.cn/Article/details/gt2haekucse.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gt2rpjjnjmm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2clnpfbqq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2zzxpzsmd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2hotgmxxy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2wqgywsiv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lglqnwlf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2xpjeumhi.html

[E19] 多行文本按行拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2bfngpalp.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gt2xwdfbuck.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258.top/Article/details/gt2gjnxhryt.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gt2hgagsjay.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gt2adheyoxn.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gt2ludwsagl.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gt2shhagzaf.html

Ruby: s.lines
来源：http://dali.gzhubu.top/Article/details/gt2vtyqwppg.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fcarjsrm.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gt2wqtxmemu.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rcpzcwnu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gt2cqrrsepy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gzhubu.top/Article/details/gt2azilureq.html

TS:   if (s === "") {}
来源：http://dali.shuidangran.top/Article/details/gt2ehemmjhn.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2cjmvbdcq.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gt2iqompfva.html

Ruby: if s.empty?
来源：http://dali.pycfn.com/Article/details/gt2dbklsrvr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gt2cckswcqg.html

[E21] 超长截断加省略号
来源：http://dali.gaohongyu789.top/Article/details/gt2mkmwapej.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gt2iffftlon.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2ovigrflr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2kkwxylhq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2bhvvyxih.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2mjgtfarz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gt2uzyxdkot.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2jdxpzlpw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdotzmyd.html

[E22] 字节长度与字符长度
来源：http://dali.yangfankeji.com/Article/details/gt2ehdewgym.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tewslgpk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2jnbwagls.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gt2ucirfkpw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmgizike.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tanke756.top/Article/details/gt2flnodjrw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gt2ddariiwd.html

Ruby: s.bytesize;  s.length
来源：http://dali.ivvv.top/Article/details/gt2xxsiikqe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gt2ofuwwwaw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2oefwekrc.html

F. 文件与目录
来源：http://dali.yj20258.top/Article/details/gt2wospmuxd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2rsrjmjns.html

[F01] 读取整个文件
来源：http://dali.zdqjudy.top/Article/details/gt2imglyfiu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fylrmeaw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gt2urcgenmc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hammf.cn/Article/details/gt2vdytlgst.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzfcyjcr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2iwrxihcs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sufxvd.cn/Article/details/gt2rhbvmdcn.html

Ruby: File.read("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2xdgjaowe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2qmtpyebf.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gt2pemqekbc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.mhx1999.top/Article/details/gt2ezbvavld.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gt2gfhikhog.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gt2xvglucya.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gt2bhooaanr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltbkwbnj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenlongwang.top/Article/details/gt2ntamhram.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aibaodan.cn/Article/details/gt2fisxkpzi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.havefunace.top/Article/details/gt2immowgwa.html

[F03] 写入文件（覆盖）
来源：http://dali.0kj1m.cn/Article/details/gt2emthqqdo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gt2qwpgvqyn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2pqcjbaaz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gt2tagmtwfk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gt2mahphphe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2xmbkdyzv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gt2ivjpiofh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnqzz.top/Article/details/gt2bigzeyfn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntuhtglf.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gt2zkosnwtm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2volmvglo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.andypj.xyz/Article/details/gt2wsluztcw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gt2wxtbibkf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gt2cqoxoyid.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.snrcjt.cn/Article/details/gt2ehknidaj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guannengcc.top/Article/details/gt2tnsemeih.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuanzhike.top/Article/details/gt2onqbprvl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dianchejie.cn/Article/details/gt2ghlcjzrs.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gt2wchtwhcg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yongpay.top/Article/details/gt2akknrkuc.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2eseishyq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2iglbgyfm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2aqvpvhxi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzklyzlz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.quarkkingdee.top/Article/details/gt2svigbhoh.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2gqxxshuh.html

C#:   File.Exists("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2xyshknsk.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gt2vsqwgwhl.html

Py:   os.remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2pstmfmsu.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2wowxelsa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2udxcrsvq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2yzabqjdu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2nftbpgnc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2aosrgzho.html

Ruby: File.delete("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2tqrauumr.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2aiwcylch.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gt2fhlofebi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gt2qafkmqxe.html


<!-- 参考信息 -->