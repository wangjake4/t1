代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qfcvibqa.html

[D16] 求和与平均值
来源：http://dali.guowangkeji.top/Article/details/gt2esrykuuk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2ruqivhcd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj202588.top/Article/details/gt2kyleyskc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gt2ysxumwsa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2ctbtqgik.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gt2tdnvjvky.html

Go:   // 手写循环累加
来源：http://dali.tanke756.top/Article/details/gt2wmobleea.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tanke756.top/Article/details/gt2inbrwwrz.html

C#:   list.Sum();  list.Average()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rawdngvp.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzyegfn.html

Py:   max(arr);  min(arr)
来源：http://dali.cashguo.top/Article/details/gt2lghotoeo.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gt2vurhoszj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gt2myolbhrf.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gt2iuueghjd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2sevfgkhf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gt2npzpxqqw.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gt2qejezjgz.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gt2jqamnznp.html

[D18] 扁平化嵌套数组
来源：http://dali.dianchejie.cn/Article/details/gt2tcmbmizq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gt2ffcrmtwl.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gt2bjcsblng.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gt2vnucxbfr.html

TS:   nested.flat();
来源：http://dali.0kj1m.cn/Article/details/gt2rqhzlnpn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2bojykybe.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gt2rmbfnhcl.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gt2janmrhbh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rwetowhg.html

[D19] 按字段分组
来源：http://dali.hfpthk.cn/Article/details/gt2nhtedfhp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zdqjudy.top/Article/details/gt2rczhdnuu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnqzz.top/Article/details/gt2pjzvjwfp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jiagoushi.top/Article/details/gt2droudtjo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gt2ccwdvijz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hywenlv.cn/Article/details/gt2bkmzjooo.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gt2ovuujqaq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gt2ycozzwzy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gt2rbbicyjr.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gt2zeljklyu.html

Py:   Counter(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2wpiapcfb.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2svpjjkxv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gt2eiuvkbab.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gt2cmoswfzs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjuyipve.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gt2kidodthd.html

Ruby: arr.tally
来源：http://dali.jqgufenzy.top/Article/details/gt2oujyddbl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gt2jdxkslnl.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gt2xnfjotxm.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2qvapffsi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fzhhl.top/Article/details/gt2tquaiexu.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2xnlkbghf.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xisfgulv.html

Java: list.contains(x)
来源：http://dali.hammf.cn/Article/details/gt2edtqerhl.html

Go:   slices.Contains(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2klxlwncy.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gt2ruuysoxj.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2dmytibnz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sweek.top/Article/details/gt2djpqfwrk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangdashe.top/Article/details/gt2ncbzupdq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.redwolf501.top/Article/details/gt2jqeqdnzp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ivvv.top/Article/details/gt2zzrdnsdg.html

TS:   [...arr];
来源：http://dali.nwbrower.top/Article/details/gt2bvnfxmta.html

Java: new ArrayList<>(list);
来源：http://dali.andypj.xyz/Article/details/gt2qhxvzxmk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ouxewxbv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yangfankeji.com/Article/details/gt2kaskjlyi.html

C#:   new List<int>(list);
来源：http://dali.daria6918.cn/Article/details/gt2ouuqttrx.html

[D23] reduce 累积计算
来源：http://dali.dianchejie.cn/Article/details/gt2zcxmzdvr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdjsuvu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2bunhabus.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2tkqnzozc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2ljihfnjc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zdqjudy.top/Article/details/gt2zutkwrca.html

Go:   // 手写循环
来源：http://dali.snrcjt.cn/Article/details/gt2yitwoqgf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnxiangtu.top/Article/details/gt2iklilhkl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.9152youxi.cn/Article/details/gt2wxhchptm.html

[D24] 字典 / Map 基本操作
来源：http://dali.hfpthk.cn/Article/details/gt2hqlkaduw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gt2kljsguxu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shzxlz.cn/Article/details/gt2gcpojhba.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2vhdzkzvr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2ojnwtbgp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.meibo888.top/Article/details/gt2wegftyuk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2metheoyo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgufenzy.top/Article/details/gt2ulmmvksg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gt2mwkkximm.html

[D25] Set 集合去重与交并差
来源：http://dali.pengpengdd.cyou/Article/details/gt2xatqpvjr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pycfn.com/Article/details/gt2aetbaoux.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hywenlv.cn/Article/details/gt2lqyvskip.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2whagfjjn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxuanxn.top/Article/details/gt2qshypqxh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gt2jmonjcuq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gt2ywbuqwlu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gt2kwpcufws.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aibaodan.cn/Article/details/gt2gdbsxdzc.html

[D26] 数组转字符串
来源：http://dali.nwbrower.top/Article/details/gt2dsjpqnpf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2hzdtovtx.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2ipvvadrj.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gt2acmgkmmw.html

TS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gt2vfkcuxji.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gt2yzfesbje.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guowangkeji.top/Article/details/gt2sxachrte.html

Ruby: arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gt2eltzwtln.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gt2strltyyj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2gbfmbsnn.html

E. 字符串处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ecfrzhgk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2egcpniye.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2yqmcboah.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jianghu66.top/Article/details/gt2uczztobj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.c1oappe.top/Article/details/gt2ygkddewi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gt2rwgulirk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gt2olwmzrag.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnxiangtu.top/Article/details/gt2aqhlbdzi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daria6918.cn/Article/details/gt2cwtrkwan.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuxming.cn/Article/details/gt2dzlfnwrh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2jifektst.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcqzxmx.html

Py:   "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gt2yumwjnui.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2ddiwpnti.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2lkugilby.html

TS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2vzmmawlf.html

Java: "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2kqqopgbj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gt2ynaiocfr.html

Ruby: "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gt2stpbgqye.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gt2kpcrbrig.html

[E03] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gt2zasmbxlm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jiagoushi.top/Article/details/gt2psgbgket.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gt2bupkonca.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2uwproarb.html

TS:   s.slice(1, 4)
来源：http://dali.sxryk.cn/Article/details/gt2qicotvbk.html

Java: s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2myyrymyg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gt2rqnfckuc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhoulong.xyz/Article/details/gt2xjlvbhqj.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigufen.top/Article/details/gt2lmajoqyb.html

[E04] 查找子串位置
来源：http://dali.zhiwuduotai.top/Article/details/gt2enqkrlsq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gt2dfxyxisp.html

PHP:  strpos($s, "x");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2phsbacrz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tianlin.xyz/Article/details/gt2ofytjycv.html

TS:   s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2szgjycjy.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2actjcvxa.html

Go:   strings.Index(s, "x")
来源：http://dali.jiagoushi.top/Article/details/gt2sfzptwtq.html

Ruby: s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdpqqlod.html

C#:   s.IndexOf("x")
来源：http://dali.daria6918.cn/Article/details/gt2rpwhpwut.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigufen.top/Article/details/gt2ltsratju.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gt2rctceiiu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gt2trpidlts.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2unnrdffm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ehwqpu.com/Article/details/gt2ykowujsq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2luehgbcb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.bjfxy.top/Article/details/gt2focdkkzu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ydzc1.top/Article/details/gt2evskyesn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2iujsyltm.html

[E06] 替换子串
来源：http://dali.daria6918.cn/Article/details/gt2yrwewdet.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gt2jqccmham.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gt2ehpnejbm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2pptdozlx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2dzzghkvp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udkajpxf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2jdeabzqn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2hyzkprsu.html

C#:   s.Replace("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2ivmnljcl.html

[E07] 按分隔符拆分
来源：http://dali.yj202588.top/Article/details/gt2ckedqdtm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gt2baytbkug.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2xcnhddhy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jsnxsmgq.html

TS:   s.split(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2vztnmyys.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ehwqpu.com/Article/details/gt2rrlbgrzl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gt2cgphhfam.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gt2bwskgzzp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.0kj1m.cn/Article/details/gt2klwypbkt.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gt2ldioocjn.html

Py:   ",".join(items)
来源：http://dali.yonumen.top/Article/details/gt2eadvcmkf.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gt2lvqqqfph.html

JS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdvaqlzp.html

TS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2zkpkamri.html

Java: String.join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gt2heruopra.html

Go:   strings.Join(items, ",")
来源：http://dali.gotoacloud.top/Article/details/gt2rjxsjtzh.html

Ruby: items.join(",")
来源：http://dali.jianghu66.top/Article/details/gt2felfcmnm.html

C#:   string.Join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gt2koklkoda.html

[E09] 去除所有空白字符
来源：http://dali.jianghu66.top/Article/details/gt2dysmmolc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lfqzelpn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gt2iaonsdwi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gt2ogfiyzur.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gt2wirtuhxm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daria6918.cn/Article/details/gt2rcpiyuvv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.316326.xyz/Article/details/gt2hidnhumr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigfzy.top/Article/details/gt2idmcsthe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gt2eqbbquea.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oehplhhb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258888.top/Article/details/gt2jprkfdgm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guowangkeji.top/Article/details/gt2bctzxhvr.html

JS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gt2kcdlqock.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrmtilmv.html

Java: String.format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gt2kfzuzxok.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2rkwospzf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gt2yhztbcuc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.kuanghao11.cn/Article/details/gt2gyslmizi.html

[E11] 反转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2bsmqmyxt.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gt2axcaeofb.html

PHP:  strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gt2meiulqri.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqzyujbp.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2fbuydoew.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hywenlv.cn/Article/details/gt2cepmvvvl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gt2yospuhew.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gt2bmpqvwru.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gt2bhkkhgtp.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gt2wvgudbwp.html

Py:   s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zovpaulh.html

PHP:  substr_count($s, "a");
来源：http://dali.jyoumei.cn/Article/details/gt2fpjmptqy.html

JS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2oriwqcwk.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gt2yqgdurxk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenzaomai.com/Article/details/gt2cdzoupca.html

Go:   strings.Count(s, "a")
来源：http://dali.gaohongyu789.top/Article/details/gt2rnbgjivt.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gt2yjjxwfox.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gt2cmbwqypu.html

[E13] 逐字符遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdcestrt.html

Py:   for ch in s: print(ch)
来源：http://dali.vqdsnc.cn/Article/details/gt2gszigrrr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gt2ypibrrgn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2ftdyoces.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gt2nwkfulzl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2nxrtxpbx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gt2krhvjfpw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjdnuaur.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2cpfnrdpz.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vyjewxnm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gt2utyuljsz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dianchejie.cn/Article/details/gt2zojxfmsl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxinkj.top/Article/details/gt2xuowtxkd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gt2bkzugqch.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.haohaochexian.top/Article/details/gt2gcdhdgiq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ydzc1.top/Article/details/gt2azyqcemx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.quarkkingdee.top/Article/details/gt2nsgwgzgb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gt2ivlolads.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gt2nsomirol.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenlongwang.top/Article/details/gt2rdjigyvw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2mlefmviw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj202588.top/Article/details/gt2egynumva.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cyzrdjtd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xylfe.cn/Article/details/gt2fkzemgog.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqsbmpdb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gt2xfxydexe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gt2ykomyzqv.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gt2ytucqtkg.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gt2fdtzwvql.html

PHP:  number_format(1234567);
来源：http://dali.sysykeji.top/Article/details/gt2jzbtoelt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gt2mjloznvs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gt2rdbajauk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gt2msdtuhrv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clrlfcpy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gt2rqnsebbv.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gt2phrxkvjn.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gt2nadkwcfb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fengsongda.top/Article/details/gt2gggpsrkg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhengqikj.top/Article/details/gt2lyxvrglb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gt2cewvhhue.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gt2kicmbmra.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fengsongda.top/Article/details/gt2rqucvnpp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258888.top/Article/details/gt2apnounyl.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gt2biktwfqh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgufenzy.top/Article/details/gt2drdiqbsq.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2amznogdy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.haohaochexian.top/Article/details/gt2oqwqhgif.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gowzadoh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2mmgrcllk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2jarfabvc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2luvvmyih.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2uqycfzqd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gt2zpnumacv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gt2vhztidjy.html

[E19] 多行文本按行拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2donjycfs.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gt2ouclffpi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2ipmbllpg.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqsodxaw.html

TS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gt2lhxkyojv.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gt2zqiqkgxk.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gt2kkzqajhm.html

Ruby: s.lines
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfstbsfq.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gt2vlqjyhbl.html

[E20] 判断字符串是否为空
来源：http://dali.tianlin.xyz/Article/details/gt2sggofpcc.html

Py:   if not s:
来源：http://dali.fzhhl.top/Article/details/gt2nddcfmyj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gt2oqeqopcp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ivvv.top/Article/details/gt2nalotnei.html

TS:   if (s === "") {}
来源：http://dali.quarkkingdee.top/Article/details/gt2evxfvyua.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2itpyusym.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ssovbqpq.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahqjgfsf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gt2kdkkbczb.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oyiiprlc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grtdegsy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2tiblcovc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylzerilx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2qnmxgyxf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohnpuvme.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gt2zadaayia.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gt2cqpabdwp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2lslevlqi.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gt2fsxrdmjg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gt2ssxedngn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2rvvpnfez.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2xugsowea.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2elpddqpt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258.top/Article/details/gt2vlfqclzt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xscrmrjd.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2ijtbkybk.html


<!-- 参考信息 -->