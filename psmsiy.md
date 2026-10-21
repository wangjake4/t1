代发 wailian999

[D15] 去重
来源：http://dali.yj202588.top/Article/details/gtouslltgd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtgdkdkjxz.html

PHP:  array_unique($arr);
来源：http://dali.guannengcc.top/Article/details/gtfofrbnmg.html

JS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gthpklpetm.html

TS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtmhpwiniv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daria6918.cn/Article/details/gtmbvrvsqr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cqqwz.cn/Article/details/gtacznctxv.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gtgwuhflds.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gtvojwsjtc.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gtzmarfnez.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtqfynyltk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gttpkwjdmo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtpkyrryfw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtkuxzvmjk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gtvaqtxown.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtkfezvugg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aibaodan.cn/Article/details/gtnxqyncgv.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gtrdbpcbtx.html

[D17] 最大值与最小值
来源：http://dali.hysaishi.cn/Article/details/gtgcnvxogl.html

Py:   max(arr);  min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtqalnltrc.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtratdrvtj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gtqskbyqgl.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gtabzfuecz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yonumen.top/Article/details/gtnhfitlii.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zycfv.cn/Article/details/gtvberxpev.html

Ruby: arr.max;  arr.min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztlhjgem.html

C#:   list.Max();  list.Min()
来源：http://dali.jyoumei.cn/Article/details/gtiymwsqve.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gtxeormzhy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ydzc1.top/Article/details/gtsyjploca.html

PHP:  array_merge(...$nested);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfffinlsj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenlongwang.top/Article/details/gtmhvsiqou.html

TS:   nested.flat();
来源：http://dali.quarkkingdee.top/Article/details/gtyhbjjawz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gttrxbcqbo.html

Go:   // 手写双层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxwfkdax.html

Ruby: nested.flatten
来源：http://dali.guannengcc.top/Article/details/gtoxfnuhpo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gtjcsywehv.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gtzxnqxhte.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.redwolf501.top/Article/details/gtqohozjiy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gtoncnlpef.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pengpengdd.cyou/Article/details/gtwjgasozo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gthdhwniiv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gtzhpumdnb.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecbwmpud.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jianghu66.top/Article/details/gtbtmdlydn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangdashe.top/Article/details/gtcwnqmzya.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokjowwtl.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gtnhvxybtn.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gtzrgocmgz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtzezcaryd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtlscntrov.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gtiisvqzly.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gtctbvbocr.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gtxcxahxgq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tianlin.xyz/Article/details/gtzespfvjl.html

[D21] 判断是否包含某元素
来源：http://dali.guannengcc.top/Article/details/gtpbapovha.html

Py:   x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtrnqcbixd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tanke756.top/Article/details/gtibszzefy.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtdbpjhvcg.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gteoohneoh.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gtqfahcfuf.html

Go:   slices.Contains(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtpnxqdykg.html

Ruby: arr.include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtwtxrtykl.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtshwnipdw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gtnkfcvkbk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gtunffwrsf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuanzhike.top/Article/details/gtoefacrgp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gtyhlsjadg.html

TS:   [...arr];
来源：http://dali.jlsjyb.cn/Article/details/gtobbjtxba.html

Java: new ArrayList<>(list);
来源：http://dali.gogol.net.cn/Article/details/gtapcdpkoc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiusgfdy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gtmobblpco.html

C#:   new List<int>(list);
来源：http://dali.cdnleiting.top/Article/details/gtbsfmnziu.html

[D23] reduce 累积计算
来源：http://dali.yueranfly.top/Article/details/gtqvbfegdh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.andypj.xyz/Article/details/gtyxnpbcio.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ybcxt.top/Article/details/gtvlcsewtl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtputekljy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gthqptjrjq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aibaodan.cn/Article/details/gtbpvqqrik.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gthgtrsoly.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hysaishi.cn/Article/details/gtuzkwtxva.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ydzc1.top/Article/details/gtbzqretbi.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtetlnhgtx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gtpydpclkc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtotvriduv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangdashe.top/Article/details/gtusqiiteh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gtwxxyosey.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xziqi.cn/Article/details/gtgkjaojfw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gtdftmcqrs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gtnwihjalt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gtpcqltzfp.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigufen.top/Article/details/gtnsbtfrgw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sweek.top/Article/details/gtnipjbehv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.birdmap.top/Article/details/gtusvnighp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gtyosjrcuv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gtvxujkdlh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gtekdxcifr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.svipenyu.cn/Article/details/gtqsfyrqqs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cashguo.top/Article/details/gtwgpyjcha.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtijfjrnln.html

[D26] 数组转字符串
来源：http://dali.pycfn.com/Article/details/gtkzwpnlzt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tanke756.top/Article/details/gtkbvvubxr.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxbtaucq.html

JS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtkyztbpdi.html

TS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gttiuvynkv.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtjghccalk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gtobplatvc.html

Ruby: arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtucorobuq.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gteftbgiiz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzdmzhire.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gtdjdxbawx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtccfscafs.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtvnkglamr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ivvv.top/Article/details/gtldtrtylj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.redwolf501.top/Article/details/gtgtoahuro.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtlhhdvzdt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtjunedurl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsdulugg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jianghu66.top/Article/details/gtksqxarjp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nwbrower.top/Article/details/gtvzyvumdt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtdbjhgbhn.html

[E02] 重复字符串
来源：http://dali.hnqzz.top/Article/details/gtcfohphjo.html

Py:   "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtzfzvxdtz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cdnleiting.top/Article/details/gtmgcjpdap.html

JS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtnnpsyvvo.html

TS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtivuyjwuq.html

Java: "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtisnusgjp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtbogocorv.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtojrvembs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cdnleiting.top/Article/details/gtpjmygxdw.html

[E03] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtuyimdjjs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fengsongda.top/Article/details/gtqbrxcpyc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtpwufbppj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtsworzpsq.html

TS:   s.slice(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtydvvolah.html

Java: s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtkukupcfa.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.redwolf501.top/Article/details/gtaaqxzfrc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.svipenyu.cn/Article/details/gtqfrkevmn.html

C#:   s.Substring(1, 3)
来源：http://dali.gotoacloud.top/Article/details/gtzczcbhxy.html

[E04] 查找子串位置
来源：http://dali.yanxiufei.cn/Article/details/gtmznuylxv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtyqiaqdvh.html

PHP:  strpos($s, "x");
来源：http://dali.yvedp.cn/Article/details/gtatvrqsgr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cheryme.top/Article/details/gtqbrfhafi.html

TS:   s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtxwohvsmi.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtbqpkxkog.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxuanxn.top/Article/details/gthetyznba.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgstlrmkd.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtnoojsfju.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.kuanghao11.cn/Article/details/gtdrhecipa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtdhsjupff.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hammf.cn/Article/details/gtdnthgdqk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gtfucygvsr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuanzhike.top/Article/details/gtolabtuld.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtkdyeityw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgufenzy.top/Article/details/gtlcyfgurk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aibaodan.cn/Article/details/gteisxirsv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtmcyarunh.html

[E06] 替换子串
来源：http://dali.vqdsnc.cn/Article/details/gtwdnvuqvf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtxruorlvn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ppjwa.cn/Article/details/gtguvgoimk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtjjvrkvca.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtzcfuinln.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdnthkak.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtpzjehgqh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gtmhddwuet.html

C#:   s.Replace("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtdgdjzxzb.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gtvwkbrnvh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gtiwnxhsst.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.redwolf501.top/Article/details/gtwjgtqkzu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aibaodan.cn/Article/details/gtmdwiszzv.html

TS:   s.split(",")
来源：http://dali.chenlongwang.top/Article/details/gtkdmxfauc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigufen.top/Article/details/gtdymuaubf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gtvrfgnjno.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gtqddosrst.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guowangkeji.top/Article/details/gtpgllzfsb.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gtvnsorfmh.html

Py:   ",".join(items)
来源：http://dali.yuanzhike.top/Article/details/gtfyppmxcy.html

PHP:  implode(",", $items);
来源：http://dali.zhixingplan.top/Article/details/gtfsdxrioc.html

JS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gteolvchmr.html

TS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtulxovnvc.html

Java: String.join(",", items)
来源：http://dali.redwolf501.top/Article/details/gtdworsdti.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gtubembdrp.html

Ruby: items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtimvrhgty.html

C#:   string.Join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtgzkvdxwd.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtacdrcypv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtaioefqxp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgfzy.top/Article/details/gtyvznrmfw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtiltitski.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtssjjcasu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gtystktbeq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gtuigbzkpq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqzxrgqg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gtubphzjhb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gthewgvcuu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtnrtbvapo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gtnbyvgnoj.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtuuozchwf.html

TS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtoxaoyhdd.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtzoxcjcbf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtwermccmd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtczhhpqwo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gtyxcbyguv.html

[E11] 反转字符串
来源：http://dali.yangfankeji.com/Article/details/gthugkehrm.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gtvyscaoif.html

PHP:  strrev($s);
来源：http://dali.shuidangran.top/Article/details/gtydtgovtm.html

JS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtcmnisdoa.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtcbwveadx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gtpmxrhext.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhixingplan.top/Article/details/gtxhruwugj.html

Ruby: s.reverse
来源：http://dali.cdnleiting.top/Article/details/gtuyqvagxy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtnascocdn.html

[E12] 统计某字符出现次数
来源：http://dali.ybcxt.top/Article/details/gtirerbxtv.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gtsnucqjwi.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gtswecbjeo.html

JS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtxexnkuds.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtqpmkieae.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gtiapqtvpv.html

Go:   strings.Count(s, "a")
来源：http://dali.hnqzz.top/Article/details/gtlnrigyic.html

Ruby: s.count("a")
来源：http://dali.gzhubu.top/Article/details/gtxllfyyss.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sufxvd.cn/Article/details/gttuzzdryv.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtgdgyhtzt.html

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gtilwgxfvs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtknpvhvqh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gtjaddnnnu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtttsnncqi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtreuuxdvw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangdashe.top/Article/details/gtpqrandbm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zdqjudy.top/Article/details/gtcezyhpmw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gtsmhgwvwj.html

[E14] URL 编码与 Base64
来源：http://dali.nanxinkj.top/Article/details/gtqrdpbsee.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gtmsndtaix.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gtcpyemvlx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmltzsore.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dashuyun.cn/Article/details/gtonckseeh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtortsxnwh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenjidiqi.icu/Article/details/gtksavhxty.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gtuddveuxt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtscuytgrg.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gtbgfjmlgv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gticabpxjq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gtarwqwhcl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.vqdsnc.cn/Article/details/gtefmcxdyb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258.top/Article/details/gtvkblgagy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.quarkkingdee.top/Article/details/gtudsqcumf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hysaishi.cn/Article/details/gtpbxaqqcu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigufen.top/Article/details/gtdhplwlal.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gtqhdxwijm.html

[E16] 数字千分位
来源：http://dali.shanyushiyangtech.top/Article/details/gtrslmxnbf.html

Py:   f"{1234567:,}"
来源：http://dali.birdmap.top/Article/details/gtcgfjwkjm.html

PHP:  number_format(1234567);
来源：http://dali.zycfv.cn/Article/details/gticffoypt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gthofgoxyw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtunjmssog.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtdmqciekf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhoulong.xyz/Article/details/gtdoopopfy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtwvsfwfck.html

C#:   1234567.ToString("N0")
来源：http://dali.yangfankeji.com/Article/details/gtyjeomhic.html

[E17] 首字母大写
来源：http://dali.gzhubu.top/Article/details/gtzcjgqksd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pycfn.com/Article/details/gtkeiakwag.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gtdrgdnawb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtjoerzwnc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtdlgxttfn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gtfqaqdnbv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cashguo.top/Article/details/gtzslcxfzn.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gtpksgloeg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ivvv.top/Article/details/gtjpjdvuke.html

[E18] 模板占位符替换
来源：http://dali.nanxinkj.top/Article/details/gtcwpyfbfu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gtnvwbislj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhiwuduotai.top/Article/details/gtwttqvmkc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtbnfomgis.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtrhyekivu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtokwxkdvw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtwirjbmdn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlazrbfsv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gtaejpifby.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gttpjbodcy.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gtmnjxwhbw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gtvdecwavm.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtvoxfltdz.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtsmgawcyk.html

Java: s.lines().toList()
来源：http://dali.wangdashe.top/Article/details/gtxcwnccri.html

Go:   strings.Split(s, "\n")
来源：http://dali.cheryme.top/Article/details/gtraasxllm.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gtqukhavpd.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gtricyasaf.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrcwvbyw.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gtclfilhcq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dianchejie.cn/Article/details/gtjtayhkfv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gtcomrhgro.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpoxvafqa.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtcpjvxqoh.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gtcutfuvan.html

Ruby: if s.empty?
来源：http://dali.ehwqpu.com/Article/details/gtrjclfdjk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gtjzcewcbd.html

[E21] 超长截断加省略号
来源：http://dali.cashguo.top/Article/details/gtrxrahsit.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gtgxczspel.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtvnmidsih.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtkjjifsfk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtyrubakeg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtlmkorcmd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gtyfmbbzzj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtfwcypzsg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtuynwztio.html


<!-- 参考信息 -->