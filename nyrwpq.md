代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258888.top/Article/details/gt2wmkcqbga.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zycfv.cn/Article/details/gt2yrxecyit.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gt2gyjkutwl.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gt2pfkrlavc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daxiang520.top/Article/details/gt2jeurnrrb.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gt2assdsdch.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2ersnbxpz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2xvpraeku.html

[D15] 去重
来源：http://dali.zhoulong.xyz/Article/details/gt2ftwuwaqd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gt2eqkgohac.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2xnfpzyud.html

JS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gt2xlrpxwtv.html

TS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2gyidwrox.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guannengcc.top/Article/details/gt2umvnhgyi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2asgdjujh.html

Ruby: arr.uniq
来源：http://dali.cdnleiting.top/Article/details/gt2mmxcwpmz.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2irlleehl.html

[D16] 求和与平均值
来源：http://dali.jqgufenzy.top/Article/details/gt2bnnogmst.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2xyqmfwrb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2mwrkewhz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gt2hpgxwsjf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2kehivjee.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gt2baxjyzdu.html

Go:   // 手写循环累加
来源：http://dali.xuetiantiany.cn/Article/details/gt2auetokdo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cashguo.top/Article/details/gt2rkzpotvk.html

C#:   list.Sum();  list.Average()
来源：http://dali.hywenlv.cn/Article/details/gt2owfjbmhq.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gt2rpuvokfd.html

Py:   max(arr);  min(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2hzomljit.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2aoreffun.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj202588.top/Article/details/gt2vzokikft.html

TS:   Math.max(...arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwjsuhys.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dyjucqxg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2icambgek.html

Ruby: arr.max;  arr.min
来源：http://dali.tian-w.cn/Article/details/gt2kswnahyy.html

C#:   list.Max();  list.Min()
来源：http://dali.kuanghao11.cn/Article/details/gt2rybtdhly.html

[D18] 扁平化嵌套数组
来源：http://dali.sysykeji.top/Article/details/gt2xolgdoeo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gt2hadeufgd.html

PHP:  array_merge(...$nested);
来源：http://dali.daxiang520.top/Article/details/gt2tfmmuwvv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dstqokcv.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gt2hnwdsadb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuanzx.com/Article/details/gt2fnywoboj.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gt2lsnkvhnd.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrpcfbhz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2hnoqvmxl.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gt2trmqhroh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.0kj1m.cn/Article/details/gt2tvbsiqbg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqpwvqmk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sufxvd.cn/Article/details/gt2agmcixms.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gt2iamxbfbn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gt2pszaxbix.html

Go:   // 手写 map[string][]T
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxqiutpf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgufenzy.top/Article/details/gt2edmxaerf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hfpthk.cn/Article/details/gt2whldoytr.html

[D20] 统计每个元素出现次数
来源：http://dali.hnqzz.top/Article/details/gt2snvcatnd.html

Py:   Counter(arr)
来源：http://dali.redwolf501.top/Article/details/gt2eltxzxgi.html

PHP:  array_count_values($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2stvvtoxu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gt2fjjghswy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gt2baanfluw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gzhubu.top/Article/details/gt2worecior.html

Go:   // 手写 map[T]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swrzylqm.html

Ruby: arr.tally
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdwacfae.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gt2bvwahocp.html

[D21] 判断是否包含某元素
来源：http://dali.iojbl.cn/Article/details/gt2loupcszj.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gt2sehdaqnw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gt2jjxitqiw.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2tohwymyc.html

TS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gt2vctcinox.html

Java: list.contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mltxzhkj.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2kfbdadgw.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gt2ngkwetaz.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2tvffnhah.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gt2omiknirk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.smart0.xyz/Article/details/gt2ivuxgfsv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gt2vddjysps.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2bigqhzph.html

TS:   [...arr];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nklufjwa.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gt2obzzvoib.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gt2vdxnknoc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gt2qwuvtrhi.html

C#:   new List<int>(list);
来源：http://dali.9152youxi.cn/Article/details/gt2gwsloyxs.html

[D23] reduce 累积计算
来源：http://dali.guannengcc.top/Article/details/gt2xwpazeoc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gt2djbrxbry.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gt2iforvuxf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gt2uecgphcg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gt2ncpyggzy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fplxspka.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gt2oieyahar.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zdqjudy.top/Article/details/gt2nmkpfoah.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hammf.cn/Article/details/gt2ljnubvjk.html

[D24] 字典 / Map 基本操作
来源：http://dali.dashuyun.cn/Article/details/gt2gjewounh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gt2ijmuvwmi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2eheqpdsb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2tccdkuso.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2nbzehdej.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hysaishi.cn/Article/details/gt2wrytjbkg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yvedp.cn/Article/details/gt2ktvyyxpk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2cpvlbkqt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gt2ogmqouvj.html

[D25] Set 集合去重与交并差
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfvezwty.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gt2rvzhohqw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hywenlv.cn/Article/details/gt2kygzimwn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2exhztoyn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ppjwa.cn/Article/details/gt2gehytcmz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fengsongda.top/Article/details/gt2ptvrhgjf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gt2nmzaguki.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2qistwksp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pycfn.com/Article/details/gt2koiznlzi.html

[D26] 数组转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2xktaidqq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gt2faocxwvv.html

PHP:  implode(", ", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbtchtjd.html

JS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gt2incwfaxk.html

TS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gt2pvxgilvi.html

Java: String.join(", ", list)
来源：http://dali.yj20258.top/Article/details/gt2mrthkehi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2nxnognhu.html

Ruby: arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gt2lmpcpxla.html

C#:   string.Join(", ", list)
来源：http://dali.sweek.top/Article/details/gt2autpgadd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2dsitznde.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gt2wdpkfpre.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2zwgewgig.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2pjzfinbj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daria6918.cn/Article/details/gt2olnwhwss.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tanke756.top/Article/details/gt2ibqbuckd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gt2yzjeftxo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcshrgv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aibaodan.cn/Article/details/gt2tjlfijdp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2btbdqvkn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gt2ehdvsovj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2ncycknic.html

[E02] 重复字符串
来源：http://dali.dianchejie.cn/Article/details/gt2sxtudqfv.html

Py:   "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gt2yfynrnzc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gotoacloud.top/Article/details/gt2qvlxtlnq.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2flivjtid.html

TS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2huyyosnu.html

Java: "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gt2dqsadmud.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.mhx1999.top/Article/details/gt2nldgasuq.html

Ruby: "ab" * 3
来源：http://dali.316326.xyz/Article/details/gt2psvhzylr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gt2vvikwcmo.html

[E03] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gt2ypprpctb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guannengcc.top/Article/details/gt2gsnbllrb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gt2qtsiwpqi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gt2tqmmsivw.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2wlxqprxo.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxcmrrab.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gt2kmnwyvud.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xinyue.icu/Article/details/gt2svinygxy.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigufen.top/Article/details/gt2kumbswkq.html

[E04] 查找子串位置
来源：http://dali.chenjidiqi.icu/Article/details/gt2gpiixqxi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gt2nsgrntpn.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gt2siorcxgk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xziqi.cn/Article/details/gt2xtrmdzle.html

TS:   s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2lzeavuxe.html

Java: s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gt2ffxzbiib.html

Go:   strings.Index(s, "x")
来源：http://dali.zycfv.cn/Article/details/gt2aehdzbpv.html

Ruby: s.index("x")
来源：http://dali.sysykeji.top/Article/details/gt2fxkflwzo.html

C#:   s.IndexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2habwivun.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnqzz.top/Article/details/gt2ongkoiie.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gt2jiimhdlg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daxiang520.top/Article/details/gt2vpfkrqgd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gt2tdzvrvjv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangdashe.top/Article/details/gt2ztghxyde.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gt2gwtsjvfp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sxryk.cn/Article/details/gt2cqejnkbc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gt2rajxiihk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2omfgtctd.html

[E06] 替换子串
来源：http://dali.xuetiantiany.cn/Article/details/gt2pninpouy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2jiyohgdp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2wlznvxtz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2qohrwtbz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2csjbzkjl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2eukxellh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gt2bymddeqf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2zkwadjrs.html

C#:   s.Replace("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2qzwgabfy.html

[E07] 按分隔符拆分
来源：http://dali.gogol.net.cn/Article/details/gt2xgcybnkn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gt2uepklcjm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zpdjwlex.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yvedp.cn/Article/details/gt2louiqbzi.html

TS:   s.split(",")
来源：http://dali.kuanghao11.cn/Article/details/gt2sipyvxpa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ybcxt.top/Article/details/gt2ysuxookn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yueranfly.top/Article/details/gt2davjlkbu.html

Ruby: s.split(",");  s.split
来源：http://dali.zhongyouzk.top/Article/details/gt2ixalpvrt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cqqwz.cn/Article/details/gt2bqaxqetw.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258.top/Article/details/gt2ezyktxey.html

Py:   ",".join(items)
来源：http://dali.haohaochexian.top/Article/details/gt2fhclhroh.html

PHP:  implode(",", $items);
来源：http://dali.fzhhl.top/Article/details/gt2hhbyajts.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2wrcangig.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2wixmhgbt.html

Java: String.join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gt2kqmqzjlm.html

Go:   strings.Join(items, ",")
来源：http://dali.meibo888.top/Article/details/gt2oixwllkq.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdxyltni.html

C#:   string.Join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aojselbb.html

[E09] 去除所有空白字符
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtcuthkv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.birdmap.top/Article/details/gt2zenwhpda.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2sjlktowg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gt2evjmlfni.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gt2kipsswvs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgrgsnnf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmttoocf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sweek.top/Article/details/gt2pyqleaju.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqengiud.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxlqbbay.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2kegtwebq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ehwqpu.com/Article/details/gt2uzhzvvvo.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gt2rwyipdgq.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2pabovzwb.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2rsebnqlz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gt2pkhgyczp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmofsfae.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gt2dtzxdxmz.html

[E11] 反转字符串
来源：http://dali.cheryme.top/Article/details/gt2blzgtwcd.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gt2pthgwiut.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbbruicl.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kogdvicz.html

TS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2jvmdwprg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gt2glrgbfgv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gt2kwhamtkx.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gt2oflzejpe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gt2vazwmiqc.html

[E12] 统计某字符出现次数
来源：http://dali.hfpthk.cn/Article/details/gt2jdjcuiza.html

Py:   s.count("a")
来源：http://dali.yongpay.top/Article/details/gt2fuipvjem.html

PHP:  substr_count($s, "a");
来源：http://dali.jiagoushi.top/Article/details/gt2xbfrlcpg.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yheizdcy.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gt2vbibegja.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gt2uivlqbep.html

Go:   strings.Count(s, "a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhxdgffg.html

Ruby: s.count("a")
来源：http://dali.iojbl.cn/Article/details/gt2qqlezgkh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gt2xccllpuo.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2piuybvmu.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gt2xejksfue.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.smart0.xyz/Article/details/gt2kdqakpkk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gt2lwetizbm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2ihcpviqa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2treanxoe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilbwsgww.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gt2evpauxsr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2dgomeklc.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gt2sooxekre.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gt2bjrhrecx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.svipenyu.cn/Article/details/gt2rhzlwscz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yongpay.top/Article/details/gt2jevoszfm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sysykeji.top/Article/details/gt2avkdgzaq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yangfankeji.com/Article/details/gt2pwecbxhm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpcuuqly.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gt2psmpdrah.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gt2prvuybvm.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangshuangyany.cn/Article/details/gt2tnvntkkg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nwbrower.top/Article/details/gt2sqdziofv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gt2qcojnflx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.iojbl.cn/Article/details/gt2rqlolwrk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sweek.top/Article/details/gt2xrmgzjsn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmlqipq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hysaishi.cn/Article/details/gt2aictkyby.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.c1oappe.top/Article/details/gt2qfgexpso.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2szpdogbo.html

[E16] 数字千分位
来源：http://dali.sysykeji.top/Article/details/gt2lmtwmtxz.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gt2xopptzzj.html

PHP:  number_format(1234567);
来源：http://dali.xylfe.cn/Article/details/gt2sivblylz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gt2ximeqxtq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gt2xtpkzahs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vfxghzhp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgfzy.top/Article/details/gt2vwcqxzza.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2uovoiqmo.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gt2uqgtjbob.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gt2yvtgbzui.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gt2yblqisdl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujapdgap.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gt2ydbnrdkv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gt2gknqsskn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sxryk.cn/Article/details/gt2dahkfvij.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hysaishi.cn/Article/details/gt2myxlwuif.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gt2qjvsnlla.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnxiangtu.top/Article/details/gt2npmojoic.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gt2lrjlnzkj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gt2tmqjbrfl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.quarkkingdee.top/Article/details/gt2elparvbh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2igsyxbfn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2lmamqfzx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2bgexefuo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2xuncddzv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuxming.cn/Article/details/gt2ehmjzmpp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.svipenyu.cn/Article/details/gt2fhjcybgg.html

[E19] 多行文本按行拆分
来源：http://dali.shzxlz.cn/Article/details/gt2zxkzodfk.html

Py:   s.splitlines()
来源：http://dali.cdnleiting.top/Article/details/gt2dzkobwwj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bylnmvkl.html

JS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gt2xgsrztfj.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gt2mvvtxzmv.html

Java: s.lines().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2buioufut.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jzbaswwl.html

Ruby: s.lines
来源：http://dali.hammf.cn/Article/details/gt2oqlwhptq.html

C#:   s.Split('\n')
来源：http://dali.tanke756.top/Article/details/gt2ildnialy.html

[E20] 判断字符串是否为空
来源：http://dali.wangdashe.top/Article/details/gt2uraassoe.html

Py:   if not s:
来源：http://dali.aizwys.cn/Article/details/gt2uratywyc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ivvv.top/Article/details/gt2iggpvsra.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aizwys.cn/Article/details/gt2szwcblqv.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gt2siqyeron.html

Java: if (s.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gt2tkmcdftb.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gt2maqzcdmv.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gt2rriutvrj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2dywluffr.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gt2lqcuckhw.html


<!-- 参考信息 -->