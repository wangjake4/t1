代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtkvtowpuh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pycfn.com/Article/details/gtcznoyulc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.bjfxy.top/Article/details/gtrcurmxzn.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjyuxnly.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtrceekrxb.html

[D16] 求和与平均值
来源：http://dali.smart0.xyz/Article/details/gtbipvydph.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtjgnbxypu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zycfv.cn/Article/details/gtgcfnguyx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtjxjthrjr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtintgcpgz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgskiuojc.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gtokhfjxuw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gtuyticddg.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gtkzpozvoq.html

[D17] 最大值与最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuifwnle.html

Py:   max(arr);  min(arr)
来源：http://dali.svipenyu.cn/Article/details/gtcllvekvm.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gtfohqbwmr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gtguidswny.html

TS:   Math.max(...arr);
来源：http://dali.hnxiangtu.top/Article/details/gtvozwtdpw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gtcmrafiul.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtrlnjksqy.html

Ruby: arr.max;  arr.min
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcgqstty.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gtqeahdywb.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gtjgancnhv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhixingplan.top/Article/details/gtckxfvkll.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gtmwjsmtkm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gtrmmzymtr.html

TS:   nested.flat();
来源：http://dali.nanxinkj.top/Article/details/gtawdzuujl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gtsgufaaas.html

Go:   // 手写双层循环
来源：http://dali.svipenyu.cn/Article/details/gtydrywjle.html

Ruby: nested.flatten
来源：http://dali.pycfn.com/Article/details/gthxpgbwwc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtlwvmthsn.html

[D19] 按字段分组
来源：http://dali.pengpengdd.cyou/Article/details/gtecrasuog.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gtchojdpjb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gtxroqrkdb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gtcjnrrzgw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtlkkfqxpj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258888.top/Article/details/gtupomwzjy.html

Go:   // 手写 map[string][]T
来源：http://dali.daxiang520.top/Article/details/gtbudbduao.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cashguo.top/Article/details/gtbhygtden.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenzaomai.com/Article/details/gtqjiriyxz.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpxqskij.html

Py:   Counter(arr)
来源：http://dali.haohaochexian.top/Article/details/gtdrmefyhu.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gttjyujdqk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtrxxfdzyx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtxzzfqeum.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guowangkeji.top/Article/details/gtlfxntpzd.html

Go:   // 手写 map[T]int
来源：http://dali.zhiwuduotai.top/Article/details/gtozajcurp.html

Ruby: arr.tally
来源：http://dali.shangyingyoupin.top/Article/details/gtltcgxakg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gtzvfrjglr.html

[D21] 判断是否包含某元素
来源：http://dali.meibo888.top/Article/details/gtwatcbtdv.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtwmakbkoq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.redwolf501.top/Article/details/gtsocowxuv.html

JS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtkkcnphrs.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtkathgfgm.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtabxqdkjs.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtgfbtogjv.html

Ruby: arr.include?(x)
来源：http://dali.sweek.top/Article/details/gtrokeakuk.html

C#:   list.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtfhirkcof.html

[D22] 复制数组（避免共享引用）
来源：http://dali.kuanghao11.cn/Article/details/gtjrjsvmpl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gtisnhjgge.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gtwvdpoyuh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.meibo888.top/Article/details/gtywrkyfrp.html

TS:   [...arr];
来源：http://dali.feifeiyinyue.top/Article/details/gtjlifzdxm.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gtrgxkzcdy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gtplqwljrn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangdashe.top/Article/details/gtrqzqoftx.html

C#:   new List<int>(list);
来源：http://dali.fengsongda.top/Article/details/gtrotcwsmd.html

[D23] reduce 累积计算
来源：http://dali.zycfv.cn/Article/details/gtnhwixoho.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gtslglvoze.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsccwqstn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gtpbybhehh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtquuqdxdu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.0kj1m.cn/Article/details/gtucxqnvme.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gtmspengpf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jiagoushi.top/Article/details/gtdbynmtdj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gtypcevcqo.html

[D24] 字典 / Map 基本操作
来源：http://dali.pycfn.com/Article/details/gthtyzbhvr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.0kj1m.cn/Article/details/gtpyvpfaom.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gtpaaivkdq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daxiang520.top/Article/details/gtqiwbpuky.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtqidbmneh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gtpqjtqjsw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gtslrcjime.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuanzx.com/Article/details/gtzzzkajkw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gtulrkeknf.html

[D25] Set 集合去重与交并差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivvcsuaj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gtijtyjyzy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gttriemmuk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuanzx.com/Article/details/gtcpkbewxn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuanzhike.top/Article/details/gtamaohjek.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.smart0.xyz/Article/details/gtammzrxfg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gtmrpckwgh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gtbxansxah.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gtwkfswtzt.html

[D26] 数组转字符串
来源：http://dali.gogol.net.cn/Article/details/gtkuovxcjf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gtplhvgsnj.html

PHP:  implode(", ", $arr);
来源：http://dali.xylfe.cn/Article/details/gtkyvnhrsu.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtoyzvqcto.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtmbmjxcmx.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtyjesfhdu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gtsqjshjhe.html

Ruby: arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtvilywjtn.html

C#:   string.Join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gtmwrbeozr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthmgeudlt.html

E. 字符串处理
来源：http://dali.redwolf501.top/Article/details/gtpvjxadgq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtifjvboew.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtmpeirr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuxming.cn/Article/details/gtqhajnirb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenlongwang.top/Article/details/gtrzmfmaij.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtwelqztll.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gtgotbdbrm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gtoehraawt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gaohongyu789.top/Article/details/gtahtgjjwa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhiwuduotai.top/Article/details/gtkxbfyxfe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtmkwecpib.html

[E02] 重复字符串
来源：http://dali.guannengcc.top/Article/details/gtpcyqnwmm.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtyeqtntpx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtlejyskzx.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtlxilfqgg.html

TS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtfbawpsxc.html

Java: "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtvteaiyqg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dashuyun.cn/Article/details/gtibciyxcu.html

Ruby: "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtqqefmzkw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.birdmap.top/Article/details/gtqledctiv.html

[E03] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtyotsnjmi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gogol.net.cn/Article/details/gtfyvrhcph.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gttwcwexlz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtbsdkjzub.html

TS:   s.slice(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtejkfpbre.html

Java: s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtaxoyvaty.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtijxirikv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cdnleiting.top/Article/details/gtcsayathk.html

C#:   s.Substring(1, 3)
来源：http://dali.redwolf501.top/Article/details/gtnklwnfiq.html

[E04] 查找子串位置
来源：http://dali.chenjidiqi.icu/Article/details/gtxbmszfiy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ydzc1.top/Article/details/gtbeybjmbe.html

PHP:  strpos($s, "x");
来源：http://dali.snrcjt.cn/Article/details/gthjjiyetp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yueranfly.top/Article/details/gtnoixdnjk.html

TS:   s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gthcswtydk.html

Java: s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtnfmopgtd.html

Go:   strings.Index(s, "x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvinfusv.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtlyhbqsel.html

C#:   s.IndexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtzpjfalth.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fengsongda.top/Article/details/gtmfqpihrn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shzxlz.cn/Article/details/gtakgmopbb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhengqikj.top/Article/details/gtghmeqxlz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gtphfuluqe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigfzy.top/Article/details/gtbxeuxmuc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gteiipedno.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yvedp.cn/Article/details/gtclavutdq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhongyouzk.top/Article/details/gtnyueqlih.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtyktxmoor.html

[E06] 替换子串
来源：http://dali.jlsjyb.cn/Article/details/gtfopedczf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gtgcxsmxsp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ybcxt.top/Article/details/gtqbsbfcwx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtjwiugtvg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtqfailtnz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtvgnoutum.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtvauwtbtg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gtuqyvtmck.html

C#:   s.Replace("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtiwmcgrkt.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gthbrynemy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwwkhygf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtjfcbdupn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhixingplan.top/Article/details/gtwtbjowvh.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gtojgrkvnm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.snrcjt.cn/Article/details/gtlpsfrzyg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.9152youxi.cn/Article/details/gtmzftcqog.html

Ruby: s.split(",");  s.split
来源：http://dali.bjfxy.top/Article/details/gtfevofjsd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgfzy.top/Article/details/gtxwnvdoim.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gtlomyymoq.html

Py:   ",".join(items)
来源：http://dali.aibaodan.cn/Article/details/gtqcsxmtgr.html

PHP:  implode(",", $items);
来源：http://dali.wangshuangyany.cn/Article/details/gtrdxplqip.html

JS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtsglsmyjp.html

TS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefnrpemq.html

Java: String.join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gtitwonrfq.html

Go:   strings.Join(items, ",")
来源：http://dali.ppjwa.cn/Article/details/gtspbuwgyg.html

Ruby: items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtfhdbkgbl.html

C#:   string.Join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gtqofczzfq.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gtqhzolqir.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shuidangran.top/Article/details/gtpjktlgqu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hfpthk.cn/Article/details/gttbamgfig.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmshkhpwn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gtfuwbxseu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gtxankkeen.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxinkj.top/Article/details/gtfolfpxjn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gtuvqshnpp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.redwolf501.top/Article/details/gtikjtazeh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gtltgkjuoy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtldlfgsaq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtjuveabku.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtdcgofyfo.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtcbaiixub.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrvgnuok.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtfiweodgi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtoggiqgrj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gtrfpkgrqe.html

[E11] 反转字符串
来源：http://dali.aibaodan.cn/Article/details/gtmbrlodce.html

Py:   s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gtdhydabqc.html

PHP:  strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gtqbeiogmq.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtkwnbaqtq.html

TS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtevydoskw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtgvvuptqv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtxusmmvpk.html

Ruby: s.reverse
来源：http://dali.9152youxi.cn/Article/details/gtpdslwpzj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtdtevycqd.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gtyhhxnzdc.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gtklseftkd.html

PHP:  substr_count($s, "a");
来源：http://dali.shangyingyoupin.top/Article/details/gtmunxkspu.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtnxrixyce.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtjlqzbhoq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gtnbhedvku.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gtlekzqyeh.html

Ruby: s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtgycffmjd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.feifeiyinyue.top/Article/details/gtzsbhowwm.html

[E13] 逐字符遍历
来源：http://dali.haohaochexian.top/Article/details/gttwhzusxn.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gtokgqhhra.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hywenlv.cn/Article/details/gtpzpsfafl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gtvksgffkj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtxouedgny.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtrcajhhgm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtgcezulqr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtjwcqymsk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gtmqcirnwk.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gttzzvtltg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jiagoushi.top/Article/details/gtuykppojg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gtqkfgvhzi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gtbqobmlze.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtisnxyigg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj202588.top/Article/details/gtncbhqmqi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gtmthdcoxy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gthtdnmxzo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtwceodipv.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhongyouzk.top/Article/details/gthjqslabh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gogol.net.cn/Article/details/gtudxumlej.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guannengcc.top/Article/details/gtbnaucvpx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cucudq.cn/Article/details/gtpgyfoffx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gtenggfyzh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ydzc1.top/Article/details/gtmkkcaseo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiouewkkj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gtgvxwpepu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgufenzy.top/Article/details/gtxcbjnddk.html

[E16] 数字千分位
来源：http://dali.xziqi.cn/Article/details/gtaqtxkmdt.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gtarhrzsyn.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gtpllkgugl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtlefabdzb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gtlygcqsqa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtjcjhrbyu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gtlaycdrvu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gtgffteytd.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gtjusflbwo.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gtpllklsys.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yangfankeji.com/Article/details/gtxwbecenf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yvedp.cn/Article/details/gtiyuxwdac.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gtdhfjxgsb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtlfqcdlmz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gtnlsnjqrk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gtxldrccwa.html

Ruby: s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gtihsfxubg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xziqi.cn/Article/details/gtsvaijpcz.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gtvdnjjzxi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gtdccbdwtm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jianghu66.top/Article/details/gttaptmyki.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtynvhdeiq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtkvzdtpzs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywehxwmn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtqmnbvjwh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtxjzextst.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gttzsfqltf.html

[E19] 多行文本按行拆分
来源：http://dali.tianlin.xyz/Article/details/gtqleyjmnh.html

Py:   s.splitlines()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvxnpfyl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtvmyxpnhq.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gtnqlzebqr.html

TS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gtagwdqotn.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gtyrvhnnsz.html

Go:   strings.Split(s, "\n")
来源：http://dali.gotoacloud.top/Article/details/gtcyrrrcbq.html

Ruby: s.lines
来源：http://dali.yueranfly.top/Article/details/gtoyndfgag.html

C#:   s.Split('\n')
来源：http://dali.hywenlv.cn/Article/details/gtqavgvfdv.html

[E20] 判断字符串是否为空
来源：http://dali.cdnleiting.top/Article/details/gthphueouj.html

Py:   if not s:
来源：http://dali.316326.xyz/Article/details/gtiavymlob.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gtcjgvvadt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gzhubu.top/Article/details/gtotlblzzs.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gtrbaddabi.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtolqtjlfm.html

Go:   if s == "" {}
来源：http://dali.yvedp.cn/Article/details/gtzaigmdei.html

Ruby: if s.empty?
来源：http://dali.zdqjudy.top/Article/details/gtwysibwcq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gtnswroimf.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gtxpkzgdag.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gtmqlsplqo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtnjiewkil.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtbsoknppz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtquuuthmp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtteapgief.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gtiqfmhvvc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtfriauboi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtkggkpqrp.html

[E22] 字节长度与字符长度
来源：http://dali.hywenlv.cn/Article/details/gtsilpthir.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gtetalixon.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtlqkwlgad.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtteojanpd.html


<!-- 参考信息 -->