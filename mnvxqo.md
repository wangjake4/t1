代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gt2ewrlriak.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ywvnpmyd.html

C#:   list.Sort();
来源：http://dali.haohaochexian.top/Article/details/gt2inrsjofa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.redwolf501.top/Article/details/gt2mgsqodcx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cqqwz.cn/Article/details/gt2ujeixmal.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gt2ccfytddx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gt2hkhkhhgo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gt2notfwgas.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigufen.top/Article/details/gt2eqynakjn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnqzz.top/Article/details/gt2obpbauio.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qylscgan.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gt2btnadxzo.html

[D11] 反转数组
来源：http://dali.gaohongyu789.top/Article/details/gt2hrrofagp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgfzy.top/Article/details/gt2plhmorwc.html

PHP:  array_reverse($arr);
来源：http://dali.aizwys.cn/Article/details/gt2cdkzsjwj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gt2fjidckvd.html

TS:   [...arr].reverse();
来源：http://dali.wangdashe.top/Article/details/gt2hvhbjeqz.html

Java: Collections.reverse(list);
来源：http://dali.cqqwz.cn/Article/details/gt2wacgtakb.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsnqjufm.html

Ruby: arr.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2notictjp.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2niuytdts.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gt2evhyjsis.html

Py:   arr.index(x);  x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wyyavfph.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gt2mfsnmwip.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vzrkyfnk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gt2xyojubuh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.c1oappe.top/Article/details/gt2ojnysaqi.html

Go:   slices.Index(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2vsohwsqu.html

Ruby: arr.index(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2oojafbec.html

C#:   list.IndexOf(x);
来源：http://dali.yj202588.top/Article/details/gt2pdmuyzkv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gt2byzeawbf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sufxvd.cn/Article/details/gt2dszrjihq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gt2slzgzpmc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgvfwhhl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xxuuqvoj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gt2ynobnkwt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ivvv.top/Article/details/gt2bfnvqwyo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bcrrkcpu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2uwljeeqk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gt2draxctki.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jiagoushi.top/Article/details/gt2jxabkfdn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gfgrhzno.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gt2yzmnocjz.html

TS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gt2jbeuxddu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2ctilbtkv.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gt2jcmrmneg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.redwolf501.top/Article/details/gt2secxisyr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2efsgrxvt.html

[D15] 去重
来源：http://dali.chenzaomai.com/Article/details/gt2ztruaijj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gt2rlxvpmor.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gt2mhnbbaly.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gt2qtxspaps.html

TS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gt2cqborswk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gt2bdnldaax.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gt2xblnjtgh.html

Ruby: arr.uniq
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdvtucef.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gt2teaywpiw.html

[D16] 求和与平均值
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdcfjscw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2lnijibbg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2exsracbi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gt2nfpnwnda.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2dxlnoxim.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jlsjyb.cn/Article/details/gt2zdzcohjz.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gt2ighucstm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gt2fkxoiykr.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gt2fombnymc.html

[D17] 最大值与最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2werwxxka.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gt2vzzeiglc.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gt2ewtvgsug.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2rgolnryg.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gt2mvsfiixg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuanzx.com/Article/details/gt2hphsvkcx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2hrbafzpu.html

Ruby: arr.max;  arr.min
来源：http://dali.tianlin.xyz/Article/details/gt2tcwqgmzn.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigufen.top/Article/details/gt2rnuobtvc.html

[D18] 扁平化嵌套数组
来源：http://dali.snrcjt.cn/Article/details/gt2uttxlefq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhixingplan.top/Article/details/gt2kxgpclch.html

PHP:  array_merge(...$nested);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdvajcpx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2otpotoyr.html

TS:   nested.flat();
来源：http://dali.andypj.xyz/Article/details/gt2bxpkznep.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2uqavxgjq.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2gyfzsbej.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gt2wpwmrjdu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gt2wcuutjza.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gt2wshdzray.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gt2owkfdfei.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258.top/Article/details/gt2bnziaunh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gt2ujfoebmr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrcifmrf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yanxiufei.cn/Article/details/gt2pjabawxu.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gt2ifttnpdy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gt2viflttgl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gt2rglrsmor.html

[D20] 统计每个元素出现次数
来源：http://dali.cqqwz.cn/Article/details/gt2lksczaeo.html

Py:   Counter(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2jjopcguv.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2tsjanogr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gt2irtudxpx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2ewjkybdy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gt2gxbhkunp.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gt2horxsogr.html

Ruby: arr.tally
来源：http://dali.gotoacloud.top/Article/details/gt2vpxhjald.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gt2biqdcbgf.html

[D21] 判断是否包含某元素
来源：http://dali.daria6918.cn/Article/details/gt2cryrhbvh.html

Py:   x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2stlrprnl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvqytmlf.html

JS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2hltblegg.html

TS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gt2bokenuvh.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2azfzixvb.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2wyxmzxzb.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gt2skemavfw.html

C#:   list.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2qofpwfyf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.smart0.xyz/Article/details/gt2ljyklslt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gt2fexdoazw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gt2vkdtfiwk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2zdfqerkp.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gt2dzjpccyu.html

Java: new ArrayList<>(list);
来源：http://dali.zhixingplan.top/Article/details/gt2ewqkijqa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gt2heyjrqhy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj202588.top/Article/details/gt2rgnlmxqe.html

C#:   new List<int>(list);
来源：http://dali.cheryme.top/Article/details/gt2bmzmyacz.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gt2xtqfmcyr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2dwecguol.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2gpwlpclw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2dldbierx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2xdnfcniu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xwrjmvon.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gt2mjjrvcvv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hammf.cn/Article/details/gt2imibbdvq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gt2kzoyksps.html

[D24] 字典 / Map 基本操作
来源：http://dali.birdmap.top/Article/details/gt2qtbjkfvp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zdqjudy.top/Article/details/gt2zeipairb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gt2utdghbys.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2hcgmiqui.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2gwicaide.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ryfgigyn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sysykeji.top/Article/details/gt2lqionray.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gt2oiffshqq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sweek.top/Article/details/gt2wfkrztcm.html

[D25] Set 集合去重与交并差
来源：http://dali.aibaodan.cn/Article/details/gt2mzhmxqyt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.svipenyu.cn/Article/details/gt2inhgghlp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gt2hpfrptqw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cdnleiting.top/Article/details/gt2kdrmyaak.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258888.top/Article/details/gt2ifdjddid.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fzhhl.top/Article/details/gt2mxuefbqs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ppjwa.cn/Article/details/gt2pdbkfhjz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.snrcjt.cn/Article/details/gt2imwmlyns.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xylfe.cn/Article/details/gt2gyexgfxa.html

[D26] 数组转字符串
来源：http://dali.meibo888.top/Article/details/gt2asobpelp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2qpmstgpn.html

PHP:  implode(", ", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbbffcev.html

JS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2tkffqxyw.html

TS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2wizucmmy.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gt2zlbzvhmo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cashguo.top/Article/details/gt2zhcnfmxg.html

Ruby: arr.join(", ")
来源：http://dali.sweek.top/Article/details/gt2brssepuf.html

C#:   string.Join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gt2klaggpcd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jsongqpp.html

E. 字符串处理
来源：http://dali.jlsjyb.cn/Article/details/gt2efdjgfhb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ajfftgoj.html

[E01] 拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2bpyjyhwh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangdashe.top/Article/details/gt2oupydaud.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sufxvd.cn/Article/details/gt2tpshulln.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gt2szbkdqxh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gt2dbsixytx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.c1oappe.top/Article/details/gt2bzhuuomm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gt2kmtpnmzb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.mhx1999.top/Article/details/gt2vxupczut.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2udifhgdi.html

[E02] 重复字符串
来源：http://dali.hysaishi.cn/Article/details/gt2xandyjvt.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gt2fagplgbv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gt2zkifpxqm.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gt2msztnalm.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gt2cvrountz.html

Java: "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2lmmkrivl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2fgnogdsf.html

Ruby: "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gt2nhzaqoho.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yanxiufei.cn/Article/details/gt2lyfhkjns.html

[E03] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gt2kegdodud.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdqjlerx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2gymlwaod.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2kbyfsqzu.html

TS:   s.slice(1, 4)
来源：http://dali.daria6918.cn/Article/details/gt2ihxzshlc.html

Java: s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gt2dzpqabxc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.iojbl.cn/Article/details/gt2fytkvaoq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuxming.cn/Article/details/gt2yypnxeqi.html

C#:   s.Substring(1, 3)
来源：http://dali.daxiang520.top/Article/details/gt2erbgighn.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gt2cgfvqhfc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gt2bddnggwb.html

PHP:  strpos($s, "x");
来源：http://dali.xinyue.icu/Article/details/gt2bvyoilxj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dianchejie.cn/Article/details/gt2fdhxwgus.html

TS:   s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gt2kzohdcww.html

Java: s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2kaltqwbd.html

Go:   strings.Index(s, "x")
来源：http://dali.cashguo.top/Article/details/gt2hbshmuks.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gt2gybmucdg.html

C#:   s.IndexOf("x")
来源：http://dali.c1oappe.top/Article/details/gt2vlxstixq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zrlpuoii.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gt2avxeuwsu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxuanxn.top/Article/details/gt2tlueikmb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2djfdlepe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hfpthk.cn/Article/details/gt2aeolunvq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gt2ihmswbvm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.9152youxi.cn/Article/details/gt2assmlnuq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2buqndnzz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cheryme.top/Article/details/gt2gqcshoyl.html

[E06] 替换子串
来源：http://dali.gzhubu.top/Article/details/gt2evoxjwkc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdkbleyf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxxqkljc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2ugtwcnad.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2flkwhoct.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2kiriuohx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gt2ijqtlmuo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2ciohmlma.html

C#:   s.Replace("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2opxqczxn.html

[E07] 按分隔符拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rklfaonh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhiwuduotai.top/Article/details/gt2nataraag.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2lpxjbcpv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sweek.top/Article/details/gt2kxtttjzo.html

TS:   s.split(",")
来源：http://dali.snrcjt.cn/Article/details/gt2rdvznxdh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guowangkeji.top/Article/details/gt2dvapddgj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tian-w.cn/Article/details/gt2ykvujyhp.html

Ruby: s.split(",");  s.split
来源：http://dali.mhx1999.top/Article/details/gt2sineffms.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hywenlv.cn/Article/details/gt2qkglpwaw.html

[E08] 数组按分隔符合并
来源：http://dali.zhiwuduotai.top/Article/details/gt2hssmxwli.html

Py:   ",".join(items)
来源：http://dali.xuanzx.com/Article/details/gt2apodehxc.html

PHP:  implode(",", $items);
来源：http://dali.xziqi.cn/Article/details/gt2zalrxroh.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2itspjwqq.html

TS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gt2zdirsmtl.html

Java: String.join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gt2jybzftab.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gt2mjbmytdo.html

Ruby: items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2wmnidrnf.html

C#:   string.Join(",", items)
来源：http://dali.smart0.xyz/Article/details/gt2qipegers.html

[E09] 去除所有空白字符
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukaksvbq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqrrebmx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2fujsndij.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gt2lzpkhxda.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gt2uekfmikv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gt2pnbxnamg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigufen.top/Article/details/gt2oevczovl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cheryme.top/Article/details/gt2elgvtcgl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gt2vpqdocuv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gt2eipmlygd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cucudq.cn/Article/details/gt2vzmsvfst.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yangfankeji.com/Article/details/gt2xubdyxsa.html

JS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gt2qfmaczza.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2kcbweoik.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2msvekztg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2ddzyvmjp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpywcsuv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypgofqsk.html

[E11] 反转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2dbivoiiv.html

Py:   s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gt2mtqoansj.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gt2tccgskxr.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2znngkjio.html

TS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gt2vlouxtpm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gt2ozgcvqaf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gt2awfexmxq.html

Ruby: s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmnvidyp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gt2dpjsppzb.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gt2itcyebyj.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2saslfzeg.html

PHP:  substr_count($s, "a");
来源：http://dali.xuetiantiany.cn/Article/details/gt2lqesczcj.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gt2wthiarqs.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gt2odbkrpxs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.kuanghao11.cn/Article/details/gt2fppjzluu.html

Go:   strings.Count(s, "a")
来源：http://dali.yongpay.top/Article/details/gt2cmrqjmqd.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gt2tnhmazzm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gt2ugcxmwig.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2obdqrxoq.html

Py:   for ch in s: print(ch)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hkdcviqo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daxiang520.top/Article/details/gt2lvquagwt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2tloecyba.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2eoqgmocr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2yuhlwhoo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hfpthk.cn/Article/details/gt2dpxipzak.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.kuanghao11.cn/Article/details/gt2fjuzlitg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alodxuqk.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gt2yuwufdny.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gt2qrpapvsh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gt2ckjzzurd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daria6918.cn/Article/details/gt2fslzkoaz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigufen.top/Article/details/gt2csmtwjjo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gt2zseduiqq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqkzhlja.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vnabtcpj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gt2efquoocs.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gt2eqrvdotm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gt2fyfazeue.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gt2fmqsawwo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uilijiqf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gt2ezfobleu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.vqdsnc.cn/Article/details/gt2krrzmivy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shuidangran.top/Article/details/gt2knjhyces.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gt2duljqwlx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gt2mtshxcoi.html

[E16] 数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbdbugfz.html

Py:   f"{1234567:,}"
来源：http://dali.cdnleiting.top/Article/details/gt2fwpdyord.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gt2tifveufu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gt2worvbywu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gt2eqteukwh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gt2qmywddhq.html


<!-- 参考信息 -->