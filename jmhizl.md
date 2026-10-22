代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2kqotdkpc.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gt2lrkmizrp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.andypj.xyz/Article/details/gt2quyaouex.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2wxmmxjqp.html

[D15] 去重
来源：http://dali.yuxming.cn/Article/details/gt2rrqnawwl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gt2ripimgyj.html

PHP:  array_unique($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2hpcdiqty.html

JS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gt2zfiinmsf.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2dpwpzlse.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.vqdsnc.cn/Article/details/gt2kjooozvr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tian-w.cn/Article/details/gt2jftjpmum.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gt2bsxvbkor.html

C#:   list.Distinct().ToList()
来源：http://dali.daria6918.cn/Article/details/gt2fvpnkmbo.html

[D16] 求和与平均值
来源：http://dali.hywenlv.cn/Article/details/gt2skjxlbdn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gt2cvtsddhp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2ctrovjcp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gt2idkxvzwt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gt2etwptsor.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yanxiufei.cn/Article/details/gt2tjcfrftb.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gt2szzandrg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fzhhl.top/Article/details/gt2hjigcfra.html

C#:   list.Sum();  list.Average()
来源：http://dali.yongpay.top/Article/details/gt2bjdihxgz.html

[D17] 最大值与最小值
来源：http://dali.gzhubu.top/Article/details/gt2akqjegbe.html

Py:   max(arr);  min(arr)
来源：http://dali.andypj.xyz/Article/details/gt2rjfuyogv.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2vtizjyfx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2qcvyttdg.html

TS:   Math.max(...arr);
来源：http://dali.aibaodan.cn/Article/details/gt2clnrskpq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2atziylih.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sysykeji.top/Article/details/gt2btsbedxc.html

Ruby: arr.max;  arr.min
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dzwfqhva.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gt2yhwwceap.html

[D18] 扁平化嵌套数组
来源：http://dali.zdqjudy.top/Article/details/gt2skbhrton.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tian-w.cn/Article/details/gt2bvtvpjiq.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvmwpehm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.vqdsnc.cn/Article/details/gt2dedmfuwm.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwxrvsai.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2buujlrsp.html

Go:   // 手写双层循环
来源：http://dali.haohaochexian.top/Article/details/gt2cvaezarj.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gt2ugkjhhao.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2eiogsnsf.html

[D19] 按字段分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtclmaff.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ybcxt.top/Article/details/gt2gdhbzuke.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sweek.top/Article/details/gt2nclyzjzq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gt2umyrrqyq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gt2rlllutmg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tianlin.xyz/Article/details/gt2jmiyvsqv.html

Go:   // 手写 map[string][]T
来源：http://dali.xziqi.cn/Article/details/gt2hoxjqsib.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258.top/Article/details/gt2zqtucecs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gt2cqzviort.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gt2fmgfnjwz.html

Py:   Counter(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2ndyxwvov.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gt2akxnango.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gt2vgwsweke.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gt2mmwiafhd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxnpifrs.html

Go:   // 手写 map[T]int
来源：http://dali.ppjwa.cn/Article/details/gt2fvcgmcai.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmmxxno.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuanzx.com/Article/details/gt2vpuokwnt.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2odwixljy.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gt2cqnusnzn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpziqeff.html

JS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2umgpllhz.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzciwnky.html

Java: list.contains(x)
来源：http://dali.yongpay.top/Article/details/gt2rqxumshr.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wktslzla.html

Ruby: arr.include?(x)
来源：http://dali.chenlongwang.top/Article/details/gt2wvimoewj.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2mvugtwvz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.svipenyu.cn/Article/details/gt2qajplocy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2igzvdifa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.birdmap.top/Article/details/gt2mvjozvof.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lgtwlhsg.html

TS:   [...arr];
来源：http://dali.bjfxy.top/Article/details/gt2gavpcwam.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258.top/Article/details/gt2buxiuwrk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxuanxn.top/Article/details/gt2ozqyxess.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpkjfntq.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gt2dxvgnshe.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gt2ijaqeevc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2pwlivteg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gt2xkdetxeo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2veyfthnt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gt2qdfskidc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hywenlv.cn/Article/details/gt2crhohxdu.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gt2mcgcjbmp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.svipenyu.cn/Article/details/gt2tgbkqazu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gt2varnzeek.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gt2tbryfadm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gotoacloud.top/Article/details/gt2pnkequab.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gt2npmtoyqf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfhnrnby.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pbscpwig.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gt2apuokoqi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gt2dlsalpfh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gylrkwyn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gt2agdcusph.html

[D25] Set 集合去重与交并差
来源：http://dali.ppjwa.cn/Article/details/gt2pgqshzxk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.9152youxi.cn/Article/details/gt2nporqtju.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.meibo888.top/Article/details/gt2weukaguv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cashguo.top/Article/details/gt2zobhqyqn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gt2fohwyjjo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.andypj.xyz/Article/details/gt2huklcddi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hiqmwoxe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gt2tiwfmyhe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gt2vocrdrqm.html

[D26] 数组转字符串
来源：http://dali.ivvv.top/Article/details/gt2vtulhsbq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gt2wglstkpd.html

PHP:  implode(", ", $arr);
来源：http://dali.cucudq.cn/Article/details/gt2rdhthikb.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2fkbsvcdq.html

TS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gt2ibojdbgj.html

Java: String.join(", ", list)
来源：http://dali.cheryme.top/Article/details/gt2tgmnhetp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fengsongda.top/Article/details/gt2uidqfhya.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gt2esywpbku.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gt2ocmfkaii.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2pztcnfrl.html

E. 字符串处理
来源：http://dali.dashuyun.cn/Article/details/gt2mttrjzzz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2tdjohekd.html

[E01] 拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2ackaoxzd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gt2zpkybrzx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ydzc1.top/Article/details/gt2onlmzkqs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gt2khdptvdg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gt2owoejtjj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuxming.cn/Article/details/gt2wzuskuud.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2dyhqxicq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gt2loeyrddy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2zklddioq.html

[E02] 重复字符串
来源：http://dali.tian-w.cn/Article/details/gt2nyubyqqw.html

Py:   "ab" * 3
来源：http://dali.yj202588.top/Article/details/gt2qmbpukvn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifsbhqow.html

JS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gt2fvhnphty.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gt2rlqnewup.html

Java: "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxbhdpnb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gt2azpnaana.html

Ruby: "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gt2diarrbhp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shuidangran.top/Article/details/gt2gvwrqxvs.html

[E03] 截取子串
来源：http://dali.daxiang520.top/Article/details/gt2jccjpoaa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuanzx.com/Article/details/gt2fbdbhoag.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2rnrormjc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2cikpecvp.html

TS:   s.slice(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2emulwdpj.html

Java: s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gt2kxanlxqf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aibaodan.cn/Article/details/gt2iwgzvfmk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yongpay.top/Article/details/gt2vlhnyzaw.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gt2xfdbmjlx.html

[E04] 查找子串位置
来源：http://dali.svipenyu.cn/Article/details/gt2ukwwtkks.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gt2nvjoigbf.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gt2jcsundpp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgfzy.top/Article/details/gt2dplygtcx.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gt2clwnjhvu.html

Java: s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2wjwaatgu.html

Go:   strings.Index(s, "x")
来源：http://dali.zhongyouzk.top/Article/details/gt2hxjxcbig.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2hctkeiug.html

C#:   s.IndexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gt2wnuqgmot.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.mhx1999.top/Article/details/gt2mokdgmiv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gt2kaqjgxql.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gt2yrwszqqk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2jbpmhqzb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guannengcc.top/Article/details/gt2neipqiwi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gt2stowkeid.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tanke756.top/Article/details/gt2llnatmcc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pyhtnrsi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2oywyhjnl.html

[E06] 替换子串
来源：http://dali.dashuyun.cn/Article/details/gt2nalefcox.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2edsqhxlb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwyoocyk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2bvtdrtqo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2mimufoho.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2nlhiifol.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gt2mihcexyq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2hzxlbulj.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2mxtpvdmz.html

[E07] 按分隔符拆分
来源：http://dali.ydzc1.top/Article/details/gt2khxqkrih.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgufenzy.top/Article/details/gt2xabdrygn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2zojqjguu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sweek.top/Article/details/gt2tackrtua.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2leojjepg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.0kj1m.cn/Article/details/gt2mkxzaywy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ivvv.top/Article/details/gt2lysqsqsm.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gt2znwedesb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258888.top/Article/details/gt2vbcbjshc.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gt2jpooyuui.html

Py:   ",".join(items)
来源：http://dali.yuanzhike.top/Article/details/gt2snrwfqkx.html

PHP:  implode(",", $items);
来源：http://dali.quarkkingdee.top/Article/details/gt2vvpebpgy.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gt2lzneefpu.html

TS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2kvvsmifa.html

Java: String.join(",", items)
来源：http://dali.daria6918.cn/Article/details/gt2xgjytnoa.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gt2fqhqzikj.html

Ruby: items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yeubxchd.html

C#:   string.Join(",", items)
来源：http://dali.mhx1999.top/Article/details/gt2roybtogq.html

[E09] 去除所有空白字符
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdbrtlhq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gt2npvaztrn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.birdmap.top/Article/details/gt2fublqixf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gt2vchtwdrb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2ugplmlgo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hammf.cn/Article/details/gt2gwpcnbgh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gt2dauzncmn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.c1oappe.top/Article/details/gt2limdlidq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gt2ztgsycbe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hammf.cn/Article/details/gt2ampoogyk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2fgjgnsef.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gt2guuyfccu.html

JS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gt2nrjdhteb.html

TS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gt2vqqbkncq.html

Java: String.format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gt2zsfqxrln.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gt2rcqpqqpk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2yeylcmou.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xziqi.cn/Article/details/gt2hrkunisz.html

[E11] 反转字符串
来源：http://dali.wangdashe.top/Article/details/gt2nggvrzpz.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gt2spaeqnvu.html

PHP:  strrev($s);
来源：http://dali.yj20258888.top/Article/details/gt2wuoghhnu.html

JS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2cqtshrgg.html

TS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2vqnuezhu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangdashe.top/Article/details/gt2yvvkhzjv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gt2krpzkccs.html

Ruby: s.reverse
来源：http://dali.shuidangran.top/Article/details/gt2maklkjbe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gt2wthpuswh.html

[E12] 统计某字符出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bplewbsk.html

Py:   s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2wynzuwau.html

PHP:  substr_count($s, "a");
来源：http://dali.fzhhl.top/Article/details/gt2dkxwvfhp.html

JS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gt2dzwvxvhj.html

TS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gt2mszmfvzb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yanxiufei.cn/Article/details/gt2zleiewim.html

Go:   strings.Count(s, "a")
来源：http://dali.zhixingplan.top/Article/details/gt2zenngekj.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gt2wisqullf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj202588.top/Article/details/gt2vriblyte.html

[E13] 逐字符遍历
来源：http://dali.yuanzhike.top/Article/details/gt2xkvdutzr.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gt2iouvxtxb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gt2xcsebhnf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzzafoni.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smxylphi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2iwhhijtx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nwbrower.top/Article/details/gt2swyomxnv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hysaishi.cn/Article/details/gt2zitmckpg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2ohieanid.html

[E14] URL 编码与 Base64
来源：http://dali.smart0.xyz/Article/details/gt2syxnwirz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhoulong.xyz/Article/details/gt2rbqjkxvp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gt2pyybsyaf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnqzz.top/Article/details/gt2ehjpwqjw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2nnijalko.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2nzskavvh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gt2cdiiyzuz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dpoegoej.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zdqjudy.top/Article/details/gt2xkocczph.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewwcsfcs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gt2djrgemfy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.0kj1m.cn/Article/details/gt2hssjgulg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xzyngqmf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hfpthk.cn/Article/details/gt2eqouufhn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rsjcmbdk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cufatwcf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ehwqpu.com/Article/details/gt2xjyaqeks.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gt2uwwxdese.html

[E16] 数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxnzoqqn.html

Py:   f"{1234567:,}"
来源：http://dali.dianchejie.cn/Article/details/gt2mvoliwrt.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lqjzifcb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phjsprug.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gt2dogbtlme.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gt2ovvqtvta.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gt2npioxqgr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gt2wwgnnyrl.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gt2jstfyjht.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gt2dndoraxz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gt2aghroibe.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.birdmap.top/Article/details/gt2asfihuka.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gt2trpaoiwo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2rzzliljn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gt2azsumuww.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hammf.cn/Article/details/gt2iqvvxgmd.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gt2grwuhobo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gt2sogewwow.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gt2hraaftym.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpqumikp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dashuyun.cn/Article/details/gt2gfrpxoav.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gt2ohbkbtmi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imwtbprx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2prpppgum.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2kamsncyt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gt2cougygmc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.redwolf501.top/Article/details/gt2svgsktgy.html

[E19] 多行文本按行拆分
来源：http://dali.yongpay.top/Article/details/gt2ygmxiwvo.html

Py:   s.splitlines()
来源：http://dali.jinqigufen.top/Article/details/gt2sfgyjgyg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tanke756.top/Article/details/gt2ifzcrixs.html

JS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gt2fehxhkpo.html

TS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gt2acpgwolf.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gt2tcafnkds.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2ndditima.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gt2kxmjxgbo.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gt2bmplxxgf.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gt2gtrqwmjh.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gt2gdzxnfnk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gt2tbuphvmi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsmzmnfm.html

TS:   if (s === "") {}
来源：http://dali.zdqjudy.top/Article/details/gt2oeyadgsz.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gt2zglatbrn.html

Go:   if s == "" {}
来源：http://dali.yj20258.top/Article/details/gt2lfwqvgis.html

Ruby: if s.empty?
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbsfkacf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2vigveepl.html

[E21] 超长截断加省略号
来源：http://dali.sweek.top/Article/details/gt2lgselrjs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gt2eckwrqlj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2mihpaiev.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2mvugnejq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2xrikeywv.html


<!-- 参考信息 -->