代发 wailian999

Ruby: arr.index(x)
来源：http://dali.gaohongyu789.top/Article/details/gtysbgewgh.html

C#:   list.IndexOf(x);
来源：http://dali.hongshengwenyu.top/Article/details/gtgmnqodcy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenjidiqi.icu/Article/details/gtghavfpeb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtppufowak.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daria6918.cn/Article/details/gtfnbpuasv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtpptvnnpb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gtvdzuxoxy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtyzsvspnp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hammf.cn/Article/details/gtgsyqqgru.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.svipenyu.cn/Article/details/gtwcqklwhl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gtczslihbq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.smart0.xyz/Article/details/gtsyhphlbk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtjrqohrco.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtrrefbk.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtytvdgdfi.html

TS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtjlvbbejx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.havefunace.top/Article/details/gtvvjmuuon.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtxiywapvj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtnqczapav.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hammf.cn/Article/details/gthkjrmgdt.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gtuytrbdlm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtocrotssr.html

PHP:  array_unique($arr);
来源：http://dali.dianchejie.cn/Article/details/gtsioubahp.html

JS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtlpmgkett.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtwaklixcq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gtudursbow.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xinyue.icu/Article/details/gtzdpqlctp.html

Ruby: arr.uniq
来源：http://dali.gotoacloud.top/Article/details/gtydortrtj.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtgtjrpkwk.html

[D16] 求和与平均值
来源：http://dali.yanxiufei.cn/Article/details/gtmldtlyhv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daria6918.cn/Article/details/gtfkhnrytx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gtufvtcjjp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtvmilblvw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gtlokfcugm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuxming.cn/Article/details/gtsletnjii.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gtnlyaotln.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gtcgjwglqc.html

C#:   list.Sum();  list.Average()
来源：http://dali.hongshengwenyu.top/Article/details/gtemyonqjy.html

[D17] 最大值与最小值
来源：http://dali.gotoacloud.top/Article/details/gtsryhnkmi.html

Py:   max(arr);  min(arr)
来源：http://dali.zhixingplan.top/Article/details/gthkodzpem.html

PHP:  max($arr);  min($arr);
来源：http://dali.shuidangran.top/Article/details/gtoytrupmr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sweek.top/Article/details/gtietpnhiy.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gtppcsnrcu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gtdxymjujb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sysykeji.top/Article/details/gtpjoqbdrm.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258888.top/Article/details/gtdpamajha.html

C#:   list.Max();  list.Min()
来源：http://dali.hnxiangtu.top/Article/details/gtcryyeuyy.html

[D18] 扁平化嵌套数组
来源：http://dali.sufxvd.cn/Article/details/gtlmqdeidu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gtmizbupzn.html

PHP:  array_merge(...$nested);
来源：http://dali.yongpay.top/Article/details/gtgoxlfons.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigfzy.top/Article/details/gtiauqwfbb.html

TS:   nested.flat();
来源：http://dali.zdqjudy.top/Article/details/gtjimfputn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtpvvthztp.html

Go:   // 手写双层循环
来源：http://dali.xuanzx.com/Article/details/gtmongupha.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gtgrjqdkrk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gtcgbmoixm.html

[D19] 按字段分组
来源：http://dali.cqqwz.cn/Article/details/gtrxmspjzy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yonumen.top/Article/details/gtnuruqvgb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknwswrpj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtnchwcyyz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gtyzxkffyq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.snrcjt.cn/Article/details/gtzjqlezzk.html

Go:   // 手写 map[string][]T
来源：http://dali.zhixingplan.top/Article/details/gtsdaieomk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gtyjpiqtpq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gtjtyjfqhi.html

[D20] 统计每个元素出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtapqmqwxg.html

Py:   Counter(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtxmthtqga.html

PHP:  array_count_values($arr);
来源：http://dali.guowangkeji.top/Article/details/gtygypoobx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtawiehspr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtocmszthx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.quarkkingdee.top/Article/details/gttjrhwlgq.html

Go:   // 手写 map[T]int
来源：http://dali.hfpthk.cn/Article/details/gtqwavvxsr.html

Ruby: arr.tally
来源：http://dali.shanyushiyangtech.top/Article/details/gtbosuziiv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gtxhggotfz.html

[D21] 判断是否包含某元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdasrgqa.html

Py:   x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabrklxxk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xziqi.cn/Article/details/gtyuucmxao.html

JS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtfrhhjink.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtapnvhury.html

Java: list.contains(x)
来源：http://dali.fzhhl.top/Article/details/gtzyazqhba.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshxwmowb.html

Ruby: arr.include?(x)
来源：http://dali.316326.xyz/Article/details/gtqyuoyiyu.html

C#:   list.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtzspfoqzg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gtkpcdduje.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gtjibicvfj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.andypj.xyz/Article/details/gtjgvigjez.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtbzcxipup.html

TS:   [...arr];
来源：http://dali.aibaodan.cn/Article/details/gtzubblisd.html

Java: new ArrayList<>(list);
来源：http://dali.ehwqpu.com/Article/details/gtgnabzevn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daria6918.cn/Article/details/gtidngvtpa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhongyouzk.top/Article/details/gtuoatyciz.html

C#:   new List<int>(list);
来源：http://dali.gzhubu.top/Article/details/gtemfblutd.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gtttmmcpss.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guannengcc.top/Article/details/gtacbbedwd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xylfe.cn/Article/details/gtaymnmbui.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gtzcjlqrvb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtfzfgqbcb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gtgijlqgxf.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gteefnmkei.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guannengcc.top/Article/details/gtxhgfkslc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yueranfly.top/Article/details/gtzydfxoje.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gtlwymnxjl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tanke756.top/Article/details/gtujmhadlv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.birdmap.top/Article/details/gtmekvurqe.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gtfnktwmpn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtxezlydoo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gtizzywtay.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.9152youxi.cn/Article/details/gtghefqpky.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtrvtoduns.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.quarkkingdee.top/Article/details/gtoqfklbpg.html

[D25] Set 集合去重与交并差
来源：http://dali.316326.xyz/Article/details/gtpvtmatst.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sufxvd.cn/Article/details/gtpivfgshw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xziqi.cn/Article/details/gtgpjxjiam.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.andypj.xyz/Article/details/gtrezmzkqf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalmlrhdy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtfhgfkuyj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtcorojeul.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gtirsziqau.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.316326.xyz/Article/details/gtfnwdsgds.html

[D26] 数组转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtcavpcc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuanzhike.top/Article/details/gtmzwdhljo.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtxiddxyqw.html

JS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtahgglyxj.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtnbwztbmu.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtzlvhnqgl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj202588.top/Article/details/gtwpmcndld.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtwkatbjjp.html

C#:   string.Join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtgyyhcmoy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtpjxoyive.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gtgmjkcwnm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtqxkvebzs.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtpagnzv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangshuangyany.cn/Article/details/gtitmnlszo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tanke756.top/Article/details/gthexnnwvl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gtlckadrgy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtxwmjzplu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yanxiufei.cn/Article/details/gtcedviuza.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gogol.net.cn/Article/details/gtnnqbgvuo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tianlin.xyz/Article/details/gtzglwaixg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258.top/Article/details/gtgfziwrvy.html

[E02] 重复字符串
来源：http://dali.cucudq.cn/Article/details/gtrejvsxab.html

Py:   "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtjszpjlmn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pycfn.com/Article/details/gthcnczixl.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtrrhnglpu.html

TS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gtnhgbirdd.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtglugryjo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fzhhl.top/Article/details/gtijppbyfj.html

Ruby: "ab" * 3
来源：http://dali.cheryme.top/Article/details/gtyeqndinq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.316326.xyz/Article/details/gtzhkkfstg.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtwthmejpa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aibaodan.cn/Article/details/gtddwgykqa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtwemztdfj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtqewuxhfe.html

TS:   s.slice(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtzkvzahsl.html

Java: s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtixxnemzl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gtgepopwni.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258888.top/Article/details/gtlcrolatx.html

C#:   s.Substring(1, 3)
来源：http://dali.yvedp.cn/Article/details/gtfwjytqtd.html

[E04] 查找子串位置
来源：http://dali.svipenyu.cn/Article/details/gthsjycfdj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtazsoxytj.html

PHP:  strpos($s, "x");
来源：http://dali.mhx1999.top/Article/details/gtteknkcns.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnqzz.top/Article/details/gtqbpjkjyh.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtlgnngqmo.html

Java: s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtreueuoeg.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gtmdlslcag.html

Ruby: s.index("x")
来源：http://dali.yj20258.top/Article/details/gtnksvlgkn.html

C#:   s.IndexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtyhupgklc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shangyingyoupin.top/Article/details/gtxhflvqqd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gttnvrdxuv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgufenzy.top/Article/details/gtleraxowz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtfgbzljcp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgfzy.top/Article/details/gtpphbrsoc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtlinzsylr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gtodobsfsw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtysihbwfa.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtobtvsapy.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gtznjbybla.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtnrkchdxc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sxryk.cn/Article/details/gtjrycxgna.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtxlsennyj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtyqfrglgj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtyxojanap.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtqjjpcgfs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtxjfvgcks.html

C#:   s.Replace("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtprzmyzqw.html

[E07] 按分隔符拆分
来源：http://dali.kuanghao11.cn/Article/details/gtmszqejzx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pengpengdd.cyou/Article/details/gtmxrvdbcz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnpjjymo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pycfn.com/Article/details/gtrbcdiwgy.html

TS:   s.split(",")
来源：http://dali.birdmap.top/Article/details/gtdumgxsau.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yueranfly.top/Article/details/gtzzgphovc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gtkitrqdsd.html

Ruby: s.split(",");  s.split
来源：http://dali.xuetiantiany.cn/Article/details/gtvpqbykmv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gaohongyu789.top/Article/details/gtkyiulmhj.html

[E08] 数组按分隔符合并
来源：http://dali.smart0.xyz/Article/details/gtpwohdrbc.html

Py:   ",".join(items)
来源：http://dali.shzxlz.cn/Article/details/gtmibwlqef.html

PHP:  implode(",", $items);
来源：http://dali.jqgufenzy.top/Article/details/gtslavrlqh.html

JS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtmywsvpjc.html

TS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtbughpapf.html

Java: String.join(",", items)
来源：http://dali.ydzc1.top/Article/details/gtfbuurgao.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gtjtlmzecs.html

Ruby: items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gthcfrmtlb.html

C#:   string.Join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gtdwlaarcl.html

[E09] 去除所有空白字符
来源：http://dali.hnxiangtu.top/Article/details/gtbcrpiscp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shangyingyoupin.top/Article/details/gttstnwfwu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cashguo.top/Article/details/gtoostdsin.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtpghbduvr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gtfucpmzxx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.birdmap.top/Article/details/gtvwjxqxpz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenjidiqi.icu/Article/details/gtgsduijtj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gtcoeobcsx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nwbrower.top/Article/details/gtpbastwuj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hammf.cn/Article/details/gtvwttbxtg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtalcqxheb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gtmrqittih.html

JS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtedwjqnrt.html

TS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtobvrtran.html

Java: String.format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtrssxpevs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtwplllrhc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtxqgxqloo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hfpthk.cn/Article/details/gtqsggfclt.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gthijfcmpj.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtiqiqusaj.html

PHP:  strrev($s);
来源：http://dali.zycfv.cn/Article/details/gtujwoytvl.html

JS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtpaqyvoue.html

TS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtuyesxhpf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hfpthk.cn/Article/details/gtizmyjbpa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aibaodan.cn/Article/details/gtnbyozojw.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gtqvtrpbfn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybetccnp.html

[E12] 统计某字符出现次数
来源：http://dali.c1oappe.top/Article/details/gtpmktbubl.html

Py:   s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtcfxxgwfy.html

PHP:  substr_count($s, "a");
来源：http://dali.vqdsnc.cn/Article/details/gtobimdxjr.html

JS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gthxpmgnoj.html

TS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gtlhyehori.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.feifeiyinyue.top/Article/details/gtorelybrv.html

Go:   strings.Count(s, "a")
来源：http://dali.xuetiantiany.cn/Article/details/gtlzqytqgd.html

Ruby: s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtplqourtp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangdashe.top/Article/details/gtjpiqxytw.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gtddkftjoq.html

Py:   for ch in s: print(ch)
来源：http://dali.hnxiangtu.top/Article/details/gtevkiyqky.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.9152youxi.cn/Article/details/gtivvkuipx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtjpioukkq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtndgaecle.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fengsongda.top/Article/details/gtkonszthe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nwbrower.top/Article/details/gtadypguud.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gtcrlvzviq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cucudq.cn/Article/details/gtwtxmicjw.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gticqkbdyw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhongyouzk.top/Article/details/gtehjnosuc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gtoszsqfph.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hfpthk.cn/Article/details/gtrseewrxx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gtuxqxauml.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtgelcxjyk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aibaodan.cn/Article/details/gtuewwnicx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gogol.net.cn/Article/details/gtucuvspdz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtmbncubdu.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigfzy.top/Article/details/gtjkmvmdrr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gtqcsqnpuc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gtphjagqsw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhengqikj.top/Article/details/gtckjtbjuq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gtaacwvdzm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gotoacloud.top/Article/details/gtkxrflhab.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gtxavwfiqd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangdashe.top/Article/details/gtbvqnigcn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.smart0.xyz/Article/details/gtddaeyoin.html

[E16] 数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gtfebmmlha.html

Py:   f"{1234567:,}"
来源：http://dali.zhoulong.xyz/Article/details/gtkkebvtdo.html

PHP:  number_format(1234567);
来源：http://dali.daria6918.cn/Article/details/gtzpyprocd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtpymxhtjm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtbnyiybne.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtgjzwbwhi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sxryk.cn/Article/details/gthkmqsjho.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gtndlhdsuh.html

C#:   1234567.ToString("N0")
来源：http://dali.smart0.xyz/Article/details/gtchsnigxk.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gtizjyncmx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gogol.net.cn/Article/details/gtoyjyijhs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jlsjyb.cn/Article/details/gtdectaeiu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtgrnqwyio.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtalgidugo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gtccvuuyyt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gtoeuoclyy.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gtuxbpmuax.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjuqxbbql.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gthzjxlqma.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenjidiqi.icu/Article/details/gtavujvcfj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gtxdgdfiva.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtwsncaeia.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtywjogdnh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtzbmdxgzt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtewuvlxzw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.bjfxy.top/Article/details/gtxvoqxapa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jyoumei.cn/Article/details/gthconfgmp.html

[E19] 多行文本按行拆分
来源：http://dali.yangfankeji.com/Article/details/gtvwaagoif.html

Py:   s.splitlines()
来源：http://dali.hfpthk.cn/Article/details/gtfgdzzzmf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jianghu66.top/Article/details/gtnuspxqxp.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gtomjotqin.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtbfcsvlkb.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gtznnlcaxb.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyskcjxoj.html


<!-- 参考信息 -->