代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jyoumei.cn/Article/details/gtrhcpxzzv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtqpihkquf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtkuobcmdk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtcifxvlcz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gtoelywwoj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aizwys.cn/Article/details/gtjilvfovo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zycfv.cn/Article/details/gtutwkihzr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gaohongyu789.top/Article/details/gttdzxwprw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gtwevbotdu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprhoaubr.html

JS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtcvvenwqx.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtotvbjdzj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xinyue.icu/Article/details/gtxxavpakb.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtgosdtnpe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj20258.top/Article/details/gtmqpsjmnk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesohdggi.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtxtxxlwhw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtubcfqkjs.html

PHP:  array_unique($arr);
来源：http://dali.yongpay.top/Article/details/gteflaryyl.html

JS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gtszhxyvhg.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtcacbiejz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yangfankeji.com/Article/details/gtgxkwezlb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsuxboavx.html

Ruby: arr.uniq
来源：http://dali.svipenyu.cn/Article/details/gtybxdqtbr.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gtpehfvqyv.html

[D16] 求和与平均值
来源：http://dali.shzxlz.cn/Article/details/gtkmdmvrnv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sweek.top/Article/details/gtunipfihz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtvfegfdbz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gtoqjeiwzp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gtfztoeivs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gaohongyu789.top/Article/details/gtygmnapcm.html

Go:   // 手写循环累加
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwetoujre.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gteftyedvy.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gtjqhcrfdp.html

[D17] 最大值与最小值
来源：http://dali.c1oappe.top/Article/details/gtovpswoay.html

Py:   max(arr);  min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtyfbrfmzt.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gtodbzfdbo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gtbviafxck.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gtsbhanxcx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yongpay.top/Article/details/gtcxowbduq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gttiihmohl.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gtcggfplfg.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gtgrnwovrm.html

[D18] 扁平化嵌套数组
来源：http://dali.dashuyun.cn/Article/details/gttizwirxv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gtxwdfbdiq.html

PHP:  array_merge(...$nested);
来源：http://dali.bjfxy.top/Article/details/gttuybujhw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhengqikj.top/Article/details/gthcfhfzhr.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpeujqabz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gtwjnsyhph.html

Go:   // 手写双层循环
来源：http://dali.guannengcc.top/Article/details/gtnddxnmlr.html

Ruby: nested.flatten
来源：http://dali.wangdashe.top/Article/details/gthzwpttsy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gtgdrzcdga.html

[D19] 按字段分组
来源：http://dali.xinyue.icu/Article/details/gtsjxgiswp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtognufbbo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cucudq.cn/Article/details/gterlrxwla.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gzhubu.top/Article/details/gtnowskvuq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtulbdlrko.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gtotnfwwfr.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gtvjsyvvdt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gtgpwnfzrt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj202588.top/Article/details/gtfuafgoze.html

[D20] 统计每个元素出现次数
来源：http://dali.sysykeji.top/Article/details/gtcppbkfyw.html

Py:   Counter(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtengypdhp.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gtfkafrjyn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtbfjakzqo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gteyzpcbdh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.quarkkingdee.top/Article/details/gtvtpqlhgg.html

Go:   // 手写 map[T]int
来源：http://dali.tian-w.cn/Article/details/gtphczuvfk.html

Ruby: arr.tally
来源：http://dali.zhixingplan.top/Article/details/gtvithervu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gthxyazqmn.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gtnhgyengw.html

Py:   x in arr
来源：http://dali.jqgufenzy.top/Article/details/gtqipuwfjl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhengqikj.top/Article/details/gtbeqanirw.html

JS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtuvptohaq.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtsglwcpzr.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtpjfwpymq.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtgaqipjim.html

Ruby: arr.include?(x)
来源：http://dali.sxryk.cn/Article/details/gtscmgvrzt.html

C#:   list.Contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtotijxwdc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gtvnfqdvsc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gttyiazyay.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gteapwddyd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yongpay.top/Article/details/gtzjkawhrj.html

TS:   [...arr];
来源：http://dali.nwbrower.top/Article/details/gtuciqmkxb.html

Java: new ArrayList<>(list);
来源：http://dali.ppjwa.cn/Article/details/gthfgamgqe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnqzz.top/Article/details/gtmniizdor.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gtfgtgjhwh.html

C#:   new List<int>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtazyrijsd.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gtazavwuil.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cqqwz.cn/Article/details/gtvzzukusz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtogsmuq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtkerqtmyz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gtrfxalulr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gtznsbwqfz.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtfzeptehv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gtjvxiysyq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ivvv.top/Article/details/gtfrptipui.html

[D24] 字典 / Map 基本操作
来源：http://dali.pengpengdd.cyou/Article/details/gtpnmhljfi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zycfv.cn/Article/details/gtbpkrgtrr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhengqikj.top/Article/details/gtvvurntdy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccosutvn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtqzzrnxbt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzulrgjkx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.birdmap.top/Article/details/gtuzikbwrs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gtkpoetbth.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gtbhpnyppp.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gtwiyrxhns.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuetiantiany.cn/Article/details/gtyqqqphvi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jyoumei.cn/Article/details/gtolzhbvem.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgfzy.top/Article/details/gtldlvnlbb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gtehbwijmh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gtovqgnlre.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj202588.top/Article/details/gtemjkkdln.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xylfe.cn/Article/details/gtojqlhale.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.smart0.xyz/Article/details/gtwgtknxpi.html

[D26] 数组转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtpkstvrst.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cucudq.cn/Article/details/gtmcfsaznu.html

PHP:  implode(", ", $arr);
来源：http://dali.cucudq.cn/Article/details/gtvvsyapqk.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtrpmogldc.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtxhhyzzmt.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtmclrifin.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gtvsncmqer.html

Ruby: arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtenhduzaw.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtujbtucbt.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gthjqqlavt.html

E. 字符串处理
来源：http://dali.guannengcc.top/Article/details/gtutbaoajp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtoieipzes.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmezlsgkr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yongpay.top/Article/details/gtiwqnpkiz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guowangkeji.top/Article/details/gtkfwydcam.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gtxfusukft.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtisakyvwc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gzhubu.top/Article/details/gtbhnqmzac.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtopvtguwj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxqzgper.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.birdmap.top/Article/details/gtwgrfnibs.html

[E02] 重复字符串
来源：http://dali.sxryk.cn/Article/details/gtjkvojwpo.html

Py:   "ab" * 3
来源：http://dali.yonumen.top/Article/details/gtpzfgabwj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gtiaukkmqi.html

JS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gtrspdsjiu.html

TS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiubgxcx.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtusjyrdto.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gthpdmvixx.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtmhobfuul.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhongyouzk.top/Article/details/gtzlbleool.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtjobletas.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gtdtrarhey.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtouvfqylz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtvzxngnwb.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvriqsneu.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtrnrlssoe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gtdiawfupl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgfzy.top/Article/details/gtrvpbcqeb.html

C#:   s.Substring(1, 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtjokyhele.html

[E04] 查找子串位置
来源：http://dali.guannengcc.top/Article/details/gtihvuprnm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxszffrbr.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gtshlcfphl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj202588.top/Article/details/gtagzkrrds.html

TS:   s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtguwdvdzu.html

Java: s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtoupmxdqs.html

Go:   strings.Index(s, "x")
来源：http://dali.bjfxy.top/Article/details/gtsvarungo.html

Ruby: s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtpqhdfpqn.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258.top/Article/details/gtiytevahg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gtkhpempvq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtskbruhcy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gtxallfxqx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gtznawczac.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgaelebk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtwavfwluo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tanke756.top/Article/details/gtlzknxboj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtowlrenjf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yonumen.top/Article/details/gtnfwxruuy.html

[E06] 替换子串
来源：http://dali.haohaochexian.top/Article/details/gtbntwdrsf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gtebuzoofo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gtauucbcwr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtfaleetya.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtyxhawmrj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteamwcmiq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yongpay.top/Article/details/gtbnbbmhii.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.meibo888.top/Article/details/gtzkymvfgl.html

C#:   s.Replace("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gthmbiiosm.html

[E07] 按分隔符拆分
来源：http://dali.ydzc1.top/Article/details/gtuubzdror.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gthelmhoux.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtmigxyitr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yvedp.cn/Article/details/gtwxfbzvla.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gtphuvrfkb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnqzz.top/Article/details/gtdfdbujgs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gthpulchxb.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gtppkafkoy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jlsjyb.cn/Article/details/gtciznpmph.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gtdvhovvgp.html

Py:   ",".join(items)
来源：http://dali.0kj1m.cn/Article/details/gtskqqbgds.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbchjfqch.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtuxsapsve.html

TS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtrjnjcahl.html

Java: String.join(",", items)
来源：http://dali.xziqi.cn/Article/details/gtumrsxkcs.html

Go:   strings.Join(items, ",")
来源：http://dali.quarkkingdee.top/Article/details/gtpiytlnvl.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gtszdmoejs.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtowhzntet.html

[E09] 去除所有空白字符
来源：http://dali.pycfn.com/Article/details/gtfnwjavqa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gtisqtmoei.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gtgzznstvj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtziljrlnj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gtuuzwsxlm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtesgtbpnc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hongshengwenyu.top/Article/details/gtnvcvrmsb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tian-w.cn/Article/details/gtprqhkpfm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258888.top/Article/details/gtppswkoyg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tian-w.cn/Article/details/gtfnuqkfok.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gttlmygpfb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gtblbyrdrf.html

JS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtvaolizfs.html

TS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtjqxyppwb.html

Java: String.format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtcmxnbndx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtjtxzymfw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtyimzguqn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.vqdsnc.cn/Article/details/gtnqfwhxbx.html

[E11] 反转字符串
来源：http://dali.zycfv.cn/Article/details/gtbaycteuv.html

Py:   s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtwdcbwnxg.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gtquthdekh.html

JS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtossswjuj.html

TS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtfmxjbgaq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gtgqxsztjy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtytpwmahl.html

Ruby: s.reverse
来源：http://dali.tian-w.cn/Article/details/gtexberiit.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtneeajmsh.html

[E12] 统计某字符出现次数
来源：http://dali.hysaishi.cn/Article/details/gtemcpwrvu.html

Py:   s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtajtsoovv.html

PHP:  substr_count($s, "a");
来源：http://dali.gzhubu.top/Article/details/gtyykcxrhb.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtxhrfksbp.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gteerpttje.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyqvkkij.html

Go:   strings.Count(s, "a")
来源：http://dali.cucudq.cn/Article/details/gtiwyaorbm.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gthajnfzcn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.quarkkingdee.top/Article/details/gteyhzplvj.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gtvyrqtzie.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gtvygrxsyf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jlsjyb.cn/Article/details/gtinjxwsjq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjyyeqkk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gtcznxaqhn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gtvkqbxvzm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gtkyomyjll.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgufenzy.top/Article/details/gtwklciehf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtywxetnvk.html

[E14] URL 编码与 Base64
来源：http://dali.yonumen.top/Article/details/gtodtkjqlc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jiagoushi.top/Article/details/gtxeckjjyf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gtarltqupl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gtwbiuexqe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gtexudohsy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtkvciurdl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pycfn.com/Article/details/gtjnqymoyp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gtsglysgbd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtedtedtxt.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gtgjcufyir.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gtbyzenbfh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjtfxbur.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tanke756.top/Article/details/gtrwlljrsh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shuidangran.top/Article/details/gtnncgtjxm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.redwolf501.top/Article/details/gtdowcrxic.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtycrkiwqu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gtodcnacex.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258.top/Article/details/gtvrbywkms.html

[E16] 数字千分位
来源：http://dali.hnqzz.top/Article/details/gtiexamnvb.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gtpaagvznw.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gtnoggsaxc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtocwywqzm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtlkjinpki.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtueampurt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhengqikj.top/Article/details/gtprkbnkuz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sufxvd.cn/Article/details/gtldovatzt.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gtxnopikcf.html

[E17] 首字母大写
来源：http://dali.zhixingplan.top/Article/details/gttdfktolj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sxryk.cn/Article/details/gtfgvjvrkn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtrdmjouiv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzqdylcv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtficyaarf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzelgcmq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtnkmsqqgi.html

Ruby: s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gtdpbzfuur.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gtncfynnbf.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gttbtecgux.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyiznrbeb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hysaishi.cn/Article/details/gtctngyzxj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtzlcahkzj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gthlqpphxm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtlyoaxnts.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtsptfsuvm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.mhx1999.top/Article/details/gtokpyntej.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ydzc1.top/Article/details/gtujahglyw.html

[E19] 多行文本按行拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtneldmafs.html

Py:   s.splitlines()
来源：http://dali.ppjwa.cn/Article/details/gtfhjvvjtm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtotuyxfgd.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtqsdloxjh.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gtzvcyvetg.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gtcjagzhvo.html

Go:   strings.Split(s, "\n")
来源：http://dali.fzhhl.top/Article/details/gtsmunwkey.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gtwwnlyppp.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gtpcyovgzx.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhlyokpw.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gtmvyvwugk.html


<!-- 参考信息 -->