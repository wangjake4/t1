代发 wailian999

[D19] 按字段分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2altnpyvk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.havefunace.top/Article/details/gt2gamwwxyt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aizwys.cn/Article/details/gt2rcvenxwv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigufen.top/Article/details/gt2ttigdgrf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gt2hkkeqojs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yonumen.top/Article/details/gt2bqmhzhaf.html

Go:   // 手写 map[string][]T
来源：http://dali.yangfankeji.com/Article/details/gt2grpemwil.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jspulkne.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxkbiinu.html

[D20] 统计每个元素出现次数
来源：http://dali.quarkkingdee.top/Article/details/gt2ddiokiuf.html

Py:   Counter(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2xvnnuxzx.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gt2pevxwffq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gt2ortuviwk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gt2yivofvxy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2urvonwhz.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rlodsqmt.html

Ruby: arr.tally
来源：http://dali.hysaishi.cn/Article/details/gt2iaivytlg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gt2abmjejhh.html

[D21] 判断是否包含某元素
来源：http://dali.nanxuanxn.top/Article/details/gt2dpxbzbgj.html

Py:   x in arr
来源：http://dali.fengsongda.top/Article/details/gt2bbfmlkcv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.0kj1m.cn/Article/details/gt2eplvxlji.html

JS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2vrykocjp.html

TS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gt2rluprndu.html

Java: list.contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2tnyeuqez.html

Go:   slices.Contains(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2cmgsfrof.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2fvnoxcmv.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ppwgjngk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tianlin.xyz/Article/details/gt2hkpgqdkv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2gnrpeufw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2icgnjsip.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2qzgoldgz.html

TS:   [...arr];
来源：http://dali.wangdashe.top/Article/details/gt2amyggfrk.html

Java: new ArrayList<>(list);
来源：http://dali.andypj.xyz/Article/details/gt2kdpgdbdr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.kuanghao11.cn/Article/details/gt2iosdvinb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnqzz.top/Article/details/gt2jtkgxuwk.html

C#:   new List<int>(list);
来源：http://dali.jlsjyb.cn/Article/details/gt2bccmxjhc.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gt2mfzwvnxi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2quwpfcnw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2lfsrrojb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2wasvlgaj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2klibynrg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gaohongyu789.top/Article/details/gt2wzsgbxwa.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gt2sjnnbxwp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gt2uivenpck.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gt2zmaezfop.html

[D24] 字典 / Map 基本操作
来源：http://dali.daria6918.cn/Article/details/gt2hxufjxug.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gt2btbpqyyh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgfzy.top/Article/details/gt2cwzlogvl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gt2zzigrnqz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kgqgxhfk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jyoumei.cn/Article/details/gt2giglzlfh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gt2xszqnkgk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gt2tpmfclij.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgufenzy.top/Article/details/gt2cwtdwhfv.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gt2jjmlwpii.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gt2eawyzumn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gt2ucslcuzm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2voqjugqz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zymjjhbp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2xzxybtjx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gt2elhkixef.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fzhhl.top/Article/details/gt2fnpjklqn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gt2ukyrnxlq.html

[D26] 数组转字符串
来源：http://dali.shzxlz.cn/Article/details/gt2mlnsvyqc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sysykeji.top/Article/details/gt2krtrhyxs.html

PHP:  implode(", ", $arr);
来源：http://dali.c1oappe.top/Article/details/gt2wyygrylw.html

JS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2cmoocnrv.html

TS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmrrfjvd.html

Java: String.join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gt2coqjpzah.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2likxaohy.html

Ruby: arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jysohvns.html

C#:   string.Join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gt2wjdppkaw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2oyrdnuzl.html

E. 字符串处理
来源：http://dali.hfpthk.cn/Article/details/gt2komiethy.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2eahpxucg.html

[E01] 拼接字符串
来源：http://dali.hammf.cn/Article/details/gt2jmilgmzn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggzhoelq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2zqqawtis.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gt2alrwkcph.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gt2mkzzyjfb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.iojbl.cn/Article/details/gt2rbhllfej.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.0kj1m.cn/Article/details/gt2jeqieuck.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.havefunace.top/Article/details/gt2eplowplm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2uqikoihr.html

[E02] 重复字符串
来源：http://dali.ehwqpu.com/Article/details/gt2kdppminm.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gt2zmxycfdo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2mtjddzsj.html

JS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gt2cqbtobbg.html

TS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gt2wellsldv.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2gxqmyktl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigufen.top/Article/details/gt2wjwfzned.html

Ruby: "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gt2fovbvzqr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guowangkeji.top/Article/details/gt2hvriuzfd.html

[E03] 截取子串
来源：http://dali.jyoumei.cn/Article/details/gt2loofevwp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hysaishi.cn/Article/details/gt2yrkadbgp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2pkcbbswh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gt2fvhghaaw.html

TS:   s.slice(1, 4)
来源：http://dali.yj202588.top/Article/details/gt2mfbmxutd.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gt2jlyffhvg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkffzesy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nwbrower.top/Article/details/gt2mefhytib.html

C#:   s.Substring(1, 3)
来源：http://dali.jiagoushi.top/Article/details/gt2vdunklqj.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qqtopvpm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2ehlopxiw.html

PHP:  strpos($s, "x");
来源：http://dali.jlsjyb.cn/Article/details/gt2ovwtxlux.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.smart0.xyz/Article/details/gt2qeffujjk.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gt2ytwhvdvv.html

Java: s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwifwpjc.html

Go:   strings.Index(s, "x")
来源：http://dali.zhengqikj.top/Article/details/gt2ydqrrjzl.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2lomeiwkw.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2ecjdryrr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenzaomai.com/Article/details/gt2capeyewf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj202588.top/Article/details/gt2xnrrvein.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dianchejie.cn/Article/details/gt2zljnvzre.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hegmtbpy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.andypj.xyz/Article/details/gt2anutsnba.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2zsyjwosg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ybcxt.top/Article/details/gt2etinckmc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.smart0.xyz/Article/details/gt2nokwlnqx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gt2qxiunuow.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gt2slhrjhzh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqkmmifv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yvedp.cn/Article/details/gt2zuqnkgwk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2liflhjdx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2decttuxs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2zshvvoff.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2xowunqql.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2sztcxhba.html

C#:   s.Replace("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2cogtzphq.html

[E07] 按分隔符拆分
来源：http://dali.jqgfzy.top/Article/details/gt2lvbmnpin.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gotoacloud.top/Article/details/gt2jjvhewbn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2tujfdulk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2pbjyafwu.html

TS:   s.split(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbfaekzx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.birdmap.top/Article/details/gt2iezftrvw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ppjwa.cn/Article/details/gt2gtkdbwsr.html

Ruby: s.split(",");  s.split
来源：http://dali.hywenlv.cn/Article/details/gt2nwkckcxj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhixingplan.top/Article/details/gt2lurxurux.html

[E08] 数组按分隔符合并
来源：http://dali.dashuyun.cn/Article/details/gt2skfvqjwz.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gt2iqpvrlbo.html

PHP:  implode(",", $items);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ypmqdxga.html

JS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gt2ztrnjcrn.html

TS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uztpwesh.html

Java: String.join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gt2togfqqmg.html

Go:   strings.Join(items, ",")
来源：http://dali.daria6918.cn/Article/details/gt2ecyelxkv.html

Ruby: items.join(",")
来源：http://dali.cucudq.cn/Article/details/gt2mmrcbdga.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gt2mkvqdqzf.html

[E09] 去除所有空白字符
来源：http://dali.9152youxi.cn/Article/details/gt2kuaodtoq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kxsfmhhf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2ktxarjtw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gt2icayrxhn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gt2lpnnzfeu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuanzx.com/Article/details/gt2qkquisfy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj202588.top/Article/details/gt2wyqwffrx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2aypviurh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fzhhl.top/Article/details/gt2cwfaidva.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hfpthk.cn/Article/details/gt2ogookymf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zkacswjj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.redwolf501.top/Article/details/gt2owornfnf.html

JS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2facmpdko.html

TS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2kzikxwli.html

Java: String.format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2wbjyoawj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2qvtftgfk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gt2nwnujqkl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbzdhicw.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2kootfpfn.html

Py:   s[::-1]
来源：http://dali.hnqzz.top/Article/details/gt2cyiuglqi.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gt2vwyqcugh.html

JS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gt2ipxylgly.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2ygpvlmkv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xylfe.cn/Article/details/gt2dmnydnyl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guannengcc.top/Article/details/gt2sjbnywiw.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gt2loqjllhz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gt2pzeorntp.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258888.top/Article/details/gt2aiheqhvj.html

Py:   s.count("a")
来源：http://dali.wangdashe.top/Article/details/gt2vcvqwijp.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gt2amdvzyay.html

JS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gt2iajeubia.html

TS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gt2swaqdypt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tian-w.cn/Article/details/gt2bfstvmcu.html

Go:   strings.Count(s, "a")
来源：http://dali.zdqjudy.top/Article/details/gt2mbbgealv.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gt2nxqdnskz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tanke756.top/Article/details/gt2uebxjeik.html

[E13] 逐字符遍历
来源：http://dali.zdqjudy.top/Article/details/gt2zaqjvvpx.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gt2cremxxod.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gt2axdfmwgt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gt2fijsqean.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gt2jpwsgrgc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2rckocbuo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gt2rjvbfrwu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fengsongda.top/Article/details/gt2lxlebavj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gt2apblqfyw.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gt2kohxkwim.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gt2byifplvd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gt2elpnizpb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxinkj.top/Article/details/gt2jsnnzfsi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2qscprufz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2wtfmwsly.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gt2tnbtcwsr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gt2whlirxco.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gt2navenfdo.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gt2btmcekyp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gt2lyukgwrr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2zmerpcrg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2wienmxun.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.birdmap.top/Article/details/gt2osbiaxgd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cdnleiting.top/Article/details/gt2ihbnxkki.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gt2kolcjyyb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gt2wisbijjo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuxming.cn/Article/details/gt2fpdfdxki.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gt2yvpdiajn.html

Py:   f"{1234567:,}"
来源：http://dali.gaohongyu789.top/Article/details/gt2eicdzhwk.html

PHP:  number_format(1234567);
来源：http://dali.xinyue.icu/Article/details/gt2ttjktxam.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gt2oowpnqou.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gt2rdcekdjl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wekdhtqb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gaohongyu789.top/Article/details/gt2fvzeagzi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2jtyhllqb.html

C#:   1234567.ToString("N0")
来源：http://dali.hysaishi.cn/Article/details/gt2arqtewoc.html

[E17] 首字母大写
来源：http://dali.jyoumei.cn/Article/details/gt2wgwnfxal.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pycfn.com/Article/details/gt2pjvasmzf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gt2iiekutss.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gt2qfwdkine.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gt2ftncaevx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2oldmjsng.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2krqauzso.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmismyrn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gt2esgaxwox.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gt2uzmgrqxb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shuidangran.top/Article/details/gt2twmrqcjp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gt2hajcgetb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rxrptalf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2loywfyko.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lknplkaa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2ntdsynvc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gt2qpnhfalb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgfzy.top/Article/details/gt2lcnvnpfe.html

[E19] 多行文本按行拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlcxyvtf.html

Py:   s.splitlines()
来源：http://dali.gogol.net.cn/Article/details/gt2xhwjwicw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gt2atzxpfvw.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gt2ettgtdrx.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gt2zppafokf.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqiqyrht.html

Go:   strings.Split(s, "\n")
来源：http://dali.hywenlv.cn/Article/details/gt2zuaaoinz.html

Ruby: s.lines
来源：http://dali.ppjwa.cn/Article/details/gt2ukibhpgi.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gt2aqujwpqj.html

[E20] 判断字符串是否为空
来源：http://dali.xinyue.icu/Article/details/gt2finhwsot.html

Py:   if not s:
来源：http://dali.haohaochexian.top/Article/details/gt2dakirasf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gt2njfazeti.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gt2yatbpojx.html

TS:   if (s === "") {}
来源：http://dali.yueranfly.top/Article/details/gt2oagoquim.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gt2mpxdznhp.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gt2cbsraevw.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gt2rupukyjb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gt2tnifgpfv.html

[E21] 超长截断加省略号
来源：http://dali.316326.xyz/Article/details/gt2nppghkxv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gt2sezcoelo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2czhzumrx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2oafddrei.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2mwecxcmw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2vnwznlkd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gt2ayobrczv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2xfkahbbs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gt2aeexmkpq.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gt2vjqanuci.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2oudlrpjf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2lqkoyabr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2sjtohwbg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gt2ooiqciom.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gt2vbhnccrg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gt2kxjaqvtu.html

Ruby: s.bytesize;  s.length
来源：http://dali.hfpthk.cn/Article/details/gt2uuaqtgsc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gt2prdimpzl.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ldfinqde.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2mesyxscs.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2mfgqmcbb.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gt2gdfxmtky.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gt2nmhycjas.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2tnijvpfx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gt2ltrtecpt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gt2fwgvnkiv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2qikagzhg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gt2wwabvmri.html

Ruby: File.read("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2npnmxxxz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2jiphzyrn.html

[F02] 逐行读取文件
来源：http://dali.yvedp.cn/Article/details/gt2kxjodhxz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvdzgtwi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gt2thxnzmhk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gt2ogloixey.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gt2zlgimijx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gt2uubizedm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gt2bqlazlnh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gt2vjjfbbas.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gt2kgqptaas.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gt2tvarbnjz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daria6918.cn/Article/details/gt2lremlpom.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gt2siqtgpxh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gt2kparzkao.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gt2hjunlmip.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gt2muopzawg.html


<!-- 参考信息 -->