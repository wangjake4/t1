代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.cdnleiting.top/Article/details/gtmwlahpgs.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gtqemfaghi.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtavsqfkhb.html

Ruby: arr.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduphwtow.html

C#:   list.Reverse();
来源：http://dali.yonumen.top/Article/details/gtaxrfvkdv.html

[D12] 查找元素下标
来源：http://dali.haohaochexian.top/Article/details/gtyzxobnmh.html

Py:   arr.index(x);  x in arr
来源：http://dali.dashuyun.cn/Article/details/gtosmevypo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gthvctddhu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gtryhkezuj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtjdqbwrej.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gthdtdsvsv.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtyxufscqz.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gtzvkxxarr.html

C#:   list.IndexOf(x);
来源：http://dali.gzhubu.top/Article/details/gtjkcfbywe.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gtlznzggdb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hammf.cn/Article/details/gtdwpvgdoe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gtuegvyszu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gtytxiuork.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtnjtbatad.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjdrekwa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gtsdjnrlvk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gtkjoappax.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ivvv.top/Article/details/gtrxmzjafh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxuanxn.top/Article/details/gtkiqmqerq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtkoeoac.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtibqjkqeb.html

JS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gthsnxufra.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtpyvjqfgi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtqrvrphku.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gtobbrphtf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtcozxgacs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtrqgkxizq.html

[D15] 去重
来源：http://dali.chenzaomai.com/Article/details/gtmfyygujl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtqehehvlq.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrqqotex.html

JS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbinfwiwg.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtzrjtzzfd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangdashe.top/Article/details/gtzsbmjhfv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gtmtxgeeqv.html

Ruby: arr.uniq
来源：http://dali.fzhhl.top/Article/details/gtcgxqqavr.html

C#:   list.Distinct().ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtakzllqxy.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gthmdtedej.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphsjjfqi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gtdluyhzui.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtvcuaubpe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gtyaqhcrgt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gtezgwpvpl.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gtxoelybth.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gtbcfilacx.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gtcidbyepv.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gtpijektuc.html

Py:   max(arr);  min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtjennyarn.html

PHP:  max($arr);  min($arr);
来源：http://dali.aizwys.cn/Article/details/gtbbygluuw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtckcakxjs.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gtavmuxwqq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gtztmftdhk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtfobefbvl.html

Ruby: arr.max;  arr.min
来源：http://dali.iojbl.cn/Article/details/gtfgptmjpy.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigufen.top/Article/details/gtawkfudpp.html

[D18] 扁平化嵌套数组
来源：http://dali.yonumen.top/Article/details/gtltkyyrer.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gzhubu.top/Article/details/gtklmmkava.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gtgqkfcwfb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenzaomai.com/Article/details/gtyxrjybrg.html

TS:   nested.flat();
来源：http://dali.yuxming.cn/Article/details/gtvmrnwupi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jianghu66.top/Article/details/gtgmkaldjr.html

Go:   // 手写双层循环
来源：http://dali.zhengqikj.top/Article/details/gtojasyyxa.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gtwcwdqael.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tian-w.cn/Article/details/gtsxmzymjo.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxugdesl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gtxrflmjfy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj202588.top/Article/details/gtqgpmnqpd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhengqikj.top/Article/details/gtwmmpxtgm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtvyfgseeg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jianghu66.top/Article/details/gtleboqxek.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gtabgtsveh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gtbfgfeaxs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gtbphdrwic.html

[D20] 统计每个元素出现次数
来源：http://dali.haohaochexian.top/Article/details/gtybrrmced.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gtcxoztlrj.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gtorpvlzjl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtsmhugynz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gtuuhzvwjf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yangfankeji.com/Article/details/gtugkrnqab.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gtdudkrxid.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gtwgbddqvt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmepilwd.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gtdlreqdbf.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gtlubzvpqp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gtgomditgp.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtofqtzwkd.html

TS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtpuvjecfa.html

Java: list.contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtsaembfhi.html

Go:   slices.Contains(arr, x)
来源：http://dali.guannengcc.top/Article/details/gthsjauvub.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gtnixmqvsb.html

C#:   list.Contains(x)
来源：http://dali.cashguo.top/Article/details/gtczovqmtw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnxiangtu.top/Article/details/gtjbwpmddb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtaxerfxql.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gtzgjecyyf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gtrazyfamz.html

TS:   [...arr];
来源：http://dali.jlsjyb.cn/Article/details/gtzomvyrgm.html

Java: new ArrayList<>(list);
来源：http://dali.sxryk.cn/Article/details/gtpdbqbqel.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guowangkeji.top/Article/details/gtvzuijoye.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangshuangyany.cn/Article/details/gtgdvcrhey.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gtbrqwtyam.html

[D23] reduce 累积计算
来源：http://dali.mhx1999.top/Article/details/gtwhdqjewf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtgjzuztpk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gthjhdcstw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtsgvyntpk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gtygozgisp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gtffofuvnp.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtextntojs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xziqi.cn/Article/details/gtrpqtwvyk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gturdamval.html

[D24] 字典 / Map 基本操作
来源：http://dali.fzhhl.top/Article/details/gtucihdzjk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gtbazaevty.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigfzy.top/Article/details/gtieydxvmn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.iojbl.cn/Article/details/gtqhhlbrsj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtehwgbbyo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gtgnxyiler.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtafpkywpj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqmgosvg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dianchejie.cn/Article/details/gterasnsxe.html

[D25] Set 集合去重与交并差
来源：http://dali.daria6918.cn/Article/details/gtqukgfamr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryjpdwhe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxhbkjpz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvetuocxv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gttcuslkls.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.smart0.xyz/Article/details/gtaxkyggnb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jiagoushi.top/Article/details/gtbjmnvfss.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.meibo888.top/Article/details/gtrbocqiiy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gtotivkinx.html

[D26] 数组转字符串
来源：http://dali.ppjwa.cn/Article/details/gtbvrdyadx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gtlptaykmn.html

PHP:  implode(", ", $arr);
来源：http://dali.daxiang520.top/Article/details/gtlnwakrsl.html

JS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtkljlddqh.html

TS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtpjguzkmm.html

Java: String.join(", ", list)
来源：http://dali.tanke756.top/Article/details/gtsyldsomu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgufenzy.top/Article/details/gtrywqxnds.html

Ruby: arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtrqhgpbgn.html

C#:   string.Join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gtmmgofpop.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttoiojrkw.html

E. 字符串处理
来源：http://dali.yj202588.top/Article/details/gttbufeuqj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrezufaoi.html

[E01] 拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtfgqiugrm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gtvjxwksqj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cashguo.top/Article/details/gtswhihrqk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteaehwgzg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtnllvsbra.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ivvv.top/Article/details/gtqyqnetbn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gtychbqsej.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxcnfwwi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aizwys.cn/Article/details/gthnqjaczr.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gtbtrmkrit.html

Py:   "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtgsoxiknh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.meibo888.top/Article/details/gtkqxessaz.html

JS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtygvkthxi.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtddoptnho.html

Java: "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtttpwtfsg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gtssroaiyr.html

Ruby: "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gtnrawonoq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gtiyhqrabi.html

[E03] 截取子串
来源：http://dali.yonumen.top/Article/details/gtmryvondq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guowangkeji.top/Article/details/gtxynbkvbx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtqadkarnl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtywpqotxt.html

TS:   s.slice(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtpprxiolf.html

Java: s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtlkqysgqb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258.top/Article/details/gtloxzarme.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tanke756.top/Article/details/gthcgnpsbb.html

C#:   s.Substring(1, 3)
来源：http://dali.shzxlz.cn/Article/details/gtejmejckl.html

[E04] 查找子串位置
来源：http://dali.cashguo.top/Article/details/gtlxnovhfi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtoxyzymoj.html

PHP:  strpos($s, "x");
来源：http://dali.snrcjt.cn/Article/details/gthmpogtmi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gtzneuslbk.html

TS:   s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtuoczeube.html

Java: s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtibrlvsyr.html

Go:   strings.Index(s, "x")
来源：http://dali.ppjwa.cn/Article/details/gtojfhbrar.html

Ruby: s.index("x")
来源：http://dali.316326.xyz/Article/details/gthsrrjvex.html

C#:   s.IndexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtjbdltgbw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhiwuduotai.top/Article/details/gtuzgdfubn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.smart0.xyz/Article/details/gtuhfuipfs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.kuanghao11.cn/Article/details/gtltoxprho.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtqouybuif.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gtnwsdeqnn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtdgztruwb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aizwys.cn/Article/details/gtjhscyyfn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtoixwvzez.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtgbnfupgc.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gtsxnuddxm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtgjsfozox.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ppjwa.cn/Article/details/gtlfzctzeb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtdizgtefr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtppmlyngs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gttbdcwqbs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gteckfjmqd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtiefcgftm.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258.top/Article/details/gtqpdsdkwe.html

[E07] 按分隔符拆分
来源：http://dali.kuanghao11.cn/Article/details/gttlwwmzvw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gtdispzkte.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtlxcwibhj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.0kj1m.cn/Article/details/gtdcldkpni.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjirfxld.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fengsongda.top/Article/details/gtuoqlqmbu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sxryk.cn/Article/details/gtzslkajup.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gtzyphzqki.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gtewdlyske.html

[E08] 数组按分隔符合并
来源：http://dali.zdqjudy.top/Article/details/gtfxggdhqx.html

Py:   ",".join(items)
来源：http://dali.hysaishi.cn/Article/details/gtmuipjxpd.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gtgascwxdy.html

JS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtmkzplnpg.html

TS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtktgwgees.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gtgjbrexvo.html

Go:   strings.Join(items, ",")
来源：http://dali.kuanghao11.cn/Article/details/gtdcigvlwx.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtktipropt.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtyfzqrgvh.html

[E09] 去除所有空白字符
来源：http://dali.jianghu66.top/Article/details/gtljqqqaph.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nwbrower.top/Article/details/gtzdqaxbfo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gtzhfhwwae.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtitbakehb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtqbhpeupj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtpkqwjnjp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tian-w.cn/Article/details/gtxobytzgi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cdnleiting.top/Article/details/gtwffujeiv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gtucgeomlf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hywenlv.cn/Article/details/gttpjtimyd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtezmfifhh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gtmpotiuex.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtdclckghw.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtfppspexy.html

Java: String.format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtngeggpnd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtefbbfhcm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtaarkehhg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nwbrower.top/Article/details/gttffdvqdp.html

[E11] 反转字符串
来源：http://dali.sysykeji.top/Article/details/gtesnxdzfg.html

Py:   s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtjzymleom.html

PHP:  strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gtjnfqdgpb.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtarhvicdg.html

TS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtctpohytd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gtclmfldjl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.havefunace.top/Article/details/gtrfomunyf.html

Ruby: s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtpqcgdgai.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gttkxaynre.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gtnqpgsuhd.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtptesnclt.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgfzy.top/Article/details/gtvvcqxbjl.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtdbgxomii.html

TS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtazhsrvuw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gtbsfnufal.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gtknpazgfr.html

Ruby: s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtneengvhs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gtjdfnsppg.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gtghzqlxkh.html

Py:   for ch in s: print(ch)
来源：http://dali.xylfe.cn/Article/details/gtaalitwsi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.mhx1999.top/Article/details/gtxfyalste.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtortcohea.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtqjmqgbde.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gtizelsidi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jianghu66.top/Article/details/gthglylvpk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cucudq.cn/Article/details/gtifhajfsu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guannengcc.top/Article/details/gtfaivcffn.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gtkqhlethe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gtiamwgpov.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.svipenyu.cn/Article/details/gtvkuzcrsn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.andypj.xyz/Article/details/gtspgupulw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigfzy.top/Article/details/gtbkqerhlp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgeefdnjt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gtuosvfume.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gthryoqkzk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutvbxoxg.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gtrduulojr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbaxnhbpi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtbeylhbbj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtjsxvvfrt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jyoumei.cn/Article/details/gtmcwdkeno.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gtqajddynd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cucudq.cn/Article/details/gtxutviwoj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zdqjudy.top/Article/details/gtgvcclznj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtozybjnjr.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gttznlzotz.html

Py:   f"{1234567:,}"
来源：http://dali.bjfxy.top/Article/details/gtafgbipsh.html

PHP:  number_format(1234567);
来源：http://dali.xuanzx.com/Article/details/gtzawlyarv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtitrdsnkd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkjmvrhr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtjxjxfbnm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gtcxvkznrd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hysaishi.cn/Article/details/gtpotvrrda.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gtsshoghbj.html

[E17] 首字母大写
来源：http://dali.jianghu66.top/Article/details/gtltsupddu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gtmiahkqgo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgfzy.top/Article/details/gtsxmalkrt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtbjknfatv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gttqttyeod.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gtrrxqqzpj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtajzbshnk.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gteljhabzo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258888.top/Article/details/gtpjiuixdd.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gtthbbglqn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gtknzfjlce.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuanzhike.top/Article/details/gtpqmauflp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtiwqdyvko.html


<!-- 参考信息 -->