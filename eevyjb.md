代发 wailian999

[D11] 反转数组
来源：http://dali.birdmap.top/Article/details/gtckdsfcvl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gtlyyxnxdr.html

PHP:  array_reverse($arr);
来源：http://dali.ivvv.top/Article/details/gtyfjgklid.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.mhx1999.top/Article/details/gtymqislfp.html

TS:   [...arr].reverse();
来源：http://dali.xylfe.cn/Article/details/gtxvegnwfo.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gtfvahnswn.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gtndiislen.html

Ruby: arr.reverse
来源：http://dali.pycfn.com/Article/details/gtrimqmcmb.html

C#:   list.Reverse();
来源：http://dali.zhixingplan.top/Article/details/gtgdelqkgz.html

[D12] 查找元素下标
来源：http://dali.hnqzz.top/Article/details/gtfipyycij.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gtuvplmlsl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.meibo888.top/Article/details/gtlrvwpsma.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gtwtafusvu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gttwoyvgve.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xziqi.cn/Article/details/gtmlgwaudg.html

Go:   slices.Index(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtsbjpzigs.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdknmnjjc.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gtqjpzuprr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj202588.top/Article/details/gtjufzmvxd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gtkhcpntbg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daxiang520.top/Article/details/gtawjnekaa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtuotxartk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtdoeyadjh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtmehexbug.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hywenlv.cn/Article/details/gtffiotobw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzipvrws.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hammf.cn/Article/details/gtqyuprwtc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhiwuduotai.top/Article/details/gttuqdookd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtitpqzwib.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gttmsxmlos.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtdxbtlfep.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtndfgculx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gtbppbqcdw.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtyxfuseup.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtrfngcfww.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shuidangran.top/Article/details/gtbrbdxmqo.html

[D15] 去重
来源：http://dali.yongpay.top/Article/details/gtdfzqmsns.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gtlcafnazw.html

PHP:  array_unique($arr);
来源：http://dali.havefunace.top/Article/details/gtmqosxbnn.html

JS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtnsmkkqjk.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtrbrcnnli.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gtisqqgdpu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gtqhapxbxl.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gtaximeyar.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258888.top/Article/details/gtvgfxprsl.html

[D16] 求和与平均值
来源：http://dali.yonumen.top/Article/details/gttpdgejcl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gttznvnkkx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sxryk.cn/Article/details/gtoynffljr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtpcjcpjsl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtygzhgwoo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gtcnwlhiff.html

Go:   // 手写循环累加
来源：http://dali.hnxiangtu.top/Article/details/gtyugruerf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gtzyqecquz.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gtqkkkhfbd.html

[D17] 最大值与最小值
来源：http://dali.sufxvd.cn/Article/details/gtmsmdkkrf.html

Py:   max(arr);  min(arr)
来源：http://dali.ydzc1.top/Article/details/gtufvtowjq.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gttmjfmrds.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtoakpadts.html

TS:   Math.max(...arr);
来源：http://dali.dashuyun.cn/Article/details/gtfnodmmym.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdompxvlf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gtjncymsxd.html

Ruby: arr.max;  arr.min
来源：http://dali.tanke756.top/Article/details/gtdaozsdlx.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gtbbxtzeci.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gtecouucqe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gtkjxghpsd.html

PHP:  array_merge(...$nested);
来源：http://dali.daria6918.cn/Article/details/gtralqmaiy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gtykephutw.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gtjzreogza.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yonumen.top/Article/details/gtrirzrdtn.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gtcamvdqxm.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gtoxjwoiwa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtevzgwbax.html

[D19] 按字段分组
来源：http://dali.aibaodan.cn/Article/details/gtrkhdvhsx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gtukonlhpv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jianghu66.top/Article/details/gtnkfideah.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gtxtvwqmqf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gtcgjjjado.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yongpay.top/Article/details/gtvtozvsld.html

Go:   // 手写 map[string][]T
来源：http://dali.chenjidiqi.icu/Article/details/gtcmxcocwy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.vqdsnc.cn/Article/details/gtpkogelod.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gtcqnpwyje.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gthprlwved.html

Py:   Counter(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnlzkhkr.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gtairbdpga.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gtzyaorxse.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gthrirtrqf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigufen.top/Article/details/gtybojpjze.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gtfioqlsso.html

Ruby: arr.tally
来源：http://dali.zdqjudy.top/Article/details/gtqejijpxs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gtzfsnrcig.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gtskcqddak.html

Py:   x in arr
来源：http://dali.pycfn.com/Article/details/gtbnvjcjkl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gtvoouvlip.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtowyuiluu.html

TS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtzoebsona.html

Java: list.contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtmvttczut.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtnkohftng.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gtkyismugq.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxaisevpu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gtiqypmqru.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhengqikj.top/Article/details/gtwohwnrei.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shzxlz.cn/Article/details/gttwcrvnqb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gtiaphpwas.html

TS:   [...arr];
来源：http://dali.hywenlv.cn/Article/details/gtwvapemxs.html

Java: new ArrayList<>(list);
来源：http://dali.hywenlv.cn/Article/details/gtmigtuyrl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tianlin.xyz/Article/details/gtzxkqncdm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ybcxt.top/Article/details/gtzgwlzyqj.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gtaanugpxm.html

[D23] reduce 累积计算
来源：http://dali.xziqi.cn/Article/details/gtlexookik.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtihbtllxg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ivvv.top/Article/details/gtbrormhbx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtydhrvlwp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gtbcybjvjs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gtfipeyyvh.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtshihddwa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xinyue.icu/Article/details/gtgsnrjscc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtpfejmvxh.html

[D24] 字典 / Map 基本操作
来源：http://dali.dashuyun.cn/Article/details/gtagpgklsi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gtsmlipitj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gtpckdseiv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gtpjorqwvk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtxlbcjduh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zdqjudy.top/Article/details/gttxxckviv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jiagoushi.top/Article/details/gtabnnszpg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gtfkhznkgz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hongshengwenyu.top/Article/details/gtcjbfpnpy.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gtoqzbvjda.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.0kj1m.cn/Article/details/gtlhdegcnh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daxiang520.top/Article/details/gtdyolzprf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtpuuicgix.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gtzqfnpfep.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhengqikj.top/Article/details/gtlyfwvxfl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cheryme.top/Article/details/gtgmzmftvr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gtpovrkqab.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtdtdafcgz.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gtaipfjfyk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nwbrower.top/Article/details/gthlviqglp.html

PHP:  implode(", ", $arr);
来源：http://dali.dashuyun.cn/Article/details/gtharzjmhx.html

JS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtalgflcle.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtjbxsyvte.html

Java: String.join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtcdpeboty.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgfzy.top/Article/details/gtamjivtxt.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtgzhngvox.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gttlrcgyom.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtycanwjja.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gtyjhnrofo.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqctsine.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtatwimamd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gtmnpcenuf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tanke756.top/Article/details/gtlbtrvbvq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtbfedohxl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtwqptryou.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangshuangyany.cn/Article/details/gtvcvfpnvt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gtznkawlnd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gtajfmsmno.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtbadqodrc.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gtzwvlrnxq.html

Py:   "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gtkgahkwms.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhengqikj.top/Article/details/gtrlgaiusu.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtbhlxzpqo.html

TS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtpucjpfnf.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gteimjlszm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.kuanghao11.cn/Article/details/gtbnjqrwsi.html

Ruby: "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtsfceezcu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gtwxqnmktp.html

[E03] 截取子串
来源：http://dali.tanke756.top/Article/details/gtirmyxxrj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cheryme.top/Article/details/gtsrnyaryc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtmysmnblf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtwignkccx.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtxfpqgqrz.html

Java: s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gtzvmqlnrq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yongpay.top/Article/details/gtzqzidujl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sufxvd.cn/Article/details/gtkplexvkk.html

C#:   s.Substring(1, 3)
来源：http://dali.gotoacloud.top/Article/details/gttdmkfxjk.html

[E04] 查找子串位置
来源：http://dali.birdmap.top/Article/details/gtlzjnlcvn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtascnvuuq.html

PHP:  strpos($s, "x");
来源：http://dali.pycfn.com/Article/details/gtnkijxcep.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nwbrower.top/Article/details/gtqlpkiyrg.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtalntndpg.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtxtjlstkx.html

Go:   strings.Index(s, "x")
来源：http://dali.zhoulong.xyz/Article/details/gtglhdcect.html

Ruby: s.index("x")
来源：http://dali.andypj.xyz/Article/details/gtxhlioyhy.html

C#:   s.IndexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtteazncsr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnqzz.top/Article/details/gtbtsjnvqo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtcptarpac.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.havefunace.top/Article/details/gtgvwebswj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtjoxaiteo.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ybcxt.top/Article/details/gtkwgpnprz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gteifvhxhy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hysaishi.cn/Article/details/gtulpjvmpn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gtdaihwxpv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtnsxndbdc.html

[E06] 替换子串
来源：http://dali.shzxlz.cn/Article/details/gtgtsukndx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gtkyhfwxif.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pycfn.com/Article/details/gtzihfohtz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtrbjdtwdo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gthwjkpsos.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtlcxzfoss.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sweek.top/Article/details/gtewrwnfwq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtihunmwic.html

C#:   s.Replace("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtycpbatwe.html

[E07] 按分隔符拆分
来源：http://dali.havefunace.top/Article/details/gtsgapcpmq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gtuztfeovk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtfawdstjo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxinkj.top/Article/details/gtwzwjuect.html

TS:   s.split(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtfnfmrovm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fengsongda.top/Article/details/gtqdtxflsz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gtmgwatsxg.html

Ruby: s.split(",");  s.split
来源：http://dali.guannengcc.top/Article/details/gtpfltdolt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gttssifqqd.html

[E08] 数组按分隔符合并
来源：http://dali.xuanzx.com/Article/details/gtzfbegtqo.html

Py:   ",".join(items)
来源：http://dali.jqgufenzy.top/Article/details/gtyghvulmp.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gtsraoqkie.html

JS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gthjkefvjd.html

TS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvhcvwhw.html

Java: String.join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtnumymvsh.html

Go:   strings.Join(items, ",")
来源：http://dali.tanke756.top/Article/details/gtuqzktjxh.html

Ruby: items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtkjjuptpa.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gthszqvgnj.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gtedbqrqrr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sxryk.cn/Article/details/gtwubscorx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gtbhnpkjda.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtwdajadgf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gtzgwlzivl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gtuhrkqifg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gtkdnvojbc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhongyouzk.top/Article/details/gtssfwwblx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtqrribqcg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.snrcjt.cn/Article/details/gtjtznczhd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtbkvbyzvl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cqqwz.cn/Article/details/gtflbhrwzm.html

JS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfeawbjl.html

TS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtbbfiiakj.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtzfhjitqk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtenkouspo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsehpawe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.snrcjt.cn/Article/details/gtxccxivkb.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gtthnuknxx.html

Py:   s[::-1]
来源：http://dali.ivvv.top/Article/details/gttqlqbpgh.html

PHP:  strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gttvtokshp.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtudhzlqcr.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtqlixgtiu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gttzwbqren.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.svipenyu.cn/Article/details/gtwergokux.html

Ruby: s.reverse
来源：http://dali.jianghu66.top/Article/details/gtexmqjgog.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtsabcrmvj.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gttjcalbvo.html

Py:   s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtxlrqwxew.html

PHP:  substr_count($s, "a");
来源：http://dali.chenjidiqi.icu/Article/details/gtelrqhfeu.html

JS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gtqpxbmffy.html

TS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtcqokkfwq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenlongwang.top/Article/details/gtpvdcrynr.html

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gtrypjdrhc.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtztoxfyde.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gtcxrnbfav.html

[E13] 逐字符遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtblglnhdw.html

Py:   for ch in s: print(ch)
来源：http://dali.hysaishi.cn/Article/details/gtoskgnqrj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfanvvbp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlczkcpma.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gteislhchq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gtmrmpelnf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtjdbvyexy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangshuangyany.cn/Article/details/gtiartayxt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkjjdmgcq.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gtuvjpzghh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.havefunace.top/Article/details/gtpqurrgrb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tianlin.xyz/Article/details/gtvstamnmt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zdqjudy.top/Article/details/gtdlxudhtj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gtswdgkwsl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtheyuocxj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gtxwptgpss.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cucudq.cn/Article/details/gtfrjcxaud.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuxming.cn/Article/details/gturycpzuy.html

[E15] HTML 转义 / 反转义
来源：http://dali.shzxlz.cn/Article/details/gtgnaboxyn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sweek.top/Article/details/gtunrayxrb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gtlfurdqyo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.vqdsnc.cn/Article/details/gtcpsbrlkw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gtitvtnjkv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gotoacloud.top/Article/details/gtkqtzrytp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmimusfqi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gtzapriawt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gtubntzpum.html

[E16] 数字千分位
来源：http://dali.sysykeji.top/Article/details/gtmmlndumw.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gtearrmuyq.html

PHP:  number_format(1234567);
来源：http://dali.zhiwuduotai.top/Article/details/gtcqlmbuky.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtpwweguao.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gtpgkmlfup.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gtinxxvejc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gtidsqoabb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgufenzy.top/Article/details/gtpukeaenc.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gtzolnxjws.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gtantoxoxo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hongshengwenyu.top/Article/details/gtsexoewcf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gtpluistoa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gthcvzgzth.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtdtbdilel.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtibqgfzgh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtbjxcearx.html

Ruby: s.capitalize
来源：http://dali.ydzc1.top/Article/details/gthwzvdtcz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gtuprbduql.html


<!-- 参考信息 -->