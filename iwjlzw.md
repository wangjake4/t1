代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2evllcdlh.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gt2cdrbyuid.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj20258888.top/Article/details/gt2fcpihqun.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2bpesgjka.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2xgxyzsij.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2mduwotbf.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gt2ifpbypdp.html

JS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gt2dyoykhej.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2gdbclufb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gt2hjvuovqn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daxiang520.top/Article/details/gt2jongvpxt.html

Ruby: arr.uniq
来源：http://dali.zycfv.cn/Article/details/gt2dhtlzylj.html

C#:   list.Distinct().ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2ruwusfkh.html

[D16] 求和与平均值
来源：http://dali.jyoumei.cn/Article/details/gt2xjzqekvd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2paeijrkj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2xlhvmcat.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2piubmyxy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gt2bkyaqjur.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gt2bjyqhmum.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkupbqha.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gt2yswsqeos.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gt2ypmktirb.html

[D17] 最大值与最小值
来源：http://dali.yongpay.top/Article/details/gt2fyloaape.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2irbjathk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2qfzfceub.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gt2apffqdcn.html

TS:   Math.max(...arr);
来源：http://dali.yvedp.cn/Article/details/gt2aabirvhq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gt2ezhnobvh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2pqpwdaop.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gt2zsanrlwl.html

C#:   list.Max();  list.Min()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bksgqcak.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gt2nvsxflwf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.andypj.xyz/Article/details/gt2dredrgri.html

PHP:  array_merge(...$nested);
来源：http://dali.xuanzx.com/Article/details/gt2ffghrmwo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yongpay.top/Article/details/gt2glqxyfog.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gt2faiidjwc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2tzildnxt.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gt2cqjpfgzn.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gt2bfhzjhjq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gt2pbkmparc.html

[D19] 按字段分组
来源：http://dali.mhx1999.top/Article/details/gt2mkwmxnnq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ppjwa.cn/Article/details/gt2fczqdaqm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gzhubu.top/Article/details/gt2mgvphptg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenjidiqi.icu/Article/details/gt2xcbqwklw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenjidiqi.icu/Article/details/gt2etxiqife.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gt2omcefcdv.html

Go:   // 手写 map[string][]T
来源：http://dali.cqqwz.cn/Article/details/gt2xxrmuplk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2owkclrvq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gt2tbmkjehc.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gt2hynprdpj.html

Py:   Counter(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2jyyvqjkm.html

PHP:  array_count_values($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2isviomng.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gt2zltmpqfu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gt2lvdyzymt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gt2jwlqfdkh.html

Go:   // 手写 map[T]int
来源：http://dali.jqgfzy.top/Article/details/gt2uibmykji.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnrsussk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuanzx.com/Article/details/gt2xpeqpzyh.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dklbytbc.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gt2cacuxwxv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gotoacloud.top/Article/details/gt2ojdxhdix.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dptjigeq.html

TS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yudifzzi.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hygnohga.html

Go:   slices.Contains(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2soxxsluj.html

Ruby: arr.include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cgdfixoj.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2cmpimoxq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cheryme.top/Article/details/gt2ylvbwtgg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xinyue.icu/Article/details/gt2oftvpgeg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cashguo.top/Article/details/gt2ivbbzjfi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2tpcwjfag.html

TS:   [...arr];
来源：http://dali.tianlin.xyz/Article/details/gt2szrmzmeu.html

Java: new ArrayList<>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwiwlvqk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gt2lzndpmdm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gt2uxymsdin.html

C#:   new List<int>(list);
来源：http://dali.yangfankeji.com/Article/details/gt2ylgwkkyd.html

[D23] reduce 累积计算
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yfawyxgh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2ydnnqjsv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewfstnzh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2yqjfsczl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jympexst.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gt2oikeagkl.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gt2quwzbvlk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhengqikj.top/Article/details/gt2lhzhbotz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ydzc1.top/Article/details/gt2wqbjkrwp.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gt2elemmdne.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.9152youxi.cn/Article/details/gt2wergcrgh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bptvyjzw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yonumen.top/Article/details/gt2rapkfgfq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2rnjiqfev.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnqzz.top/Article/details/gt2sovjfpjf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aibaodan.cn/Article/details/gt2icjnpysv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guannengcc.top/Article/details/gt2xquxwenp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpjozenq.html

[D25] Set 集合去重与交并差
来源：http://dali.pycfn.com/Article/details/gt2wivnxyor.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aibaodan.cn/Article/details/gt2gehkcddq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daxiang520.top/Article/details/gt2kghzcmhk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tianlin.xyz/Article/details/gt2fgffwehz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rabwactb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuanzx.com/Article/details/gt2uvcycesc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gt2lhcthujc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gt2kqjznlmw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gt2wzsdffrt.html

[D26] 数组转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2wggqjkxw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2zrcinrzu.html

PHP:  implode(", ", $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2kyyezbli.html

JS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fqkpmjab.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2vdjryayu.html

Java: String.join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2muetglna.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2mcmzcrto.html

Ruby: arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gt2hylzpwln.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2cixetyqq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2kyeohlqx.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gt2yywexeks.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xriewdpa.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjwcmcbs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gt2phsybnbu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tian-w.cn/Article/details/gt2vjyvcdch.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2oecbpitm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gt2oraybllf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.andypj.xyz/Article/details/gt2qivzeysg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cpcvdqrb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhixingplan.top/Article/details/gt2nfrsggfe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xttsfyxx.html

[E02] 重复字符串
来源：http://dali.yangfankeji.com/Article/details/gt2vosglykl.html

Py:   "ab" * 3
来源：http://dali.yongpay.top/Article/details/gt2rwkanrfe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gt2sdgapsjg.html

JS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jghpnmpf.html

TS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gt2ldbgghqd.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2osnwcqlu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gt2beflzomh.html

Ruby: "ab" * 3
来源：http://dali.cheryme.top/Article/details/gt2vokxwvpg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvnjfddl.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gt2pqzyfvyp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tian-w.cn/Article/details/gt2xyovgkwx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2pvceyjyy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2lqnmcqaq.html

TS:   s.slice(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvvyavqb.html

Java: s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fdikhocl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gt2sfetjrqc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xylfe.cn/Article/details/gt2rcnwbhsn.html

C#:   s.Substring(1, 3)
来源：http://dali.dashuyun.cn/Article/details/gt2gmwcpqxl.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gt2kczbvhqd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gt2iytzoffn.html

PHP:  strpos($s, "x");
来源：http://dali.jiagoushi.top/Article/details/gt2ledwylbf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.havefunace.top/Article/details/gt2axgykcfp.html

TS:   s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gt2hkkwixir.html

Java: s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gdyupwfl.html

Go:   strings.Index(s, "x")
来源：http://dali.snrcjt.cn/Article/details/gt2zwnbfcbn.html

Ruby: s.index("x")
来源：http://dali.havefunace.top/Article/details/gt2gmbnmdde.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2wgybpmyf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258.top/Article/details/gt2fnovmzgl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aizwys.cn/Article/details/gt2bmzkvwnt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sxryk.cn/Article/details/gt2gjsgxpln.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gt2onhrqzhq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gotoacloud.top/Article/details/gt2jlmxragj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gt2hhovcwrr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zdqjudy.top/Article/details/gt2azpyohoa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ppjwa.cn/Article/details/gt2beqjmidb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pycfn.com/Article/details/gt2hxnzeoul.html

[E06] 替换子串
来源：http://dali.dianchejie.cn/Article/details/gt2hkxynmcp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gt2cncmryuy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.316326.xyz/Article/details/gt2zitrpwqh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2ymjuruzt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2gtqpctok.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2dignekzr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhcouiio.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2jomszbqm.html

C#:   s.Replace("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2mitqdioc.html

[E07] 按分隔符拆分
来源：http://dali.hfpthk.cn/Article/details/gt2hdcaneuu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnqzz.top/Article/details/gt2sunalxot.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2rtroxtdn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xziqi.cn/Article/details/gt2phjwtphp.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gt2lusyyjsu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenzaomai.com/Article/details/gt2iymhfvki.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnqzz.top/Article/details/gt2wgwercqx.html

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gt2pkpoyagp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gt2puogchpp.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gt2nfywknjw.html

Py:   ",".join(items)
来源：http://dali.kuanghao11.cn/Article/details/gt2xspyreff.html

PHP:  implode(",", $items);
来源：http://dali.yanxiufei.cn/Article/details/gt2zrtkeart.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2yrnxstsi.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2yvhykkob.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gt2uozaugkr.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gt2ypkrywml.html

Ruby: items.join(",")
来源：http://dali.shuidangran.top/Article/details/gt2yisvtzhz.html

C#:   string.Join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gt2xbwlqofv.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gt2yllammth.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.haohaochexian.top/Article/details/gt2xyzvojfp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2ptnqwrhm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gt2xnasyqea.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2pitbmyrm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ckzzmbhs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2veqfpdrt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.redwolf501.top/Article/details/gt2mwxgyqch.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gt2ptcbjgpu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gt2xwvsyybc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2tgbpesso.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nwbrower.top/Article/details/gt2gqnusfye.html

JS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtvovazw.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2twevizte.html

Java: String.format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2qltyueeg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2udokognv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gt2aezikpku.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxddciig.html

[E11] 反转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rsbuzwig.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gt2xwxtsswy.html

PHP:  strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gt2eguiukgs.html

JS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2qnifhmvs.html

TS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2hylzfope.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gt2iaktfhhm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258.top/Article/details/gt2nrrkqwqi.html

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gt2uthsobnf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gt2jffrsnvs.html

[E12] 统计某字符出现次数
来源：http://dali.kuanghao11.cn/Article/details/gt2znviiony.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gt2qvlrtzyh.html

PHP:  substr_count($s, "a");
来源：http://dali.haohaochexian.top/Article/details/gt2dcdwbysa.html

JS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gt2teugwawy.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gt2rgfuksjd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gt2awawdvbi.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gt2esmpmotu.html

Ruby: s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvfsoame.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jianghu66.top/Article/details/gt2tdtkcnoo.html

[E13] 逐字符遍历
来源：http://dali.xinyue.icu/Article/details/gt2gwwlulqv.html

Py:   for ch in s: print(ch)
来源：http://dali.zhengqikj.top/Article/details/gt2tvwqpdmo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tian-w.cn/Article/details/gt2nipasglt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gt2jrgbqdbs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2bjhsvvme.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258.top/Article/details/gt2mujshrkc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2msqfjyhx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dianchejie.cn/Article/details/gt2hgzfwkww.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkgtgkca.html

[E14] URL 编码与 Base64
来源：http://dali.ybcxt.top/Article/details/gt2dygyldou.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gt2dmlkzmbs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2rslogusn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gt2mgjchhfv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cucudq.cn/Article/details/gt2tpdkdobz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gt2apjcutpc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jiagoushi.top/Article/details/gt2xyzraspe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xylfe.cn/Article/details/gt2zjgbhnfy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shuidangran.top/Article/details/gt2xzcrnjjb.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gt2yjmvnbrw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.andypj.xyz/Article/details/gt2vyjgzjnk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gt2kwczkidf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbblzazz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gt2ykrnhdgs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.vqdsnc.cn/Article/details/gt2mianfmyb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvlyudmb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.mhx1999.top/Article/details/gt2ktxsujvn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ehwqpu.com/Article/details/gt2kahybvkg.html

[E16] 数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gt2faeaufel.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gt2ckojgedy.html

PHP:  number_format(1234567);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kspshyun.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kllncwcn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gt2jsztqtcx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.redwolf501.top/Article/details/gt2upraclpb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgfzy.top/Article/details/gt2iizrkjjf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srkdpvrl.html

C#:   1234567.ToString("N0")
来源：http://dali.tianlin.xyz/Article/details/gt2yivmqgbc.html

[E17] 首字母大写
来源：http://dali.zycfv.cn/Article/details/gt2qmkrvuaa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gt2vclppabx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shuidangran.top/Article/details/gt2suegmneo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gt2ankxjfpe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gt2omiucqge.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zycfv.cn/Article/details/gt2ybfgjlkq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tian-w.cn/Article/details/gt2kdstukkp.html

Ruby: s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gt2jtymlhvk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.havefunace.top/Article/details/gt2xanewrdf.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gt2jmdnxcvp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aibaodan.cn/Article/details/gt2zyrjdqat.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jiagoushi.top/Article/details/gt2wckobgdd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2equpemqa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2nisfngyj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2pqqaxeff.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2qnydrkem.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ehwqpu.com/Article/details/gt2mpivngyl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gt2odyoqdwx.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gt2ibbnywva.html

Py:   s.splitlines()
来源：http://dali.yuxming.cn/Article/details/gt2iahonmzf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2hsbgwctu.html

JS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gt2iskqrgom.html

TS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gt2ksxmdhzy.html

Java: s.lines().toList()
来源：http://dali.jqgfzy.top/Article/details/gt2unxxcizi.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gt2uwigwjjj.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gt2bgctmutt.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gt2fdfixaqg.html

[E20] 判断字符串是否为空
来源：http://dali.ydzc1.top/Article/details/gt2txyxjxsa.html

Py:   if not s:
来源：http://dali.ybcxt.top/Article/details/gt2nkeggsdf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gt2ugrkprpq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2awsgfjif.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ossaxmic.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gt2adcsnrtf.html

Go:   if s == "" {}
来源：http://dali.aizwys.cn/Article/details/gt2wqmasbvy.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gt2qlcmgety.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ydzc1.top/Article/details/gt2ubpptcag.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gt2rkduxtyg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gt2auowyanf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2emniezwi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2qihsujpi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2sevtmadq.html


<!-- 参考信息 -->