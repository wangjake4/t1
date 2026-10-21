代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ppjwa.cn/Article/details/gtywhcdxha.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtvbeispxs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtssiwniuj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sxryk.cn/Article/details/gtprrbtvqk.html

[D15] 去重
来源：http://dali.nwbrower.top/Article/details/gtrnlewpck.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gtynmqoexm.html

PHP:  array_unique($arr);
来源：http://dali.tian-w.cn/Article/details/gtvhlzdmea.html

JS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtinfsozji.html

TS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxyouyqt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gthsoqjynh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sufxvd.cn/Article/details/gtfbuzjikv.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gtmifktokz.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gtksmdysni.html

[D16] 求和与平均值
来源：http://dali.chenlongwang.top/Article/details/gtxfxczrhy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtkcnjbvvi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.0kj1m.cn/Article/details/gthcxnoyvr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtyezssqpb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gtbsxhrrzu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yangfankeji.com/Article/details/gtajlsogfh.html

Go:   // 手写循环累加
来源：http://dali.tianlin.xyz/Article/details/gtgfudftkl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fzhhl.top/Article/details/gtkrrdnrar.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxinkj.top/Article/details/gtfpintkgr.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gthnskgqwe.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gtlgeoujbt.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gtlwjkooei.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgfzy.top/Article/details/gtklzhohiq.html

TS:   Math.max(...arr);
来源：http://dali.meibo888.top/Article/details/gtgcpudlfw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtpxwshrtq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gtjytmobwi.html

Ruby: arr.max;  arr.min
来源：http://dali.hammf.cn/Article/details/gtuplzkkcv.html

C#:   list.Max();  list.Min()
来源：http://dali.zhengqikj.top/Article/details/gtyoeiyyba.html

[D18] 扁平化嵌套数组
来源：http://dali.sxryk.cn/Article/details/gtnxlstooe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gtjntvgzxx.html

PHP:  array_merge(...$nested);
来源：http://dali.sweek.top/Article/details/gtsiftduzs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gtcrwvdggq.html

TS:   nested.flat();
来源：http://dali.nanxinkj.top/Article/details/gtpwxstehj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sysykeji.top/Article/details/gtnvxvbszw.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtvotfxatv.html

Ruby: nested.flatten
来源：http://dali.hnxiangtu.top/Article/details/gtadcautlp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtaekiewyl.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gtjhhhmvfi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhongyouzk.top/Article/details/gtbfsateil.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgufenzy.top/Article/details/gtlfzqgiyg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlkeypkg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gtteapatyj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xziqi.cn/Article/details/gtsijvraix.html

Go:   // 手写 map[string][]T
来源：http://dali.feifeiyinyue.top/Article/details/gtljapmkku.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jianghu66.top/Article/details/gtekindqfy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gtfarjqlcc.html

[D20] 统计每个元素出现次数
来源：http://dali.haohaochexian.top/Article/details/gtguwtaqwh.html

Py:   Counter(arr)
来源：http://dali.tanke756.top/Article/details/gtbjaxvgdg.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtfasqqmki.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtsrtoniya.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtsvehcwmk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gogol.net.cn/Article/details/gttcghatth.html

Go:   // 手写 map[T]int
来源：http://dali.aibaodan.cn/Article/details/gtmufxwakq.html

Ruby: arr.tally
来源：http://dali.sweek.top/Article/details/gtiadumuzw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gtzyobisfv.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gtftgyhwdv.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gtmedxspld.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gttbwthxkr.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtkjhdclap.html

TS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtwxytpyxj.html

Java: list.contains(x)
来源：http://dali.yvedp.cn/Article/details/gtxbovltku.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtgnwkwoyt.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtmxcaecyb.html

C#:   list.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtphtoasam.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj202588.top/Article/details/gtcvmcvkto.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gtwamgdwbo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.bjfxy.top/Article/details/gthtedtoed.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gteufcvxzk.html

TS:   [...arr];
来源：http://dali.c1oappe.top/Article/details/gtssfqhmls.html

Java: new ArrayList<>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtigewkjxa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yueranfly.top/Article/details/gtjvhjqeti.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tanke756.top/Article/details/gtphxjqpwa.html

C#:   new List<int>(list);
来源：http://dali.yj20258888.top/Article/details/gtavbalrbb.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gtoxjfgzor.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.snrcjt.cn/Article/details/gtuunajtkw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gtgyrbhqji.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtvakgubre.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gtnjmhtjai.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndmgraay.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gthtrezpgf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gtkigmvpkl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sweek.top/Article/details/gtxidmmllo.html

[D24] 字典 / Map 基本操作
来源：http://dali.yonumen.top/Article/details/gtghonizxh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkxdegbu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gtseduybme.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gtoxghqmfd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtvuxduhlq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ybcxt.top/Article/details/gtnhtcdzjg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gtlmxlceqb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sxryk.cn/Article/details/gtqvawvlco.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gthbxbdbye.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gtujfkxyha.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gttulmgywp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gtigpczypi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gttqrabruj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cashguo.top/Article/details/gttzjtngdi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtnigwmdim.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xylfe.cn/Article/details/gtxweqjhkt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gtxyjncavn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.smart0.xyz/Article/details/gtwrnuzghq.html

[D26] 数组转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gttccnbohq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hywenlv.cn/Article/details/gtlyxovajy.html

PHP:  implode(", ", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtkhhrxcak.html

JS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtaxfgleuv.html

TS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtdmlunfcu.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkxwpxwa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.haohaochexian.top/Article/details/gtmrdoupld.html

Ruby: arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtcvobcbbt.html

C#:   string.Join(", ", list)
来源：http://dali.cheryme.top/Article/details/gthxkwnvop.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtrnkaerkh.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gtnmghhrbz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtvfowkoru.html

[E01] 拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtawmnjocs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gtcfcyfpbr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.svipenyu.cn/Article/details/gtygzctczd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gtbruhpiyn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtbjqiquvr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gtswrqmttv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xylfe.cn/Article/details/gtaqzjkdjf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gtjyiktudt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtasiuiaav.html

[E02] 重复字符串
来源：http://dali.gzhubu.top/Article/details/gtbanrqcmm.html

Py:   "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtwtizvuka.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gtlznrsuhb.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtjlimthph.html

TS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtmroqjvxw.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtliokpxaj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ppjwa.cn/Article/details/gtscqvtzch.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtmnwovuxf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yonumen.top/Article/details/gtswxobggg.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gtjuvgqumf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.havefunace.top/Article/details/gtkivuwbxv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtmavblkix.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtcodexfma.html

TS:   s.slice(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtgcprrjfp.html

Java: s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtectxsnjx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yongpay.top/Article/details/gtiwbjxwfk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuanzx.com/Article/details/gtwqjtmlwa.html

C#:   s.Substring(1, 3)
来源：http://dali.316326.xyz/Article/details/gtvbdopvfv.html

[E04] 查找子串位置
来源：http://dali.yangfankeji.com/Article/details/gttidstmwj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gtibntrelo.html

PHP:  strpos($s, "x");
来源：http://dali.sweek.top/Article/details/gtenqfrqnj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.vqdsnc.cn/Article/details/gtdgtkghkw.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtjkopgnvm.html

Java: s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtaixxdhms.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gtfvlswdhi.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtohtdyxra.html

C#:   s.IndexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gttwlowtni.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gtkjokdtmy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.c1oappe.top/Article/details/gtoftdopad.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gtbjrwumsr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtzxurkdji.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gtplivxaii.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtpmbuyfdg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.redwolf501.top/Article/details/gthjusxjfh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtbqirlwzf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtaterldwn.html

[E06] 替换子串
来源：http://dali.ppjwa.cn/Article/details/gtpgryxsph.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtsnonaerp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gtoburqdga.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtgwbmpjet.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtgvejutca.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcntwhiq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtwuyunshp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtmzulemlz.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtdtwppuzk.html

[E07] 按分隔符拆分
来源：http://dali.yanxiufei.cn/Article/details/gthpakpslv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cheryme.top/Article/details/gtbmmkybyk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xinyue.icu/Article/details/gthjsdbirb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ybcxt.top/Article/details/gtyzgpkpkg.html

TS:   s.split(",")
来源：http://dali.cucudq.cn/Article/details/gtbjgxblpv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gtwknfztsa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtvnfrjvxw.html

Ruby: s.split(",");  s.split
来源：http://dali.wangdashe.top/Article/details/gtcanfqnqt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yanxiufei.cn/Article/details/gtbcmqwfqf.html

[E08] 数组按分隔符合并
来源：http://dali.guowangkeji.top/Article/details/gtmcuaoqry.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gthcocimuy.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gtxxiwmytj.html

JS:   items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtjcumfopk.html

TS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtzilxatym.html

Java: String.join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtkfvuxwwi.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gthleyjnkm.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtyiiccfcj.html

C#:   string.Join(",", items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgodpaws.html

[E09] 去除所有空白字符
来源：http://dali.andypj.xyz/Article/details/gtmlnmwaoo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gtyvekgrxp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhixingplan.top/Article/details/gtfbsunbuz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtktpkbtnt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtdonvbkbj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gtokdzzkau.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.vqdsnc.cn/Article/details/gtdohxonsn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gtkwfwpfyq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gthjxfvspq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmpwxoiz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtelhiqbzi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnqzz.top/Article/details/gtgwsbveeo.html

JS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtbipxbcpy.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtvxjsmdmx.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtuofhaupb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtdfxqwdah.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtwjonukpk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.quarkkingdee.top/Article/details/gtbydulbev.html

[E11] 反转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfqkzino.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtnknixgpk.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprqualay.html

JS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtfyutytkj.html

TS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtytsrqsrl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdotgbluw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jianghu66.top/Article/details/gtidzfbrge.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtwzalltct.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gtzvpzzjmh.html

[E12] 统计某字符出现次数
来源：http://dali.iojbl.cn/Article/details/gtqpewygcp.html

Py:   s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gtsntzvvnx.html

PHP:  substr_count($s, "a");
来源：http://dali.xuanzx.com/Article/details/gtoqimrkmy.html

JS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gtxmadsxqg.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtzlconvur.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.bjfxy.top/Article/details/gtbfzskutv.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gtposodhdd.html

Ruby: s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgoblmurk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jlsjyb.cn/Article/details/gtaturxybb.html

[E13] 逐字符遍历
来源：http://dali.chenlongwang.top/Article/details/gtzwtdhbbz.html

Py:   for ch in s: print(ch)
来源：http://dali.hnqzz.top/Article/details/gtqpfymkjt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yongpay.top/Article/details/gtseaptgcn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtzoryswmk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gtcjkchsnj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtmsuqcybt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gtutrglzjy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrquaiyao.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtzxnknzqq.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gtdjbimatk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtdjicjute.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shzxlz.cn/Article/details/gtnkejrasv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenlongwang.top/Article/details/gtpchnihbc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gtsmlextsy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gtzrqqfkpi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtocmtallo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ppjwa.cn/Article/details/gteyyhxzqa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cucudq.cn/Article/details/gtoiyfqmav.html

[E15] HTML 转义 / 反转义
来源：http://dali.haohaochexian.top/Article/details/gtrsdxeuuj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pycfn.com/Article/details/gtimzcropm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guowangkeji.top/Article/details/gtlchjuhht.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gteybnqlma.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gtaokyptwn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gtrzooooiy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxinkj.top/Article/details/gtqwrylyvc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sysykeji.top/Article/details/gtyusesxhj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gtijpawgrk.html

[E16] 数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdsrfvpt.html

Py:   f"{1234567:,}"
来源：http://dali.cheryme.top/Article/details/gtsuirntaq.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gtqmkjljjq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gtlckldxmv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtzunjlskv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hysaishi.cn/Article/details/gtfchzcnxg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gtrokbhasi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgfzy.top/Article/details/gtogdcuayn.html

C#:   1234567.ToString("N0")
来源：http://dali.ydzc1.top/Article/details/gtuamkrrmx.html

[E17] 首字母大写
来源：http://dali.yanxiufei.cn/Article/details/gtdlebnyfd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gtrznzwurj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gtotcwwkic.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtkkpzxbtj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtydxlpmti.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zdqjudy.top/Article/details/gtmhdyozlf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhixingplan.top/Article/details/gtezffsopi.html

Ruby: s.capitalize
来源：http://dali.ehwqpu.com/Article/details/gtinimpnsy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gtujkpnvni.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gtqhcdoqju.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gtqexobvzb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gtazrhpwhv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvyhcqqn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtgpummxba.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtvidcqxrj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtjsrymaia.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtryhzibyb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtsgeujfzx.html

[E19] 多行文本按行拆分
来源：http://dali.gotoacloud.top/Article/details/gtspyhwlwo.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gtflwsctpw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtvextpswh.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtthbedihx.html

TS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gttiwpkhzy.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gttzhzoqjq.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gtqlaehzvz.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gtcljxgrll.html

C#:   s.Split('\n')
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeawyeyc.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gtsfpblmhh.html

Py:   if not s:
来源：http://dali.sysykeji.top/Article/details/gtalknzxdp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gthsxzjgii.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ppjwa.cn/Article/details/gtjpapfaqd.html

TS:   if (s === "") {}
来源：http://dali.shangyingyoupin.top/Article/details/gtefbxbksv.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcwpgwmrl.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gtbaourrgd.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gtrtvbhpiw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.snrcjt.cn/Article/details/gtnhhgbsnq.html

[E21] 超长截断加省略号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvypuxrg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhixingplan.top/Article/details/gtfmwkzonm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gthwlxanit.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtcqybwwpd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtfdgbsijg.html


<!-- 参考信息 -->