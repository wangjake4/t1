代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hecoskpj.html

Ruby: arr.include?(x)
来源：http://dali.ppjwa.cn/Article/details/gt2mtlbnzus.html

C#:   list.Contains(x)
来源：http://dali.yonumen.top/Article/details/gt2lcvwchve.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gt2mhzcyroa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2bhsazcic.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tanke756.top/Article/details/gt2xpzucboi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2pzjfgndh.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gt2efvzpbqa.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gt2mdsyuaii.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvjskaii.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odgqiatq.html

C#:   new List<int>(list);
来源：http://dali.fzhhl.top/Article/details/gt2utzsqkem.html

[D23] reduce 累积计算
来源：http://dali.hongshengwenyu.top/Article/details/gt2wiuneslq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2guysceiy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gt2kutlwdvp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2ozznmscz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2rkgtyzzv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhixingplan.top/Article/details/gt2oawkpsob.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gt2wdovtdqo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gt2stnncmpr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gt2ayugsphc.html

[D24] 字典 / Map 基本操作
来源：http://dali.quarkkingdee.top/Article/details/gt2sboksyql.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gt2qngfniur.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2voogjzio.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.birdmap.top/Article/details/gt2cdvqgpoj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2tzpowbao.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gt2idwmttwu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gt2gmsagmrv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwkmwbfy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangshuangyany.cn/Article/details/gt2kiqpgpxf.html

[D25] Set 集合去重与交并差
来源：http://dali.xuetiantiany.cn/Article/details/gt2gloydblq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sweek.top/Article/details/gt2frwyfgln.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gt2twerwlmj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2blgtmptj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gt2kfemtzmp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2asgnixlr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xziqi.cn/Article/details/gt2mwywygeh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2dihixfsd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gt2sgrpehof.html

[D26] 数组转字符串
来源：http://dali.hywenlv.cn/Article/details/gt2vzmmngwo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gt2dvuwrcdy.html

PHP:  implode(", ", $arr);
来源：http://dali.hammf.cn/Article/details/gt2djctnxwn.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gt2shswbzpy.html

TS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gt2mmnxkyeb.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gt2elqnlbvf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gt2fcartlba.html

Ruby: arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gt2fdofpvhm.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gt2gthvaovy.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2bjhzzsnw.html

E. 字符串处理
来源：http://dali.gogol.net.cn/Article/details/gt2abbuemdo.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2bthfnstm.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhihuuqa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gt2pllvwivb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2moawxuss.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gt2jdltzxnk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gt2fbgwkirb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhoulong.xyz/Article/details/gt2xrgqrjag.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gt2ejriohfb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258888.top/Article/details/gt2mfhambzt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2npzqrzfo.html

[E02] 重复字符串
来源：http://dali.andypj.xyz/Article/details/gt2jglygugc.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2wjyxwabj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2ulwvltkn.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gt2cggpzjln.html

TS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2qsgbvumi.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2ghmxpyfz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jiagoushi.top/Article/details/gt2mcmwkknd.html

Ruby: "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gt2geafpuir.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cheryme.top/Article/details/gt2zhwcgqmx.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gt2pbzhylbk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gt2bkfuehfj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2wlscgzgo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2fscacuhb.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2bvycsthm.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2jexwnwkm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.andypj.xyz/Article/details/gt2mfjkkcco.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xylfe.cn/Article/details/gt2wndkzlsr.html

C#:   s.Substring(1, 3)
来源：http://dali.aibaodan.cn/Article/details/gt2jwtmalxu.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gt2szhhkjcs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gt2sqsmthfe.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gt2obtebnnh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.meibo888.top/Article/details/gt2tqggklal.html

TS:   s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2etvjozof.html

Java: s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gt2clqwdluj.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gt2kwyzuezs.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gt2jwcnmxia.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gt2atprbfrb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.haohaochexian.top/Article/details/gt2dxtkkyzk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pgkjgkqj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlaaeenw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2ddcvpknc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2dabqrajo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gt2vwibxwth.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.svipenyu.cn/Article/details/gt2shuxdlon.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2emjdpren.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2iyjxawfq.html

[E06] 替换子串
来源：http://dali.hfpthk.cn/Article/details/gt2lihlrtbb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gt2nhkieoyw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.svipenyu.cn/Article/details/gt2gtnhrbqu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2vownimzk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2kffbjfcy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gt2ugfrnpvh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sztkzony.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2tpmcvify.html

C#:   s.Replace("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2qqrrqxck.html

[E07] 按分隔符拆分
来源：http://dali.fzhhl.top/Article/details/gt2ttzujtaf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gt2ihjvhivy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xatrhntt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xylfe.cn/Article/details/gt2grbmqajm.html

TS:   s.split(",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hlbxiymm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2masdqxsh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.snrcjt.cn/Article/details/gt2wzgmuwgk.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gt2djmqaymu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2khzmcnaf.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gt2yqdlgsyc.html

Py:   ",".join(items)
来源：http://dali.xuetiantiany.cn/Article/details/gt2faqxowrd.html

PHP:  implode(",", $items);
来源：http://dali.gaohongyu789.top/Article/details/gt2zmktzfpt.html

JS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gt2wfdkmwtu.html

TS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jmlkqeyd.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gt2dehpngfw.html

Go:   strings.Join(items, ",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbeiacwt.html

Ruby: items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gt2rsmumsup.html

C#:   string.Join(",", items)
来源：http://dali.yj202588.top/Article/details/gt2iksxyaqf.html

[E09] 去除所有空白字符
来源：http://dali.meibo888.top/Article/details/gt2nerbuoef.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.9152youxi.cn/Article/details/gt2ucbngrhq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2tvmjtolz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jysdpfok.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2bjupicso.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gt2bzudjthb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gt2omhqdfeb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2zwhxnfoq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xinyue.icu/Article/details/gt2ldgaegbc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gt2gefgycsp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2irijklbb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.svipenyu.cn/Article/details/gt2olywknvs.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2yypwnxnc.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gksgyhwm.html

Java: String.format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gt2mapmnwmi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gt2xlciifbj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gt2saibldvs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gt2zaurzulg.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2ysljfttz.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gt2gbhkejci.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2qavjrrxs.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2xbjwjkdi.html

TS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2ixhxklez.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigufen.top/Article/details/gt2wgoinnch.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yueranfly.top/Article/details/gt2qxigienl.html

Ruby: s.reverse
来源：http://dali.iojbl.cn/Article/details/gt2kpsqgiyk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gt2dzwlylmp.html

[E12] 统计某字符出现次数
来源：http://dali.bjfxy.top/Article/details/gt2qndahuuf.html

Py:   s.count("a")
来源：http://dali.nwbrower.top/Article/details/gt2ughfegpp.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gt2tvnmacmh.html

JS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwaypmib.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gt2paspyfgi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guannengcc.top/Article/details/gt2hbzxwewe.html

Go:   strings.Count(s, "a")
来源：http://dali.zdqjudy.top/Article/details/gt2bmcxiqmy.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gt2skegnmyv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gt2cmdvmysx.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gt2yjkqlkkj.html

Py:   for ch in s: print(ch)
来源：http://dali.cqqwz.cn/Article/details/gt2uenzaplw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fdzlhipq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2rizwztna.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gt2dpatcetu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ofpazhut.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gt2lyfvqxzt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gt2wobkyhpl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2oqlvgmqv.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gt2teegbalp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gt2wxvkzpdp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2faclqdkx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxinkj.top/Article/details/gt2wfzfxpli.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.svipenyu.cn/Article/details/gt2vjhhaudd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2uxkjenfp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gt2wxmimphc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ytxfccxr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.bjfxy.top/Article/details/gt2alhrcrcq.html

[E15] HTML 转义 / 反转义
来源：http://dali.aizwys.cn/Article/details/gt2zpycctoh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gt2cdmaashh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gt2klpqxaon.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gt2ikgwjfwl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gt2edremhzo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gt2uysrizfj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2mrxycpwg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wdoqdili.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gt2ziwaoupm.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbicedvb.html

Py:   f"{1234567:,}"
来源：http://dali.bjfxy.top/Article/details/gt2usrhoitu.html

PHP:  number_format(1234567);
来源：http://dali.yangfankeji.com/Article/details/gt2dwayewkg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gt2cfwasliq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gt2kfwjfxpj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.andypj.xyz/Article/details/gt2lgkfqlgu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2mttbaabn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gt2bnllmilp.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gt2vswuhsno.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gt2zphniesc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gt2emsxyuwe.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2vxxcheti.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2vqxenymd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gt2cfrgigdd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gt2pxycwpej.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2qaarfxge.html

Ruby: s.capitalize
来源：http://dali.hammf.cn/Article/details/gt2ybnjaxgk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gt2tquybtmc.html

[E18] 模板占位符替换
来源：http://dali.xinyue.icu/Article/details/gt2wodztmln.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daxiang520.top/Article/details/gt2ndqutexu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gt2prlkfgau.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2yygzodeu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2qvlqqlgp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2iszkgemm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gt2sgtqxkww.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gt2svbbgcwy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gt2dtsjlhcn.html

[E19] 多行文本按行拆分
来源：http://dali.xylfe.cn/Article/details/gt2xdcxbegm.html

Py:   s.splitlines()
来源：http://dali.andypj.xyz/Article/details/gt2esuvumwi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2gfdktajx.html

JS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gt2cjrohwuc.html

TS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gt2kpdyynxw.html

Java: s.lines().toList()
来源：http://dali.fengsongda.top/Article/details/gt2wqkwffur.html

Go:   strings.Split(s, "\n")
来源：http://dali.mhx1999.top/Article/details/gt2zykiqjqu.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gt2llyutamz.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gt2ekamfrps.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gt2atalpuwc.html

Py:   if not s:
来源：http://dali.zhengqikj.top/Article/details/gt2kswcwkss.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pengpengdd.cyou/Article/details/gt2pussyjph.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gt2vtijhyym.html

TS:   if (s === "") {}
来源：http://dali.nanxuanxn.top/Article/details/gt2padviiyx.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gt2hxmiyaex.html

Go:   if s == "" {}
来源：http://dali.yangfankeji.com/Article/details/gt2hzindkru.html

Ruby: if s.empty?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2coxlyrql.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ehwqpu.com/Article/details/gt2caqcvppm.html

[E21] 超长截断加省略号
来源：http://dali.yonumen.top/Article/details/gt2kczymyqh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gaohongyu789.top/Article/details/gt2mwvtpixn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lmruqiti.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2tdgfljkg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxvvarwl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2dvkcpvbf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gt2kgpuehfm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmsifldd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2gclrpnwo.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gt2injvlqsd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnqzz.top/Article/details/gt2ugjmoqkd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gt2mkguocnz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gt2ysaaghvc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cakhesjl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gt2topxxmsn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.havefunace.top/Article/details/gt2oyjrapbj.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2daxqxqqq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gt2xoifacin.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2zajykmvm.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kqztikaa.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2deryyptq.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gt2niqwgqwk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxuanxn.top/Article/details/gt2rusurndn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2rqzrxish.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sysykeji.top/Article/details/gt2dmlyowkj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2xuwjtcrh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gt2stvgzgbj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gt2zkemjmjk.html

Ruby: File.read("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2sbpuhqql.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2depzauay.html

[F02] 逐行读取文件
来源：http://dali.jinqigfzy.top/Article/details/gt2zfapapdr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2zuelqwck.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gotoacloud.top/Article/details/gt2rbjgirgr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gt2qpuhpvjy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gt2hzqrrmwd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gt2tolsbqfj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigufen.top/Article/details/gt2urmoemdu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrfryzqh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gt2wjtomohe.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkigxvkc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gt2yrsehtzi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gt2rdkwjker.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gt2hvqgivpm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2mhtynmoo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aizwys.cn/Article/details/gt2fxflrszg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrnuviaj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gt2kkhipxtf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gt2couhvuwp.html

[F04] 追加写入文件
来源：http://dali.zdqjudy.top/Article/details/gt2sdkxnbod.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sweek.top/Article/details/gt2mpeyffob.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqdbixef.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gt2cwzksbbj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gt2pyjjqewq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hpurhsks.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2gxyiexrh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gt2thpamkcf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhiwuduotai.top/Article/details/gt2viholkka.html

[F05] 判断文件或目录是否存在
来源：http://dali.jianghu66.top/Article/details/gt2bzzcjdkv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhongyouzk.top/Article/details/gt2yyoxyjzc.html

PHP:  file_exists("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2jjeemsnp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2kbplzdit.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2nmyfqkal.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2dfnilsgw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gt2ndgjlxbk.html

Ruby: File.exist?("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2uzvfhcqo.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2vwtgogya.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gt2imrkhudx.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2upmzmkxe.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2mtedosnd.html


<!-- 参考信息 -->