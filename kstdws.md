代发 wailian999

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gtoiatswwb.html

C#:   list.IndexOf(x);
来源：http://dali.nanxuanxn.top/Article/details/gthjjhtnyb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258888.top/Article/details/gtxkclofnn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.andypj.xyz/Article/details/gtpesmcqnn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhoulong.xyz/Article/details/gtolbckxfw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtbgvttpsw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtsyulwowp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258888.top/Article/details/gtdtgntskl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gogol.net.cn/Article/details/gttcejevxa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gtjqqcbxmc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sxryk.cn/Article/details/gtyzeaggeo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigufen.top/Article/details/gtqqekvapf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.316326.xyz/Article/details/gthdvxjtrk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.bjfxy.top/Article/details/gtvjkdgkin.html

JS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtyefpbwyb.html

TS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtpobzxziq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.mhx1999.top/Article/details/gtbchryptf.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtqmgbgsyn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gthcglizjp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtehhmhkpl.html

[D15] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtewiiqars.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtzxvycnsg.html

PHP:  array_unique($arr);
来源：http://dali.gotoacloud.top/Article/details/gthzufayrz.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtdjhfscom.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtupuxcfks.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gtzjswlipe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.smart0.xyz/Article/details/gtrcmdbnaq.html

Ruby: arr.uniq
来源：http://dali.yanxiufei.cn/Article/details/gtpodhfaxg.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gtffdhkdbu.html

[D16] 求和与平均值
来源：http://dali.yueranfly.top/Article/details/gtqbvqirda.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daxiang520.top/Article/details/gtzhhjsfmg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtxgrqlfnx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtjoxefdea.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtklwewyea.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwvctnwu.html

Go:   // 手写循环累加
来源：http://dali.dashuyun.cn/Article/details/gtaomyzxqm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xziqi.cn/Article/details/gtcyvxqywu.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gtrqjsgdla.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gtvllaoiyw.html

Py:   max(arr);  min(arr)
来源：http://dali.haohaochexian.top/Article/details/gtycqgsbcy.html

PHP:  max($arr);  min($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtohbzwjnw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xinyue.icu/Article/details/gtnldkiryn.html

TS:   Math.max(...arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqqlrjcn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.smart0.xyz/Article/details/gturcjuwqw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtolisnlpp.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gttzajfjko.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gthbqmiuyz.html

[D18] 扁平化嵌套数组
来源：http://dali.gzhubu.top/Article/details/gtaqzppmez.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.redwolf501.top/Article/details/gtzzggbzlg.html

PHP:  array_merge(...$nested);
来源：http://dali.zhoulong.xyz/Article/details/gtaceaxyzk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuanzhike.top/Article/details/gtgikgtrdr.html

TS:   nested.flat();
来源：http://dali.gogol.net.cn/Article/details/gttkwwsdkp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fzhhl.top/Article/details/gtrrmvkpyx.html

Go:   // 手写双层循环
来源：http://dali.shangyingyoupin.top/Article/details/gtcybcbnsr.html

Ruby: nested.flatten
来源：http://dali.xuanzx.com/Article/details/gtbauwsfda.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gtdbjmhpap.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gtnjfkcbei.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gtwxopqpgt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gtjwcroqqf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gtyqycpywl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtdtjksewg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuuqknuk.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigfzy.top/Article/details/gtvsfnkcgt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gtumwtxrij.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdjiyqms.html

[D20] 统计每个元素出现次数
来源：http://dali.wangdashe.top/Article/details/gtsbltcnxb.html

Py:   Counter(arr)
来源：http://dali.guannengcc.top/Article/details/gtmcsncgyy.html

PHP:  array_count_values($arr);
来源：http://dali.9152youxi.cn/Article/details/gtcuqvwfft.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtbrmnfmlh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtgvnkelne.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aibaodan.cn/Article/details/gtrhjadedg.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gtakqhohlz.html

Ruby: arr.tally
来源：http://dali.svipenyu.cn/Article/details/gtdbsdvhtx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgfzy.top/Article/details/gtpfzzwmuc.html

[D21] 判断是否包含某元素
来源：http://dali.cheryme.top/Article/details/gtsnexesbu.html

Py:   x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxflsydxx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dianchejie.cn/Article/details/gtqcyvlcmd.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtvsppqiwl.html

TS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtgxjepvcb.html

Java: list.contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtqqhumvon.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtsdxxddff.html

Ruby: arr.include?(x)
来源：http://dali.cucudq.cn/Article/details/gtdikpujsl.html

C#:   list.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtgjkyaiyj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pengpengdd.cyou/Article/details/gtmnhpjhiv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtwakjhdae.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cashguo.top/Article/details/gtibttlnkj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtqkjwyfmu.html

TS:   [...arr];
来源：http://dali.hnqzz.top/Article/details/gthpgyvpao.html

Java: new ArrayList<>(list);
来源：http://dali.sxryk.cn/Article/details/gtsobwqlpz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sweek.top/Article/details/gtgcdwkvgj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hammf.cn/Article/details/gtxmiliory.html

C#:   new List<int>(list);
来源：http://dali.zycfv.cn/Article/details/gtkilnnynq.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gtapqjwism.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gtsnjjufkr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtvkzrdzqb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtbrhceooa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gttpsixwwa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.redwolf501.top/Article/details/gtlpsiknpz.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtdhiaifkj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gtutiwyhdv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gtkwdjtawk.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gttbkenomx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guowangkeji.top/Article/details/gtfbxtoubl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtjzvnudcd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtgroyuvfq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtogfucdqi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gtcpouumnt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuanzx.com/Article/details/gttvsvjaph.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gturnmjdre.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gtllvooqjq.html

[D25] Set 集合去重与交并差
来源：http://dali.wangshuangyany.cn/Article/details/gtgzmwamqk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gtdhyxhhtq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gtqzbslwbo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gtcqpmxand.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuanzx.com/Article/details/gtwmlngjtp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhengqikj.top/Article/details/gtlztkfmzz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dashuyun.cn/Article/details/gtctohlxzt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yongpay.top/Article/details/gtayycguhx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gtxoctjzbq.html

[D26] 数组转字符串
来源：http://dali.nwbrower.top/Article/details/gtolgahgde.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cqqwz.cn/Article/details/gtninxtvex.html

PHP:  implode(", ", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtwxfwozlq.html

JS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtxmnysgaj.html

TS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtknvbbdly.html

Java: String.join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gtukxgpckx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yongpay.top/Article/details/gtfwlpvlig.html

Ruby: arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtgwxukunw.html

C#:   string.Join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtjlgweyxk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtolsfmgmx.html

E. 字符串处理
来源：http://dali.wangdashe.top/Article/details/gtpeyradmx.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtfywhbqsi.html

[E01] 拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtmcnvzwur.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aibaodan.cn/Article/details/gttyknsvfr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cashguo.top/Article/details/gtfoqcdnyc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtcvvwzjvr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gtygkqjooy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenzaomai.com/Article/details/gtsliobgiz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gtnxuxhocz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.feifeiyinyue.top/Article/details/gtgiefszdd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gtigzkykrc.html

[E02] 重复字符串
来源：http://dali.quarkkingdee.top/Article/details/gtaynhqtlp.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvvvvire.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnqzz.top/Article/details/gtbyumahga.html

JS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtggfzawgi.html

TS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsmnefmh.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gthbimzohu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtsrpjcxbe.html

Ruby: "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gtvwpbjqvx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.snrcjt.cn/Article/details/gtgknsmhwh.html

[E03] 截取子串
来源：http://dali.pycfn.com/Article/details/gtytxfhffb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtmiblelms.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtobatwlhm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtzhunmzer.html

TS:   s.slice(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtiizqysvg.html

Java: s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gthgfttvhj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shuidangran.top/Article/details/gtikjhmdmm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtbflgyuog.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gtdhzdducq.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gtxyfwbrze.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtjzyuxqzj.html

PHP:  strpos($s, "x");
来源：http://dali.xuanzx.com/Article/details/gtxodmlyay.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwzhmkkg.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtlqhkozdi.html

Java: s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtglxijepe.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gtdwyunzrn.html

Ruby: s.index("x")
来源：http://dali.jianghu66.top/Article/details/gthdofolcx.html

C#:   s.IndexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtdtbmdrhk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fengsongda.top/Article/details/gttdukyxxr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yuanzhike.top/Article/details/gtlzmgwmbf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pengpengdd.cyou/Article/details/gtyatqljsm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtovcwwigv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnxiangtu.top/Article/details/gtktuglosx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtxjekmhmc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pengpengdd.cyou/Article/details/gtjcotalqq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.kuanghao11.cn/Article/details/gtfnafiebl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtmdtzxdlt.html

[E06] 替换子串
来源：http://dali.wangdashe.top/Article/details/gtycgdvuyq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtlvjxuvsv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.wangdashe.top/Article/details/gteurjprha.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtbrclznxy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtjndbkejo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gttpuynshf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gtucjpozas.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtlnmyffxw.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtxiqptqlq.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gtsriopeqz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258888.top/Article/details/gtufxnwkwj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtyfczisrl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sxryk.cn/Article/details/gtvmbyaevn.html

TS:   s.split(",")
来源：http://dali.hysaishi.cn/Article/details/gtmxgnpvwy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gtemhgitei.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuxming.cn/Article/details/gtsayuopvm.html

Ruby: s.split(",");  s.split
来源：http://dali.tanke756.top/Article/details/gtcvtbtepk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shangyingyoupin.top/Article/details/gtakkthqke.html

[E08] 数组按分隔符合并
来源：http://dali.gzhubu.top/Article/details/gtivpqjzmo.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gtbkqskfsm.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gttnsbsatv.html

JS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gttqzsuuhk.html

TS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtgebazamk.html

Java: String.join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtvnoszmwr.html

Go:   strings.Join(items, ",")
来源：http://dali.zhengqikj.top/Article/details/gtvsdoiwxo.html

Ruby: items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gthdjywcdl.html

C#:   string.Join(",", items)
来源：http://dali.redwolf501.top/Article/details/gtdejgttnu.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gtxnbleqhj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xylfe.cn/Article/details/gtbvskrjpx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtmnqodsgf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtgrdohswv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gtvsrjfcxe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtulehhlvr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnxiangtu.top/Article/details/gtsfaskwik.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gtjlwluadz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlegolgvp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cqqwz.cn/Article/details/gtuglrncsn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gttgiwdztw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gttehtqznb.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcvurjki.html

TS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtpsgmuebi.html

Java: String.format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtoxayawpv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gthjfntvug.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtopnkvcxm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaukowfup.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gtxzrjjzsv.html

Py:   s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtbmpwzdbt.html

PHP:  strrev($s);
来源：http://dali.shuidangran.top/Article/details/gtkomtxxsp.html

JS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtymfzhseo.html

TS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkljrlge.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtldqdzdvb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gtpwfcuhmg.html

Ruby: s.reverse
来源：http://dali.shzxlz.cn/Article/details/gtrqwrwtfr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gtvhtuotfk.html

[E12] 统计某字符出现次数
来源：http://dali.ppjwa.cn/Article/details/gtkswklais.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gttyrdizbx.html

PHP:  substr_count($s, "a");
来源：http://dali.vqdsnc.cn/Article/details/gtgjbihjal.html

JS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtunlkbmou.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtjabaicsm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxinkj.top/Article/details/gtnqyuryhs.html

Go:   strings.Count(s, "a")
来源：http://dali.havefunace.top/Article/details/gtzsdxbxec.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtnnhysrtr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jyoumei.cn/Article/details/gticdriyef.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gtyhkpwqgt.html

Py:   for ch in s: print(ch)
来源：http://dali.bjfxy.top/Article/details/gtghneforh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gtuapjrocj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwppsecvg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtoigvfyab.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtembgpdlx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gtbqpmjgvs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jlsjyb.cn/Article/details/gtcjmadfqx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtypciwrxk.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gtfxtzlnjc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.redwolf501.top/Article/details/gtyzxmrmys.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtueugvrxd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.mhx1999.top/Article/details/gtrwuuurcs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ivvv.top/Article/details/gtwbtiecir.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gtgljvrfmm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gttibxlojx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.snrcjt.cn/Article/details/gtkgixyxgd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.316326.xyz/Article/details/gtefrauerj.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gtopprdonf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnxiangtu.top/Article/details/gtnqpmcjdj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.birdmap.top/Article/details/gtrctavjty.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jlsjyb.cn/Article/details/gtlxysoxnt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gtcjkqyqvh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jyoumei.cn/Article/details/gtpchhjfeh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gtypqemaht.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gtynhbiiol.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.vqdsnc.cn/Article/details/gtgrvxlwkp.html

[E16] 数字千分位
来源：http://dali.nanxinkj.top/Article/details/gtfntfcwvq.html

Py:   f"{1234567:,}"
来源：http://dali.dashuyun.cn/Article/details/gtphxunnhj.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gtdfxzgzcg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtampmccfw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtpbhnxenn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gtzhgpsspp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gtxhcpqapl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yueranfly.top/Article/details/gtfijoddwu.html

C#:   1234567.ToString("N0")
来源：http://dali.cheryme.top/Article/details/gtumzemlkn.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcepipdy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gtsuuzglki.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gtznhzorbz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtbgzdpcit.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtfxaouzsc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gttibvxffs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuanzhike.top/Article/details/gtiajjcitv.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtwtfeucno.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ybcxt.top/Article/details/gtwifazbny.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gtwtyzhntx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangtech.top/Article/details/gthadnelal.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hysaishi.cn/Article/details/gtercgjapu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gthzkfihta.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdheapdi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtgmeafzzt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtezhvfiyo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gtevsxqnqm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtgzfwvpsq.html

[E19] 多行文本按行拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjeknqopl.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gtoivirssa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtakjvzsvt.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtwnocusqi.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gthehxwqiy.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtxaehrdpn.html

Go:   strings.Split(s, "\n")
来源：http://dali.tian-w.cn/Article/details/gtdzuooppj.html


<!-- 参考信息 -->