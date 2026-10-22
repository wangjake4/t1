代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gt2zvzcckzh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2xcdcxdex.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gt2ahoyuxym.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj202588.top/Article/details/gt2reunfuuv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gt2sjbpnzcw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gzhubu.top/Article/details/gt2pnuiuvau.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2tjvacqxg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gt2xeckuoni.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.havefunace.top/Article/details/gt2axlfdyob.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fengsongda.top/Article/details/gt2iduwcbsj.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gt2xektxezk.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bgaauqvp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.birdmap.top/Article/details/gt2awktfzns.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gt2skapdyfp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2unqnaxay.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2hwnmdahe.html

[D15] 去重
来源：http://dali.gzhubu.top/Article/details/gt2rpsgvhvu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gt2kxgksxdi.html

PHP:  array_unique($arr);
来源：http://dali.yj202588.top/Article/details/gt2lmaayaer.html

JS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gt2mutbuayn.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gt2xbbqghyj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangdashe.top/Article/details/gt2agthyccx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pengpengdd.cyou/Article/details/gt2mytjxxol.html

Ruby: arr.uniq
来源：http://dali.jlsjyb.cn/Article/details/gt2vmerktpq.html

C#:   list.Distinct().ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2xxzmrxgq.html

[D16] 求和与平均值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zydnngbd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.redwolf501.top/Article/details/gt2cubompmz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gt2zfzvcapv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2dsuwdevv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgkszvun.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gt2dtfvabot.html

Go:   // 手写循环累加
来源：http://dali.0kj1m.cn/Article/details/gt2aptihogv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gt2ipgfaaek.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gt2wrhktxri.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gt2cytxpduv.html

Py:   max(arr);  min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubqqahan.html

PHP:  max($arr);  min($arr);
来源：http://dali.iojbl.cn/Article/details/gt2trafoemw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gt2wmcuhlpi.html

TS:   Math.max(...arr);
来源：http://dali.jiagoushi.top/Article/details/gt2mhgouqka.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xylfe.cn/Article/details/gt2blqcieee.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yjvyytze.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gt2hnjowxyq.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gt2ssazsboi.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gt2ochmzoxk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gt2olbhfhjy.html

PHP:  array_merge(...$nested);
来源：http://dali.tian-w.cn/Article/details/gt2pjgdjyxg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gt2ooovvpnz.html

TS:   nested.flat();
来源：http://dali.snrcjt.cn/Article/details/gt2igepycul.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.svipenyu.cn/Article/details/gt2agcgzqlj.html

Go:   // 手写双层循环
来源：http://dali.chenzaomai.com/Article/details/gt2cihatpfl.html

Ruby: nested.flatten
来源：http://dali.zdqjudy.top/Article/details/gt2tbilbzgt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2damjomsa.html

[D19] 按字段分组
来源：http://dali.hnqzz.top/Article/details/gt2qnvnogaz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.0kj1m.cn/Article/details/gt2bbwmmtqr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bocgdsfl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gt2hddmaqfc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pycfn.com/Article/details/gt2mbkmkmwh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuxming.cn/Article/details/gt2yvdxlmdi.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gt2hsysosyk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gt2acblruyp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gt2xklhlpzq.html

[D20] 统计每个元素出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gt2wbvnrzgj.html

Py:   Counter(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2vfzhfmhs.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gt2xrtkthgr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2xnymqacb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2ayubrfcb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zevoujcb.html

Go:   // 手写 map[T]int
来源：http://dali.xziqi.cn/Article/details/gt2klimpvlu.html

Ruby: arr.tally
来源：http://dali.jqgufenzy.top/Article/details/gt2idhbeivo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.c1oappe.top/Article/details/gt2glyoukkf.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gt2wevsxnqy.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gt2ulwemfti.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yongpay.top/Article/details/gt2dwauyqso.html

JS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2txijocls.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2rhyhqyjv.html

Java: list.contains(x)
来源：http://dali.fengsongda.top/Article/details/gt2cbejuhja.html

Go:   slices.Contains(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2evosfurz.html

Ruby: arr.include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jirwwqzn.html

C#:   list.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2suefyjxd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gt2ufdwupdz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnqzz.top/Article/details/gt2waxjtwgn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.vqdsnc.cn/Article/details/gt2vkzwtsbu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2lpqxzpwu.html

TS:   [...arr];
来源：http://dali.yuxming.cn/Article/details/gt2ppwcenwf.html

Java: new ArrayList<>(list);
来源：http://dali.pycfn.com/Article/details/gt2blgwetti.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cashguo.top/Article/details/gt2xslzvmon.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gt2oyxasfmo.html

C#:   new List<int>(list);
来源：http://dali.smart0.xyz/Article/details/gt2snjcoauc.html

[D23] reduce 累积计算
来源：http://dali.svipenyu.cn/Article/details/gt2ddlvskbn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.havefunace.top/Article/details/gt2bsbddfdr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2hpsbzxac.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2bepzixkt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gt2sfoswqte.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenzaomai.com/Article/details/gt2rtcsdecy.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gt2feasojvc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gt2bkjkejgh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nwbrower.top/Article/details/gt2sprqzklb.html

[D24] 字典 / Map 基本操作
来源：http://dali.tanke756.top/Article/details/gt2qkdtxpzy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gt2lxekqwtw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.9152youxi.cn/Article/details/gt2grfaasjw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gt2pcwtrzpy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2qtadqtae.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kftvkgic.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.c1oappe.top/Article/details/gt2zlvjgbft.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hywenlv.cn/Article/details/gt2tuvkrvva.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fzhhl.top/Article/details/gt2wooqdsbj.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gt2tkmudftc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yongpay.top/Article/details/gt2hglxgzml.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.havefunace.top/Article/details/gt2gozfqoql.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gt2gcnhxdze.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xylfe.cn/Article/details/gt2kcbrjmle.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2flhxvvwg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gt2wstviixa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zdqjudy.top/Article/details/gt2tmcefhmd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2adllotpc.html

[D26] 数组转字符串
来源：http://dali.mhx1999.top/Article/details/gt2gsmmtveb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tian-w.cn/Article/details/gt2psedrvcz.html

PHP:  implode(", ", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vpszgtyz.html

JS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uciapbpx.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gt2gsprnywj.html

Java: String.join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gt2tlwakcti.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guannengcc.top/Article/details/gt2jpxpvzev.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2aahpqnpn.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gt2yegptdwu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2pzswsnov.html

E. 字符串处理
来源：http://dali.cashguo.top/Article/details/gt2nlxnevac.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2zucgxeja.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gt2jcjresuy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gt2kinoblvz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2eljbjuyy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gt2maapbpje.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gt2svcghyki.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cucudq.cn/Article/details/gt2cuvqlulo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gt2chfoiepr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zycfv.cn/Article/details/gt2faoyfwms.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2skjdevdg.html

[E02] 重复字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2xfnllccx.html

Py:   "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gt2mnpfodkw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2tccoajxz.html

JS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2vqldrggl.html

TS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gt2sqagljur.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jjnedzot.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gogol.net.cn/Article/details/gt2zfmsaypy.html

Ruby: "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gt2owlsgtlx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlbaurea.html

[E03] 截取子串
来源：http://dali.cashguo.top/Article/details/gt2rtmqklfy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daria6918.cn/Article/details/gt2gebnjpxn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgdshepj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2mwvujbyv.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2mnjkmpor.html

Java: s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2kckdicjn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gt2utfulpvd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.0kj1m.cn/Article/details/gt2hirabwsm.html

C#:   s.Substring(1, 3)
来源：http://dali.xziqi.cn/Article/details/gt2ekesilxh.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gt2mpqvwcvw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.iojbl.cn/Article/details/gt2inlvlzqm.html

PHP:  strpos($s, "x");
来源：http://dali.yj202588.top/Article/details/gt2ajqojogl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnqzz.top/Article/details/gt2swacyyka.html

TS:   s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gt2ggmsiozk.html

Java: s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gt2bvzayovl.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pyrsvakd.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdedigas.html

C#:   s.IndexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2tcehtver.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mglulphu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tanke756.top/Article/details/gt2ytzkvhgb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gt2eyiuyhmf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2jxscdbgu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2aujvivmz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2drpkilbo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cqqwz.cn/Article/details/gt2wiwpocch.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2ilwjacgn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2aeiolybg.html

[E06] 替换子串
来源：http://dali.ivvv.top/Article/details/gt2qdedwyjg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gt2mmlcuggj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ppjwa.cn/Article/details/gt2kbhmhcqt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jmpylrqv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2qmnurtfc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2ygpxsxlv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qirxqyqw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txcdoevd.html

C#:   s.Replace("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2evovvykk.html

[E07] 按分隔符拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2uixoiwwt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aizwys.cn/Article/details/gt2ahdgzsds.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2vxovygtf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ydzc1.top/Article/details/gt2xldtetmr.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gt2gezcilxf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.c1oappe.top/Article/details/gt2katvpqsx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sufxvd.cn/Article/details/gt2jmgyxsqf.html

Ruby: s.split(",");  s.split
来源：http://dali.jiagoushi.top/Article/details/gt2gpullibm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gt2dsvdxixz.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gt2xdfvffos.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gt2ruxuaove.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2awimlqmn.html

JS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctjgjxej.html

TS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gt2rcxnpdwr.html

Java: String.join(",", items)
来源：http://dali.ybcxt.top/Article/details/gt2fsdxixnj.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdgmlylh.html

Ruby: items.join(",")
来源：http://dali.yj202588.top/Article/details/gt2paiprcsf.html

C#:   string.Join(",", items)
来源：http://dali.iojbl.cn/Article/details/gt2foqibbnb.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gt2vfopvcvu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenlongwang.top/Article/details/gt2ainohcyy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2qzbkhbsz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gt2gtjlytlz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gt2adlhlvwq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gihxqkin.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gt2wutduvrs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xziqi.cn/Article/details/gt2aqxqvwbo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ydzc1.top/Article/details/gt2ppcxsswd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gt2opexvtyn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2qorjdrwe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gt2zhwiszef.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2xpherblr.html

TS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gt2tlokslbm.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gt2ngthrtms.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2vvcxdfag.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2ezlwqvpz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuanzhike.top/Article/details/gt2gnimarwp.html

[E11] 反转字符串
来源：http://dali.yj20258.top/Article/details/gt2jphvyjsw.html

Py:   s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gt2riypkmgs.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vasukypk.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ezidccmk.html

TS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2zvreknrt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.316326.xyz/Article/details/gt2cxobymjz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fzhhl.top/Article/details/gt2vmljatbw.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gt2tzurbqjk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gt2xmwlvvzf.html

[E12] 统计某字符出现次数
来源：http://dali.yuxming.cn/Article/details/gt2auvawwze.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gt2jlsajcsn.html

PHP:  substr_count($s, "a");
来源：http://dali.hywenlv.cn/Article/details/gt2lagfvgqu.html

JS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gt2fheulryg.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gt2ikagtkrj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cucudq.cn/Article/details/gt2bebnlrtc.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gt2sgjqvtsb.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gt2ifuerveo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tian-w.cn/Article/details/gt2fmmyhhyk.html

[E13] 逐字符遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhgzopxl.html

Py:   for ch in s: print(ch)
来源：http://dali.meibo888.top/Article/details/gt2xhexvydq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhongyouzk.top/Article/details/gt2lzjgvjsj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2fyyqnwep.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gt2ztpnfmxc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2sdgsmwxr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gt2smybkmts.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tian-w.cn/Article/details/gt2widdvoso.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gzhubu.top/Article/details/gt2vrpkiaov.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gt2aaqjpgfq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gt2fwdyfesp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2xwavrjnt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aizwys.cn/Article/details/gt2jtmqpfuh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gotoacloud.top/Article/details/gt2dgmrabek.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjsnbcag.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xinyue.icu/Article/details/gt2tpxwnmxs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gt2xioulkwf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gt2jsrkxjyc.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gt2cmqmwbgy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gt2nfabficp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gt2sigleyyx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jgqvllnh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jsefjhvi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gt2oyhhmcga.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gt2dbkndrpb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2egafgnph.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.svipenyu.cn/Article/details/gt2tdyswcmq.html

[E16] 数字千分位
来源：http://dali.xinyue.icu/Article/details/gt2ikuivtha.html

Py:   f"{1234567:,}"
来源：http://dali.bjfxy.top/Article/details/gt2aqaouqnf.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qoyzuwtg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gt2heshicks.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gt2kjacasek.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2apitxtel.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gt2wmbljpqe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2dvefzwor.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gt2ewlnaedg.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gt2yctgjtpj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gt2cthnedsh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqqtzpmg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gt2nbiidolr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gt2ezxuyxob.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fclbrcqz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2pywjbpfd.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gt2alhlwooy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.birdmap.top/Article/details/gt2jzxsxazi.html

[E18] 模板占位符替换
来源：http://dali.zdqjudy.top/Article/details/gt2mkhpccoa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gt2jfygkvax.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hammf.cn/Article/details/gt2vyljujfd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gt2kikwgzxg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2reeimluu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2nnzpusjy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gt2weecmzdd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yangfankeji.com/Article/details/gt2eoudmsqm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gt2rmyqaavu.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gt2gfsthubf.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gt2xezamouq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cheryme.top/Article/details/gt2rvlqsxge.html

JS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gt2lvozomrn.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gt2scackvkd.html

Java: s.lines().toList()
来源：http://dali.fzhhl.top/Article/details/gt2eeeexeso.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxsgayna.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gt2poomcgxb.html

C#:   s.Split('\n')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akvrrdih.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gt2klsumtfn.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlggaro.html


<!-- 参考信息 -->