代发 wailian999

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gt2guuesecr.html

C#:   list.IndexOf(x);
来源：http://dali.yueranfly.top/Article/details/gt2qxvgzgiu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llatcpog.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2zniwgqzi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2dqmqozdu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gt2yyscayat.html

TS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gt2nvggwaey.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2toulyxmc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuanzhike.top/Article/details/gt2rdrcyyks.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhoulong.xyz/Article/details/gt2wczkzbxc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2dxiugequ.html

[D14] 映射转换（每个元素变形）
来源：http://dali.redwolf501.top/Article/details/gt2qaqlowgr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigfzy.top/Article/details/gt2mxvizdwy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2uqcivsgm.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gt2qdgnfzwc.html

TS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gt2tgohqvor.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2bygpxmyn.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gt2dprbpckj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shuidangran.top/Article/details/gt2ciretwcl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2oonuvria.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gt2dtpwwnnj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gt2fshgmtda.html

PHP:  array_unique($arr);
来源：http://dali.mhx1999.top/Article/details/gt2nvohxagl.html

JS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpylsdop.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gt2kvlzmfjq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fengsongda.top/Article/details/gt2btgoifxx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cheryme.top/Article/details/gt2benkygmi.html

Ruby: arr.uniq
来源：http://dali.jianghu66.top/Article/details/gt2wywvsyim.html

C#:   list.Distinct().ToList()
来源：http://dali.iojbl.cn/Article/details/gt2ilifsfkf.html

[D16] 求和与平均值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lnmashdr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gt2sihlawto.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2rtyxsfsy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gt2htcrjvih.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gt2zzrgfkwx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.svipenyu.cn/Article/details/gt2dajvxgdi.html

Go:   // 手写循环累加
来源：http://dali.nanxuanxn.top/Article/details/gt2vlfhjyrd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258.top/Article/details/gt2jcmilaws.html

C#:   list.Sum();  list.Average()
来源：http://dali.c1oappe.top/Article/details/gt2sdtjbqkk.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gt2uhjyidie.html

Py:   max(arr);  min(arr)
来源：http://dali.c1oappe.top/Article/details/gt2bgftmqrz.html

PHP:  max($arr);  min($arr);
来源：http://dali.aizwys.cn/Article/details/gt2dyxyvqok.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gt2lkykbuup.html

TS:   Math.max(...arr);
来源：http://dali.nanxinkj.top/Article/details/gt2fmibxzrt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2tnosfuog.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2bcswnouy.html

Ruby: arr.max;  arr.min
来源：http://dali.cucudq.cn/Article/details/gt2loddwsew.html

C#:   list.Max();  list.Min()
来源：http://dali.svipenyu.cn/Article/details/gt2zzwjekya.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlmcgoj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gt2wmaigbmy.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gt2lsoebiue.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gt2gmzarpfe.html

TS:   nested.flat();
来源：http://dali.xziqi.cn/Article/details/gt2hekxgzbc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2lvjhwgol.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gt2eofgmead.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gt2yytikdxp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gt2wrivoxui.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gt2qrhyepsw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.svipenyu.cn/Article/details/gt2iouuicud.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guowangkeji.top/Article/details/gt2egkdafww.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlfxwlyp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gt2bzhzoogk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gt2piilfqrt.html

Go:   // 手写 map[string][]T
来源：http://dali.guannengcc.top/Article/details/gt2bhaobhaa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2locxnlen.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmtzbwgk.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gt2llrvsckr.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2xuqzbdvq.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gt2esphortk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gt2ocigclfr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gt2azbghpzf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gt2eaabzusw.html

Go:   // 手写 map[T]int
来源：http://dali.aizwys.cn/Article/details/gt2ovnqgkqo.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gt2audqgbwk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gt2vrdquvtq.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gt2cfwikvyj.html

Py:   x in arr
来源：http://dali.jinqigfzy.top/Article/details/gt2ifblfoss.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gt2mntqnqwm.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2adqkbyro.html

TS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gt2zvalfmey.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2ymtrkuvr.html

Go:   slices.Contains(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2zpijupvm.html

Ruby: arr.include?(x)
来源：http://dali.tianlin.xyz/Article/details/gt2vcolwjuu.html

C#:   list.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gt2oigovovi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gt2nijjcwgg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2gkrpdhbm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gt2clfumcdd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gt2baxjdbvn.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gt2qgnnbdhw.html

Java: new ArrayList<>(list);
来源：http://dali.sxryk.cn/Article/details/gt2nnuhbcsh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxhzmvkl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gt2pqqhkgej.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gt2djciykva.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzazrtzk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2goklcnxz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guowangkeji.top/Article/details/gt2kalvljwu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2eefhwrtz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2npntxipq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.mhx1999.top/Article/details/gt2agrammeg.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gt2lskbwkyj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sufxvd.cn/Article/details/gt2ibrmgvcq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hfpthk.cn/Article/details/gt2adhskuoc.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eljyijqv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gt2uabyaryt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gt2tvqptrpv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yvedp.cn/Article/details/gt2rxpqomcb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yonumen.top/Article/details/gt2fkzajegz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gt2ljyyrtqq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gt2jhojgbyg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gt2qelivqwg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sxryk.cn/Article/details/gt2zbaqsakr.html

[D25] Set 集合去重与交并差
来源：http://dali.bjfxy.top/Article/details/gt2xuvnlkci.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenjidiqi.icu/Article/details/gt2uljfxjty.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zycfv.cn/Article/details/gt2vvxwuisx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2addhsycn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigufen.top/Article/details/gt2qauikxip.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jiagoushi.top/Article/details/gt2brdcmlhd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fengsongda.top/Article/details/gt2mnzuqhan.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hywenlv.cn/Article/details/gt2oetcsqdy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gt2ccknnzle.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gt2yylnifji.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dashuyun.cn/Article/details/gt2hkmdegbz.html

PHP:  implode(", ", $arr);
来源：http://dali.yueranfly.top/Article/details/gt2bjeqzath.html

JS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2mxkhvwkc.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2eokginzf.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gt2yozfiwyd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.andypj.xyz/Article/details/gt2bkgkaukn.html

Ruby: arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzzizyix.html

C#:   string.Join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gt2ebgwmmou.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2cuohlxrn.html

E. 字符串处理
来源：http://dali.zhengqikj.top/Article/details/gt2wqezncmz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2lhutlmmf.html

[E01] 拼接字符串
来源：http://dali.sweek.top/Article/details/gt2lhpeuuna.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yueranfly.top/Article/details/gt2oofrgmoh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.havefunace.top/Article/details/gt2ajupvxrf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gt2pjlihtab.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gt2cjkdrtdz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aizwys.cn/Article/details/gt2lhgsqzvm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gt2auudfbyc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.bjfxy.top/Article/details/gt2qxuwarpj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2chgyozao.html

[E02] 重复字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2grluvhiz.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gt2xshwubmx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gt2jppfukgj.html

JS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gt2yxmazakz.html

TS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2pyymyfyj.html

Java: "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2ewsirqfm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gt2kjniyvqs.html

Ruby: "ab" * 3
来源：http://dali.havefunace.top/Article/details/gt2libpbmup.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmnrykli.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmnrqcpn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gt2ybgvqhka.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2uyjfnfia.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2bvdihnhp.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2goqmzsad.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2gequelwy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shuidangran.top/Article/details/gt2bfiyselv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cqqwz.cn/Article/details/gt2gvopusof.html

C#:   s.Substring(1, 3)
来源：http://dali.haohaochexian.top/Article/details/gt2bcksigqy.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgfixym.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2aypdftwx.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gt2tjewlpqu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shzxlz.cn/Article/details/gt2rtmbmlcb.html

TS:   s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gt2yfuyqqvz.html

Java: s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gt2oyzfuusz.html

Go:   strings.Index(s, "x")
来源：http://dali.wangdashe.top/Article/details/gt2myxegjnq.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2msvjgsso.html

C#:   s.IndexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gt2klzfzisf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsdnvhxm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gt2rabaedrw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enwjwmyb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2ukgjmyuw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdtijjzp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gt2wzbjjyqw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cqqwz.cn/Article/details/gt2ydrpaxqx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guowangkeji.top/Article/details/gt2yyufivlp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzulvygs.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vpyohfew.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ierojshf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aizwys.cn/Article/details/gt2utykxtgl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2zsqtfddx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2fuypkkmk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2neynvagw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gt2bvcijcbq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2ndvmlmqo.html

C#:   s.Replace("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2ainkrqjc.html

[E07] 按分隔符拆分
来源：http://dali.yj20258888.top/Article/details/gt2djoloewb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuxming.cn/Article/details/gt2nxtelbxs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vscvsdsz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gt2fyueutma.html

TS:   s.split(",")
来源：http://dali.mhx1999.top/Article/details/gt2hmvcmzzw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jianghu66.top/Article/details/gt2jwtkchjb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gt2qjanrplq.html

Ruby: s.split(",");  s.split
来源：http://dali.tian-w.cn/Article/details/gt2wljjkclf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gt2wabupixj.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gt2myjxzrtv.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gt2rodiagcw.html

PHP:  implode(",", $items);
来源：http://dali.zhixingplan.top/Article/details/gt2vhiqxvdm.html

JS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gt2xgjbcpdy.html

TS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gt2wwcryofu.html

Java: String.join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gt2nrvglnee.html

Go:   strings.Join(items, ",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovjemmsh.html

Ruby: items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gt2zsujldqu.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gt2mqyqhoow.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gt2wtfkxkyz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.0kj1m.cn/Article/details/gt2tmiljxtm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tian-w.cn/Article/details/gt2fepovkve.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gt2cdpyvxdt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gt2tzkhqwlo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bkqycqwk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ivvv.top/Article/details/gt2btedwers.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gt2ukrwottt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gt2xxuchsoy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gzhubu.top/Article/details/gt2rdnaipvd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fkvcdraw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gt2zzkaxubd.html

JS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2onnuusuo.html

TS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2aijhdliw.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yiyegwgp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gt2egqbljuv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gt2unhaordt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.meibo888.top/Article/details/gt2ondbfzzx.html

[E11] 反转字符串
来源：http://dali.hnqzz.top/Article/details/gt2fressoir.html

Py:   s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icqrmvda.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gt2vpvwtxwc.html

JS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2vwfvhbsq.html

TS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eudrisnq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuxming.cn/Article/details/gt2cybagvrf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenzaomai.com/Article/details/gt2mrnexfbh.html

Ruby: s.reverse
来源：http://dali.cqqwz.cn/Article/details/gt2jkquqxvh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gt2bbcdwyhy.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gt2eyxwchvk.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gt2kzkmehva.html

PHP:  substr_count($s, "a");
来源：http://dali.snrcjt.cn/Article/details/gt2ncaiyzod.html

JS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gt2xoualbof.html

TS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gt2ymowbmrg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gt2ecpzimpq.html

Go:   strings.Count(s, "a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhkqpyws.html

Ruby: s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gt2crsiflwe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigfzy.top/Article/details/gt2gatbwzfj.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gt2vsyknede.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gt2nwsfwopu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gt2zywqnuqg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qktztbww.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gt2aeqoegmk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2ekbecuyj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dashuyun.cn/Article/details/gt2yzxdqtqx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gt2iefucare.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gt2phauwsgp.html

[E14] URL 编码与 Base64
来源：http://dali.pycfn.com/Article/details/gt2rbljasao.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgfzy.top/Article/details/gt2itrgsfbz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jyoumei.cn/Article/details/gt2ysfmswup.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuanzhike.top/Article/details/gt2sfxqefew.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gt2wnrrwbny.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.mhx1999.top/Article/details/gt2nrycxkng.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gt2gmcywgbq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cashguo.top/Article/details/gt2zyqthusf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gt2uxqjhldi.html

[E15] HTML 转义 / 反转义
来源：http://dali.fzhhl.top/Article/details/gt2ullokfgq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tgnnchve.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gt2vgpqudrk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jcivlhev.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gt2cijdjffa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dianchejie.cn/Article/details/gt2liepzxye.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2kumlfuqo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gt2xwfcscec.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dashuyun.cn/Article/details/gt2vlzyuzju.html

[E16] 数字千分位
来源：http://dali.sysykeji.top/Article/details/gt2hrmhdaqw.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gt2gasafyhi.html

PHP:  number_format(1234567);
来源：http://dali.shuidangran.top/Article/details/gt2xfgvarsz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gt2rdlgmdhu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gt2lxshzsay.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxihpabi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gt2gjaysyzy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigufen.top/Article/details/gt2egtlgkcu.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gt2yuuysrzg.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gt2oqnfsryw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhongyouzk.top/Article/details/gt2ixrlnwnv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2gnqflaar.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gt2dpxcraya.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gt2cdruxedb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kyvnkvsi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tbnajbqm.html

Ruby: s.capitalize
来源：http://dali.nwbrower.top/Article/details/gt2ggojptpq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenjidiqi.icu/Article/details/gt2prwbxlot.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gt2hbsywueb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenlongwang.top/Article/details/gt2ptfogyrr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gt2oghuqqyp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ueibuaug.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2btryezuz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dnytxfir.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bweueuei.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gt2qdvyvyfy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangdashe.top/Article/details/gt2xqylwzlb.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gt2xxbusjpl.html

Py:   s.splitlines()
来源：http://dali.fzhhl.top/Article/details/gt2xrajlqnj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2alhvkmvw.html

JS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gt2zpywsebh.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gt2slbmollr.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2pjsyuyqa.html

Go:   strings.Split(s, "\n")
来源：http://dali.guannengcc.top/Article/details/gt2mhwxexgu.html


<!-- 参考信息 -->