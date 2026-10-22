代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.redwolf501.top/Article/details/gt2miqtpfvq.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gt2otkixhxu.html

Go:   slices.Reverse(arr)
来源：http://dali.hammf.cn/Article/details/gt2fkcmdcul.html

Ruby: arr.reverse
来源：http://dali.tian-w.cn/Article/details/gt2dcfpomjh.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gt2gofqigjt.html

[D12] 查找元素下标
来源：http://dali.yvedp.cn/Article/details/gt2tbtbgwpy.html

Py:   arr.index(x);  x in arr
来源：http://dali.ehwqpu.com/Article/details/gt2oxpcntpm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yoshwybt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2okyquile.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndlaajje.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dashuyun.cn/Article/details/gt2wgxjooof.html

Go:   slices.Index(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2fiioucqu.html

Ruby: arr.index(x)
来源：http://dali.pycfn.com/Article/details/gt2zhqfrmcf.html

C#:   list.IndexOf(x);
来源：http://dali.hnqzz.top/Article/details/gt2npkpidxw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jlsjyb.cn/Article/details/gt2veczpwhx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gotoacloud.top/Article/details/gt2yhktfuxq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gt2wlvqapwt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2icpzrcyj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2vpeoobcq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2zmivbxxf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gt2vrcodiub.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvigzghp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahlbyami.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cashguo.top/Article/details/gt2eelzalyp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gt2tgkahxdi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2okfhzbnd.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gt2thyzczrk.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gt2bkgrlglh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2fclgojai.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gt2lttexrzp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2gshmiiie.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vpwcjmak.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grpsojdx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gt2isopocqx.html

PHP:  array_unique($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2oftxrblm.html

JS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gt2fdhvlqio.html

TS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkiqhhlp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwmqhlvm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gt2idjzytdq.html

Ruby: arr.uniq
来源：http://dali.sxryk.cn/Article/details/gt2iruywgel.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gt2oyfdgpvz.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gt2vieuetnb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gt2zwikxxet.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2qcfvdsdc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gt2pjatpaip.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gt2qtttrajc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhengqikj.top/Article/details/gt2dllebgsg.html

Go:   // 手写循环累加
来源：http://dali.jqgfzy.top/Article/details/gt2cjeucziq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cheryme.top/Article/details/gt2agfccfzq.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gt2pidrqahv.html

[D17] 最大值与最小值
来源：http://dali.aizwys.cn/Article/details/gt2zyqdupfj.html

Py:   max(arr);  min(arr)
来源：http://dali.guannengcc.top/Article/details/gt2vzkfpnou.html

PHP:  max($arr);  min($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2xorrrjyt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gt2ubhefnht.html

TS:   Math.max(...arr);
来源：http://dali.andypj.xyz/Article/details/gt2okxfsfwt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgvpkynw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2skepfjjl.html

Ruby: arr.max;  arr.min
来源：http://dali.vqdsnc.cn/Article/details/gt2gwhfcoqc.html

C#:   list.Max();  list.Min()
来源：http://dali.pycfn.com/Article/details/gt2lyfpfpcu.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gt2uylmlyxa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gt2bqhwsaju.html

PHP:  array_merge(...$nested);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcdwxass.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.andypj.xyz/Article/details/gt2lcegljsm.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gt2eskszugu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2wrcvgwfg.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gt2pqicndkn.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gt2hsrucfed.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2dlsreukz.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gt2wixyhadr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dashuyun.cn/Article/details/gt2rdquhonh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dashuyun.cn/Article/details/gt2zxmcabyc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuanzx.com/Article/details/gt2xmpalzpu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hywenlv.cn/Article/details/gt2dptkunjs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gt2ubyhttho.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gt2nnyvnvvp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gt2xhnhoykv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnxiangtu.top/Article/details/gt2hdojthtl.html

[D20] 统计每个元素出现次数
来源：http://dali.havefunace.top/Article/details/gt2qrsilanr.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lafbaoxw.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gt2ypcscjrw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gt2jahkchuu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gt2kpayqpmt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gt2abuikpah.html

Go:   // 手写 map[T]int
来源：http://dali.zhixingplan.top/Article/details/gt2rvgeqqoi.html

Ruby: arr.tally
来源：http://dali.wangdashe.top/Article/details/gt2jowumkci.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhoulong.xyz/Article/details/gt2utlectqa.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gt2rzbgrcun.html

Py:   x in arr
来源：http://dali.shzxlz.cn/Article/details/gt2ecxgshwj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guannengcc.top/Article/details/gt2cwoxdixi.html

JS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjcwzglk.html

TS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gt2mwpjxfzm.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2esxnxtrw.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2pojgsesf.html

Ruby: arr.include?(x)
来源：http://dali.hfpthk.cn/Article/details/gt2tnrvxwaq.html

C#:   list.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gt2awahbfbn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gt2mhozprrj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sxryk.cn/Article/details/gt2dpcaaiww.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gt2nctovdvj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gt2ywxszgis.html

TS:   [...arr];
来源：http://dali.316326.xyz/Article/details/gt2ezmlvbof.html

Java: new ArrayList<>(list);
来源：http://dali.guowangkeji.top/Article/details/gt2eczhxjev.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gt2ylqqjtom.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gt2nhaxzblg.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gt2hipyyoda.html

[D23] reduce 累积计算
来源：http://dali.pengpengdd.cyou/Article/details/gt2tifikxtf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2yvntpmbp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2tknpjgeg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gt2aswwzyzy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gt2jjzdudgq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmsovcwk.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gt2efydmpso.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ehwqpu.com/Article/details/gt2gkmuxstc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hfpthk.cn/Article/details/gt2ugjxtnqt.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kqerzxpo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cqqwz.cn/Article/details/gt2mdmyqzhu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xinyue.icu/Article/details/gt2fjwvklll.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gt2smqlthyf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aizwys.cn/Article/details/gt2hnxgzoxt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nabcwoqd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gt2ahbjevjo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gt2hmeaxllk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258.top/Article/details/gt2hovdnfby.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gt2zgecemvx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shuidangran.top/Article/details/gt2objqinzn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gt2cqxhcifv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258888.top/Article/details/gt2sbjrwpeh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gt2ldmvkmog.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vavizlgx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gt2lmiryflt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2yjtjjpis.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangdashe.top/Article/details/gt2foonvjic.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvqpqppw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gt2loespblg.html

PHP:  implode(", ", $arr);
来源：http://dali.fzhhl.top/Article/details/gt2udvakvpo.html

JS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gt2biabzrfr.html

TS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2psupguxj.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gt2xjkklpye.html

Go:   strings.Join(strs, ", ")
来源：http://dali.iojbl.cn/Article/details/gt2mynpeizc.html

Ruby: arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2zhjrvlax.html

C#:   string.Join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gt2yijsceuk.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2wyoxoqci.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gt2imsjkzbw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ndygckyn.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwwarmdn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jiagoushi.top/Article/details/gt2ygduzxym.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sufxvd.cn/Article/details/gt2suvhxqud.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gt2jbaxcvbl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2mgteqtav.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yangfankeji.com/Article/details/gt2medlteyy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xylfe.cn/Article/details/gt2icepvlny.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigfzy.top/Article/details/gt2rvcpoups.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2ejnhbqmb.html

[E02] 重复字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2tjwgysow.html

Py:   "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uyazwknh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ketbmfls.html

JS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2ctzsmzys.html

TS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2lbxxlqef.html

Java: "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2iafjkypq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gt2dtmeskci.html

Ruby: "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gt2hcstounb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gt2qawpyltd.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gt2yrghwcop.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gt2ehvvghjx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exkfwsqw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gt2duwoyqqr.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2czyhnxpe.html

Java: s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gt2eehwwwtt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwpljkks.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhengqikj.top/Article/details/gt2xiqanmey.html

C#:   s.Substring(1, 3)
来源：http://dali.pycfn.com/Article/details/gt2wiidqyrx.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gt2qezcahzu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gt2ojsupkjw.html

PHP:  strpos($s, "x");
来源：http://dali.hysaishi.cn/Article/details/gt2kwjdsoxn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yueranfly.top/Article/details/gt2jnvjatxx.html

TS:   s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gt2opmtdseu.html

Java: s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gt2uudytqmz.html

Go:   strings.Index(s, "x")
来源：http://dali.dianchejie.cn/Article/details/gt2ormjkqbd.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gt2ytuficuf.html

C#:   s.IndexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2ziohkpms.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hywenlv.cn/Article/details/gt2rwanlawm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2gibupuxr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gt2eeqgcggo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afdhlqjn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdocobpo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2qspjebkl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ojnslpgy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2yfmharyx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2imsvncvs.html

[E06] 替换子串
来源：http://dali.chenlongwang.top/Article/details/gt2vebgkuyo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gt2skzfzkug.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.meibo888.top/Article/details/gt2uvocvwlr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhklyyuf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvcwaqzd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2bymxctpa.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpmkhhb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2xjxipmqj.html

C#:   s.Replace("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2sdkxvaqr.html

[E07] 按分隔符拆分
来源：http://dali.gzhubu.top/Article/details/gt2bkeomrqq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ehwqpu.com/Article/details/gt2qjpyjryt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2otpikzkp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xziqi.cn/Article/details/gt2gheejgro.html

TS:   s.split(",")
来源：http://dali.jqgufenzy.top/Article/details/gt2ffkgowoj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfibnueu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hfpthk.cn/Article/details/gt2oujcoasy.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gt2acebmhts.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fengsongda.top/Article/details/gt2xconggzd.html

[E08] 数组按分隔符合并
来源：http://dali.guannengcc.top/Article/details/gt2cyyhbfco.html

Py:   ",".join(items)
来源：http://dali.yj20258888.top/Article/details/gt2hrixvlbb.html

PHP:  implode(",", $items);
来源：http://dali.zhoulong.xyz/Article/details/gt2cqyzzwkf.html

JS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bbynqsvm.html

TS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2dqzejtpb.html

Java: String.join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gt2tpxpabre.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2alydytaj.html

Ruby: items.join(",")
来源：http://dali.316326.xyz/Article/details/gt2ngfylzmg.html

C#:   string.Join(",", items)
来源：http://dali.fengsongda.top/Article/details/gt2cfkcayrr.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llvhrost.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhengqikj.top/Article/details/gt2nohkowfe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gt2mirqdstn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nbgyhqpw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gt2rrdglvuy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ivvv.top/Article/details/gt2gyrlyynr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gt2livsyxbm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pjnlesxu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gt2xffuvrpm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gt2tyacrizt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2vbetmlnm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgfzy.top/Article/details/gt2kxtfzgds.html

JS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2njaszisp.html

TS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2nsqoxerw.html

Java: String.format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gt2zagxsuar.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2pjlptyvt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gt2xrbkaibi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gt2nhfgsiqj.html

[E11] 反转字符串
来源：http://dali.cashguo.top/Article/details/gt2quaytgoi.html

Py:   s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gt2sihqefoq.html

PHP:  strrev($s);
来源：http://dali.cucudq.cn/Article/details/gt2fbivcnoq.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2asltibue.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oldpookh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gt2xboxwmdj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gt2fgdofvts.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2afnfelec.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gt2uznmrfkp.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gt2itcctkah.html

Py:   s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gt2rtrbqvsd.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gt2nfwqrdlb.html

JS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gt2bxpyrzxn.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gt2blzfdqgr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gt2ukaqptni.html

Go:   strings.Count(s, "a")
来源：http://dali.daria6918.cn/Article/details/gt2jytjxljl.html

Ruby: s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2jvqjdejs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zdqjudy.top/Article/details/gt2ybrrikca.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gt2stbfxihp.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gt2gwfysxjh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlbeehiq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2viewkdhk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2sgfhzhgt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2ntawplyh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nwbrower.top/Article/details/gt2crgeedks.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pengpengdd.cyou/Article/details/gt2uowfovuf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gt2xytzwvvy.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gt2okxozhfq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xinyue.icu/Article/details/gt2njesngrg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2homeazzj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ybcxt.top/Article/details/gt2xgposyru.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2haahngkm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2qzumpxql.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gt2cjvrgemd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2exqjigqz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuanzx.com/Article/details/gt2kqfusrzl.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gt2optqkwlp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dashuyun.cn/Article/details/gt2ythqsrny.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fzhhl.top/Article/details/gt2rtpsufov.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shuidangran.top/Article/details/gt2xkpiqpwl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sysykeji.top/Article/details/gt2dmtrylpu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.vqdsnc.cn/Article/details/gt2rijvpfqi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tian-w.cn/Article/details/gt2jqxucxsg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2hkwdvnjt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gt2lyzweotc.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gt2axhdvcar.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gt2xxdwamrs.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gt2lgrvvlhx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2ysmrcvlq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gt2fkcqrnzu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gt2hoirzdrp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yvedp.cn/Article/details/gt2kgeoueoe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ydzc1.top/Article/details/gt2vaytilxv.html

C#:   1234567.ToString("N0")
来源：http://dali.havefunace.top/Article/details/gt2dlmqzfoy.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gt2pekipyme.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sufxvd.cn/Article/details/gt2xufpfvpk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gt2gaeaimpo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gt2dfibhxkn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2jckqpylv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwlqirhu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gt2revaipqa.html

Ruby: s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gt2gxhctydi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gt2bjmpausq.html

[E18] 模板占位符替换
来源：http://dali.hywenlv.cn/Article/details/gt2imolearq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.iojbl.cn/Article/details/gt2ldzzdwsu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gt2dpmdbths.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2frarykor.html


<!-- 参考信息 -->