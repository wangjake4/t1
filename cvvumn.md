代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2inqrhoqj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2spwgyjhq.html

JS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2kjrdaxde.html

TS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gt2zhvsrfgm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gt2zoqxwwyu.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gt2rdznprjw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tian-w.cn/Article/details/gt2wdsgimvm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2kzcirnkc.html

[D15] 去重
来源：http://dali.hfpthk.cn/Article/details/gt2ocgopbip.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gt2dqknuodc.html

PHP:  array_unique($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2ohytzopp.html

JS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gt2rqyvzdsr.html

TS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gt2gdyhgazo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gt2wautiypo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gt2cpcgqdai.html

Ruby: arr.uniq
来源：http://dali.havefunace.top/Article/details/gt2urzuaspb.html

C#:   list.Distinct().ToList()
来源：http://dali.birdmap.top/Article/details/gt2dhpmjggv.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhpwoll.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangdashe.top/Article/details/gt2kaytadhs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqlicakh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gt2argsfeps.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mxfioerb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hfpthk.cn/Article/details/gt2aszbjtql.html

Go:   // 手写循环累加
来源：http://dali.hnxiangtu.top/Article/details/gt2cgmwdjwp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cashguo.top/Article/details/gt2fdvffbww.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gt2wmnwnhdo.html

[D17] 最大值与最小值
来源：http://dali.cucudq.cn/Article/details/gt2adxrlojc.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2mlnqbpmu.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibklexel.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gt2ybicjzfv.html

TS:   Math.max(...arr);
来源：http://dali.chenzaomai.com/Article/details/gt2wypyxbcr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xinyue.icu/Article/details/gt2epqebhja.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2srjsvtnm.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gt2lcwerjre.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gt2wwuopzqm.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigufen.top/Article/details/gt2bctbethk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ydzc1.top/Article/details/gt2tvwiyaqk.html

PHP:  array_merge(...$nested);
来源：http://dali.shangyingyoupin.top/Article/details/gt2iqouelpf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gt2kihjkwsd.html

TS:   nested.flat();
来源：http://dali.vqdsnc.cn/Article/details/gt2ukfrpzlu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gt2yfxrfzuh.html

Go:   // 手写双层循环
来源：http://dali.jinqigfzy.top/Article/details/gt2hsmgkgse.html

Ruby: nested.flatten
来源：http://dali.shzxlz.cn/Article/details/gt2hmrzycrl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2hfkmhwey.html

[D19] 按字段分组
来源：http://dali.wangdashe.top/Article/details/gt2kswllwfb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gt2idqlvgrx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258.top/Article/details/gt2qhfptczc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sufxvd.cn/Article/details/gt2cdkrciea.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmtlxtmh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gt2cujzogix.html

Go:   // 手写 map[string][]T
来源：http://dali.daria6918.cn/Article/details/gt2xgytyzmn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yongpay.top/Article/details/gt2qjyxtglu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gt2ktfhyvkh.html

[D20] 统计每个元素出现次数
来源：http://dali.0kj1m.cn/Article/details/gt2oycmhldo.html

Py:   Counter(arr)
来源：http://dali.xinyue.icu/Article/details/gt2tkoezzom.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2rmszbnpl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gt2emcxiran.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czutujum.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gt2uuhhkywf.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gt2ybeihodo.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gt2xduarpsg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gt2inwtpzpn.html

[D21] 判断是否包含某元素
来源：http://dali.cdnleiting.top/Article/details/gt2fwixptws.html

Py:   x in arr
来源：http://dali.ehwqpu.com/Article/details/gt2zlmcfdgb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2ouhmgfne.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gt2khspqlyi.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2npdfwcro.html

Java: list.contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jthpxdll.html

Go:   slices.Contains(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2pcyivnwl.html

Ruby: arr.include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2wyopydzh.html

C#:   list.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gt2vooywuww.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jyoumei.cn/Article/details/gt2nomeeobw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gt2swrrobtk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pengpengdd.cyou/Article/details/gt2kfbjbktf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gt2pjvwnugc.html

TS:   [...arr];
来源：http://dali.jyoumei.cn/Article/details/gt2sbirpfnf.html

Java: new ArrayList<>(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2nzilanfi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2arhoxmri.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shuidangran.top/Article/details/gt2mopxtfwq.html

C#:   new List<int>(list);
来源：http://dali.guowangkeji.top/Article/details/gt2ksmznbaw.html

[D23] reduce 累积计算
来源：http://dali.dianchejie.cn/Article/details/gt2yufetwvz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2bwowmdml.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gt2ckzwjezm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2tcvswfna.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2ertcfjmp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ybcxt.top/Article/details/gt2elwtswzn.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gt2jhpbbowx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tianlin.xyz/Article/details/gt2trrioffx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gt2mvcjrbuh.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mrjnxrsd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hfpthk.cn/Article/details/gt2lmgtpmcd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nwbrower.top/Article/details/gt2exfsdylj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2jllezmxj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cashguo.top/Article/details/gt2jtnkogxm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gt2yvgnulgm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gt2bjcccdtn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gt2zwgylpar.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.meibo888.top/Article/details/gt2baonqkxz.html

[D25] Set 集合去重与交并差
来源：http://dali.tianlin.xyz/Article/details/gt2talsalfl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gt2poaqaepn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shzxlz.cn/Article/details/gt2cvnakguo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fengsongda.top/Article/details/gt2fnfxybvx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gt2xqphrbxu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gt2cyvamfsb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xylfe.cn/Article/details/gt2akjhbvga.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fimpkjpz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gt2wwticyet.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2uftygvnd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sysykeji.top/Article/details/gt2eaghvyow.html

PHP:  implode(", ", $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2dislrxuy.html

JS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gt2nmaredce.html

TS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wgboaxfv.html

Java: String.join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymkqkadd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gt2lxbtohll.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gt2gqvmsvye.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gt2diqedkht.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2mgedcdgm.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gt2hyrtuaar.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2uzihcpjl.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gt2soaglgtk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenlongwang.top/Article/details/gt2dmewcmgd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gt2sugoiasu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gt2idqhalad.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vtuvxlpl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258.top/Article/details/gt2vtquudmv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnqzz.top/Article/details/gt2pzyuzpxu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhzkhklw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2yeonsyon.html

[E02] 重复字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2opnewvkv.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkgwhct.html

PHP:  str_repeat("ab", 3);
来源：http://dali.bjfxy.top/Article/details/gt2hjyluacd.html

JS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gt2gjeophis.html

TS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2emwbsoka.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2ptoatyxf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnqzz.top/Article/details/gt2ufsncrtx.html

Ruby: "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gt2yrqdzcna.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ydzc1.top/Article/details/gt2uhqengmo.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gt2fjnvkdaa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guannengcc.top/Article/details/gt2vrvmrhnj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2ibwapljf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gt2akujyewd.html

TS:   s.slice(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2beauyzws.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2vhekjqoz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2spacollz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hfpthk.cn/Article/details/gt2oqvlmmeg.html

C#:   s.Substring(1, 3)
来源：http://dali.yongpay.top/Article/details/gt2gocqysgn.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfgrkkoz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258.top/Article/details/gt2jxogelyr.html

PHP:  strpos($s, "x");
来源：http://dali.vqdsnc.cn/Article/details/gt2xprmqoxd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnqzz.top/Article/details/gt2wjqalktd.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gt2pigjijvq.html

Java: s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gt2gmnudldq.html

Go:   strings.Index(s, "x")
来源：http://dali.dianchejie.cn/Article/details/gt2ykpfirdi.html

Ruby: s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gt2oyseswkg.html

C#:   s.IndexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gt2sqdmslix.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2vgeypzfp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gt2eahtsmsg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangdashe.top/Article/details/gt2ibdhnnfr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gt2ceiqqrwa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sysykeji.top/Article/details/gt2tiiekdrw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gt2nfpjzxrr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhixingplan.top/Article/details/gt2kadusgar.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gt2xkybecdr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2jmhfvvnz.html

[E06] 替换子串
来源：http://dali.gzhubu.top/Article/details/gt2jjaxmocm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gt2kkobqoev.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yueranfly.top/Article/details/gt2zghfpcgw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2vcydvyey.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2fxdnnfvu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjomrnfg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gt2yvafdlhe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2dyqtfzlm.html

C#:   s.Replace("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2bfhbdhta.html

[E07] 按分隔符拆分
来源：http://dali.cqqwz.cn/Article/details/gt2rzmvffpl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yvedp.cn/Article/details/gt2gjizhtgq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gt2oaeszhlk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sweek.top/Article/details/gt2cyghddlg.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2yfgmyzry.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dianchejie.cn/Article/details/gt2kbsxxwig.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shuidangran.top/Article/details/gt2mpkhfqqf.html

Ruby: s.split(",");  s.split
来源：http://dali.dashuyun.cn/Article/details/gt2mprrhgzr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aizwys.cn/Article/details/gt2nwjecbix.html

[E08] 数组按分隔符合并
来源：http://dali.zdqjudy.top/Article/details/gt2vjznjmul.html

Py:   ",".join(items)
来源：http://dali.vqdsnc.cn/Article/details/gt2phufeabw.html

PHP:  implode(",", $items);
来源：http://dali.yj202588.top/Article/details/gt2baoxijrz.html

JS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gt2vsvytbbp.html

TS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2fwwxnoii.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xdteqrzm.html

Go:   strings.Join(items, ",")
来源：http://dali.yanxiufei.cn/Article/details/gt2rztdagrd.html

Ruby: items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2qvjhyipr.html

C#:   string.Join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gt2lmwjpnme.html

[E09] 去除所有空白字符
来源：http://dali.hywenlv.cn/Article/details/gt2dsunerns.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2ktejlplg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2lrqorsjm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gt2hghdkgov.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gt2fuefsajl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gt2lnwhezbk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gt2ytatewrm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guannengcc.top/Article/details/gt2zibogyld.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cashguo.top/Article/details/gt2mrosypkt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.snrcjt.cn/Article/details/gt2mmijqupv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daria6918.cn/Article/details/gt2upojxkji.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenjidiqi.icu/Article/details/gt2btigpufm.html

JS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gt2zlmiiaqz.html

TS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2uxgxovbx.html

Java: String.format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2wepucjjm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gt2tlqpgtjn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gt2ivlqwdjs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenzaomai.com/Article/details/gt2sjavzefi.html

[E11] 反转字符串
来源：http://dali.shzxlz.cn/Article/details/gt2lhcmwunf.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wjglgjih.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gt2gknxqntl.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2eszjeuiq.html

TS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2sqojalwk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258.top/Article/details/gt2egprrilh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aakbjcfo.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2ikwrrvgm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gt2nejjwvvp.html

[E12] 统计某字符出现次数
来源：http://dali.fzhhl.top/Article/details/gt2coxzncsi.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gt2ytnwpflw.html

PHP:  substr_count($s, "a");
来源：http://dali.hnxiangtu.top/Article/details/gt2usjbvreg.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gt2xecvhbga.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gt2rpiqhtqj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuanzx.com/Article/details/gt2dmkznixc.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gt2gefzrrfl.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgefflel.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwkeggbe.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gt2vzhpeylb.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gt2gtyvaymk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gt2zskeevwt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2kuphltxh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ylyfdbhs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigufen.top/Article/details/gt2nmqaeaia.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2tefwwmpn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sxryk.cn/Article/details/gt2pwatayqo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ykzumpqn.html

[E14] URL 编码与 Base64
来源：http://dali.yvedp.cn/Article/details/gt2fnnazfoo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gotoacloud.top/Article/details/gt2sarywyjw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qepczdvr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpoklrje.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gt2xkscwydt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gt2rwcqtpow.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.svipenyu.cn/Article/details/gt2npiakcqo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gt2azyuitlg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gt2qgyeatky.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gt2xpjqwenm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aizwys.cn/Article/details/gt2givgqlpx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.bjfxy.top/Article/details/gt2jlcfpxuz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cdnleiting.top/Article/details/gt2mtdjlztu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtdckdxq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gt2wdcnevsc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2euzwrbpw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xziqi.cn/Article/details/gt2hyqnqjsz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.svipenyu.cn/Article/details/gt2bseyknsa.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gt2ovsijnbl.html

Py:   f"{1234567:,}"
来源：http://dali.sysykeji.top/Article/details/gt2hdnyltaf.html

PHP:  number_format(1234567);
来源：http://dali.dianchejie.cn/Article/details/gt2jpzabste.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gt2peclxzuu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gt2ucvkkozm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gt2fqwueisv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sxryk.cn/Article/details/gt2xnlykjgx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ekwxrohs.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gt2ptoqyhra.html

[E17] 首字母大写
来源：http://dali.jianghu66.top/Article/details/gt2mnoaccbg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigfzy.top/Article/details/gt2ikoekvvl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gt2urllsjuj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gt2pouswlwl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gt2jqyfufvd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gt2uexverwc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2skijhvnj.html

Ruby: s.capitalize
来源：http://dali.yongpay.top/Article/details/gt2kfghltny.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.316326.xyz/Article/details/gt2lddokmyd.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gt2uocoifjh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gt2nxrbqmnt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gt2zuufwdnb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fujttgwk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2lxsismbj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odkqqjel.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2hdjncqjs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gt2rrjrtpoj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhoulong.xyz/Article/details/gt2iqjnmycm.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gt2jujfwrip.html

Py:   s.splitlines()
来源：http://dali.wangdashe.top/Article/details/gt2zfiqnysu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2cnsvryav.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olfthxeo.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gt2ulotnekq.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gt2qjoizlff.html

Go:   strings.Split(s, "\n")
来源：http://dali.yangfankeji.com/Article/details/gt2oikxxcyd.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gt2vadwospx.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gt2qnndpetr.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gt2owpdkpye.html

Py:   if not s:
来源：http://dali.yuxming.cn/Article/details/gt2drlzkfjs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.bjfxy.top/Article/details/gt2jrcedocn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gt2dbhzocyy.html

TS:   if (s === "") {}
来源：http://dali.svipenyu.cn/Article/details/gt2txcudbry.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gt2ivgafhcg.html

Go:   if s == "" {}
来源：http://dali.jinqigfzy.top/Article/details/gt2wlsxcldr.html

Ruby: if s.empty?
来源：http://dali.9152youxi.cn/Article/details/gt2fvatbyqe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gt2dalplexl.html

[E21] 超长截断加省略号
来源：http://dali.yvedp.cn/Article/details/gt2rxgjdckv.html


<!-- 参考信息 -->