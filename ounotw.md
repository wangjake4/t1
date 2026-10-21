代发 wailian999

Ruby: arr.index(x)
来源：http://dali.birdmap.top/Article/details/gtnpayyrpq.html

C#:   list.IndexOf(x);
来源：http://dali.yongpay.top/Article/details/gtnvxtmqqq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gtqkbhvjwy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.svipenyu.cn/Article/details/gtzhojiprf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gtzdewuvmm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtcndwqsls.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtpqrucgrc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gthgyxgzfv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hywenlv.cn/Article/details/gtguheoaip.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sweek.top/Article/details/gtaljcwxrc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ydzc1.top/Article/details/gtxdfgpbgn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guowangkeji.top/Article/details/gtwfckpouq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenkbuweu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gtsasxvljx.html

JS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtiqmzxumg.html

TS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtxsiqlbsf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cashguo.top/Article/details/gthnfnxutc.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gtwkepjqaw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvbabhts.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.316326.xyz/Article/details/gtllkskuxe.html

[D15] 去重
来源：http://dali.hysaishi.cn/Article/details/gtullqgzku.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtjyqgkzld.html

PHP:  array_unique($arr);
来源：http://dali.daria6918.cn/Article/details/gttwcyrrpx.html

JS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtirngsyti.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtnxiefyhf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gtumajgtii.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gtzrxdchua.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gtnllomcmb.html

C#:   list.Distinct().ToList()
来源：http://dali.hysaishi.cn/Article/details/gtowivbuzp.html

[D16] 求和与平均值
来源：http://dali.9152youxi.cn/Article/details/gtddldvrpo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cucudq.cn/Article/details/gtgtybunwa.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ivvv.top/Article/details/gtsmbkgsci.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gtngdfpcit.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtraxydqos.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gtstjywrol.html

Go:   // 手写循环累加
来源：http://dali.aibaodan.cn/Article/details/gtbuvnizrg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtwboqqgbj.html

C#:   list.Sum();  list.Average()
来源：http://dali.pycfn.com/Article/details/gttserzprb.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gtcrwkxokz.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gthugosnys.html

PHP:  max($arr);  min($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtptkavosi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jianghu66.top/Article/details/gtnqpjrykg.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gtjgpefuvl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gtdgzlqghw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtiumjsvrg.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gtvxvxqkdl.html

C#:   list.Max();  list.Min()
来源：http://dali.zhixingplan.top/Article/details/gtoxaibyuf.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gtsfvpwglv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gteispcmjl.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gthyufmqru.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuanzhike.top/Article/details/gtmetpcwnl.html

TS:   nested.flat();
来源：http://dali.birdmap.top/Article/details/gtqpenxgok.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gtztrwcecs.html

Go:   // 手写双层循环
来源：http://dali.chenzaomai.com/Article/details/gtmyjepxtw.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gtnkjxyfbv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xinyue.icu/Article/details/gtjnecxluu.html

[D19] 按字段分组
来源：http://dali.jinqigfzy.top/Article/details/gtaustjtfz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ydzc1.top/Article/details/gtgdfkpdlq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gtuibwpuan.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gtisvecnjh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtbwedbvrl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gtadfsdwhn.html

Go:   // 手写 map[string][]T
来源：http://dali.cheryme.top/Article/details/gtccbdklvw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tianlin.xyz/Article/details/gtkwexscqp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxvkljic.html

[D20] 统计每个元素出现次数
来源：http://dali.shzxlz.cn/Article/details/gtoqgilqcr.html

Py:   Counter(arr)
来源：http://dali.yonumen.top/Article/details/gtpwyxsask.html

PHP:  array_count_values($arr);
来源：http://dali.shuidangran.top/Article/details/gtceokwhld.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gtdsykdhau.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtfqfsniea.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzvbhhne.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gthxyabrhx.html

Ruby: arr.tally
来源：http://dali.meibo888.top/Article/details/gtrlsugkbl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.mhx1999.top/Article/details/gtgoyciemw.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gtcmvxeyst.html

Py:   x in arr
来源：http://dali.fengsongda.top/Article/details/gtcchvvaru.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gtnmghjkfd.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtcflamskm.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtauztiunw.html

Java: list.contains(x)
来源：http://dali.hnqzz.top/Article/details/gtfauzyfsx.html

Go:   slices.Contains(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtkoibbqey.html

Ruby: arr.include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtjkckvmku.html

C#:   list.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtmeuvqumf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gtnfmfnwgq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gtekqjwixk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gttfyfpemh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gtmwdkikxh.html

TS:   [...arr];
来源：http://dali.yonumen.top/Article/details/gtyetrkngr.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gthvkdxtyy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gtssigyumk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtfvhycr.html

C#:   new List<int>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtwnptvcim.html

[D23] reduce 累积计算
来源：http://dali.aibaodan.cn/Article/details/gtuifjznzf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gtfygpuhhz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gtdijeerot.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtrrfvrsxo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtvgdcqjew.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.feifeiyinyue.top/Article/details/gttqtqkxxv.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtbguaegeo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gtmvpfocaq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhixingplan.top/Article/details/gtjdhasxpl.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gtoprmjppp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuanzx.com/Article/details/gthhooyuxw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gtupihjguo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gtplrxjsmy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtyjlxkvpa.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhjyncsl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gteaalxwab.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtpmzmrijw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigufen.top/Article/details/gtsukcunuf.html

[D25] Set 集合去重与交并差
来源：http://dali.vqdsnc.cn/Article/details/gtwrifxetq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hfpthk.cn/Article/details/gtywzuuzjr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nwbrower.top/Article/details/gtchxjhoia.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aizwys.cn/Article/details/gtdgtggxis.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblkjdovx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fzhhl.top/Article/details/gtynpnkpqn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyvelkxc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gtellcjcgm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gtojekqlxh.html

[D26] 数组转字符串
来源：http://dali.nanxinkj.top/Article/details/gtobcvlllf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gtokzxegfg.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gtnpsvkaxv.html

JS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gtkzqcbdrr.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtaokxvcjn.html

Java: String.join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtuqvgbjoe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zdqjudy.top/Article/details/gtzsmooadc.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtuztbmpiq.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtdqzptirz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtgpvlpygp.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gtamkoombj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtusfcbibt.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtfyzawwoe.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgfzy.top/Article/details/gtlndciqav.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258888.top/Article/details/gtwwfwguvf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtiemozimm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gtcdtpxmsb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aizwys.cn/Article/details/gtxskrxcng.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtcsqjbwue.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnxiangtu.top/Article/details/gtndovgdnh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtvmupecjd.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gtjqnxmzgi.html

Py:   "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gtkixsjcpi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yonumen.top/Article/details/gtoxjadyhj.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtyckukjwf.html

TS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtwvjtfbfi.html

Java: "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtnokqozdb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hfpthk.cn/Article/details/gtmacdnvht.html

Ruby: "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gtexrrktld.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xinyue.icu/Article/details/gtbkuqfoia.html

[E03] 截取子串
来源：http://dali.cashguo.top/Article/details/gtetpmbult.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xziqi.cn/Article/details/gtnpbijmmj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtosxpzuxd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtrspfygrx.html

TS:   s.slice(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtfegguxla.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtyudccwxd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jiagoushi.top/Article/details/gtjoxthwfn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhengqikj.top/Article/details/gthuebbbmp.html

C#:   s.Substring(1, 3)
来源：http://dali.snrcjt.cn/Article/details/gtsvqrxjjv.html

[E04] 查找子串位置
来源：http://dali.wangdashe.top/Article/details/gtxvhsgmsa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.andypj.xyz/Article/details/gtnpdljyhs.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gtolltqiel.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jiagoushi.top/Article/details/gtkzjzfuri.html

TS:   s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtjubbfrec.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtuuurgboh.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgufenzy.top/Article/details/gtncskjywl.html

Ruby: s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtebolacyt.html

C#:   s.IndexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gttsejxjcp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczhvyjjv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenzaomai.com/Article/details/gtnxfilcuh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258.top/Article/details/gtpkagbvtu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtisyqkpln.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daria6918.cn/Article/details/gtmldawkzf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtggncxwsr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gtvpnbhjhc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.bjfxy.top/Article/details/gtubmpnqmy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtxqwdypyj.html

[E06] 替换子串
来源：http://dali.meibo888.top/Article/details/gtpehcvvev.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtusuokxpc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigfzy.top/Article/details/gtdhzeuolk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtfxndjurw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtjslqvspg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gteuzrpjse.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtoknqbqay.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtpehaytmq.html

C#:   s.Replace("a", "b")
来源：http://dali.316326.xyz/Article/details/gtxyrkjkac.html

[E07] 按分隔符拆分
来源：http://dali.zhengqikj.top/Article/details/gtwalvrugm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daxiang520.top/Article/details/gtvevuyjtx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtnjrraljw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gtzurgnlpu.html

TS:   s.split(",")
来源：http://dali.fzhhl.top/Article/details/gttocrerhy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xziqi.cn/Article/details/gtcjumxxuf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258.top/Article/details/gtwyhlnwsd.html

Ruby: s.split(",");  s.split
来源：http://dali.sxryk.cn/Article/details/gttsligclp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.havefunace.top/Article/details/gtcbdbfakn.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gtzubaeapf.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtaeuxegpi.html

PHP:  implode(",", $items);
来源：http://dali.0kj1m.cn/Article/details/gtkdqlqnvg.html

JS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtzzqeewng.html

TS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtrzawggsl.html

Java: String.join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtkfmbnvky.html

Go:   strings.Join(items, ",")
来源：http://dali.sufxvd.cn/Article/details/gtzbxysdne.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gtxlukbman.html

C#:   string.Join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gtyjtqxpig.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gtrvkuxukn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuxming.cn/Article/details/gtxdlegyto.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.bjfxy.top/Article/details/gtddoygjab.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gtsnqyjgki.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gtwawzfljy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gtwbhfowsv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybkvsuhf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.bjfxy.top/Article/details/gtktgrcznn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gtodldyynu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gtrgmhcwcv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gtkbcmkgnk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.feifeiyinyue.top/Article/details/gtqnzwabyr.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtipyrqkzp.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtzsgwisgb.html

Java: String.format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtckutdsdq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtadmtribr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtxxfslaqc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gtiibvsdsj.html

[E11] 反转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtworwlynu.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gtnmwqevcg.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gttanffyef.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtctslnmag.html

TS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtrfyfqeou.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtljaurwtq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtkuyoeqdy.html

Ruby: s.reverse
来源：http://dali.ydzc1.top/Article/details/gtmykaferf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gtwhpeajxm.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gteyknhvsa.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gthoxtmdza.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gtsdolshlr.html

JS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtxqxxkzor.html

TS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gtfzsglzpp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shzxlz.cn/Article/details/gtsohvzzlr.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258.top/Article/details/gtsxypxyqy.html

Ruby: s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gthzerdyvw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gtkeviljys.html

[E13] 逐字符遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnlhkmoa.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gtldzmwmtf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuanzhike.top/Article/details/gthswjrvaw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gtlpfozjnr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gtwemolfdm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtpdkvvarn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtnpcmnerk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gtaynpdtji.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtgbogcikl.html

[E14] URL 编码与 Base64
来源：http://dali.hfpthk.cn/Article/details/gtoebtpfgs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pycfn.com/Article/details/gtjbgrnzxy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtyaabercq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangshuangyany.cn/Article/details/gtmgrqmqvh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.svipenyu.cn/Article/details/gtdgfwuiqu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtnlypcuwa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gtphbjxdzn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gturksvxgn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtsdtmgxbw.html

[E15] HTML 转义 / 反转义
来源：http://dali.aizwys.cn/Article/details/gtpvvcugbp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hywenlv.cn/Article/details/gthiilqckq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtmysguuos.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gtibdhcqzm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnqzz.top/Article/details/gtcpaesvgc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gtmwrqgboy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cucudq.cn/Article/details/gtrhcnznsb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gtjkjjeqyt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gtrvaiqdvp.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gtklimfqiz.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gtaxzqnhjb.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gtujofldwk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtwzvdwlny.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gtnyckouzp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cucudq.cn/Article/details/gtjxaawkpl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yangfankeji.com/Article/details/gtyapwqpxs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jyoumei.cn/Article/details/gtgrcvopcv.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gtjcjgtcyp.html

[E17] 首字母大写
来源：http://dali.bjfxy.top/Article/details/gtpyusbhtm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gtdowrlbkr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gtiknbeubg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtwtmsgdog.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtbhqnaffz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gtdzxendwo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tian-w.cn/Article/details/gtoymlgmme.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gtkxhzulee.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gtmzfdjxbd.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gtdzvjbhac.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gteydnfmvo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgfzy.top/Article/details/gtbjnppbfs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyauauoy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtptvyfeve.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtzsdbalej.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtdjmwwsxd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hfpthk.cn/Article/details/gtdobnuayq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gtrmxryygs.html

[E19] 多行文本按行拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtpiqzosma.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gtkgioqnlk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gtwrtsyama.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtcvlamfdq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtobycujwi.html

Java: s.lines().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtmrftuitj.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gtxwrnirfl.html


<!-- 参考信息 -->