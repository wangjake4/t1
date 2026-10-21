代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ydzc1.top/Article/details/gtagmukiit.html

C#:   list.Sum();  list.Average()
来源：http://dali.haohaochexian.top/Article/details/gtqtrwqvbp.html

[D17] 最大值与最小值
来源：http://dali.yueranfly.top/Article/details/gtpaklgyww.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtkfgufshm.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gtzyqbczvn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cucudq.cn/Article/details/gtuqduqhdi.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gtehovkxek.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gtlupmywss.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtkijnulxl.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gtagefroqy.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gtbbjaqddi.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gtxawnkxiw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sweek.top/Article/details/gtlojldabv.html

PHP:  array_merge(...$nested);
来源：http://dali.zhongyouzk.top/Article/details/gtmrgnrtjb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jiagoushi.top/Article/details/gtifdvzgbn.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gtqidliisf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258888.top/Article/details/gtjcyubule.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gtwchasacb.html

Ruby: nested.flatten
来源：http://dali.guowangkeji.top/Article/details/gtdzwrtypx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gtaxkndzpm.html

[D19] 按字段分组
来源：http://dali.hnqzz.top/Article/details/gtckdnwydb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gtmlztfihi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sufxvd.cn/Article/details/gtsmzebmnc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gtpewychgq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gtwgudugox.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shzxlz.cn/Article/details/gtcktudzbs.html

Go:   // 手写 map[string][]T
来源：http://dali.mhx1999.top/Article/details/gtegsyfkmo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnxiangtu.top/Article/details/gtefozoqwz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.svipenyu.cn/Article/details/gtyojsdsjx.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gtianxlcso.html

Py:   Counter(arr)
来源：http://dali.yuxming.cn/Article/details/gtrtcuikmk.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtafbejwfy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gthefycewk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtivtolgol.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hywenlv.cn/Article/details/gtlczfltoq.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gtkdlbvkqw.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gtjiebqduw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gaohongyu789.top/Article/details/gtwklqcdzn.html

[D21] 判断是否包含某元素
来源：http://dali.haohaochexian.top/Article/details/gtoqsmnvfc.html

Py:   x in arr
来源：http://dali.guowangkeji.top/Article/details/gthqxfufyk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yanxiufei.cn/Article/details/gtojfxpopa.html

JS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gtudbszljj.html

TS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtcxgwillg.html

Java: list.contains(x)
来源：http://dali.wangdashe.top/Article/details/gtgrgtvwng.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gthiqkczxz.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtpdiofxjb.html

C#:   list.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtviowbeww.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jianghu66.top/Article/details/gtzexoqwru.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tianlin.xyz/Article/details/gtdzsngclq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gthtcfamtl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cucudq.cn/Article/details/gttyiynebt.html

TS:   [...arr];
来源：http://dali.xylfe.cn/Article/details/gtxfxtdcpz.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvbnvpfe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gthfqfarwl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.haohaochexian.top/Article/details/gtllvbnuey.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtyqunjeps.html

[D23] reduce 累积计算
来源：http://dali.zhengqikj.top/Article/details/gthktiklod.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.meibo888.top/Article/details/gtlvolnybs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gtilyxzwqs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gtknklempf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjbrnjvx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gthathdwsd.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtjhjhpqjq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gtcdstfume.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gtdmnccvth.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gtnqfetvlp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gtvriybrtf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.kuanghao11.cn/Article/details/gtefszidan.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zycfv.cn/Article/details/gtdpihqxun.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtjtrwfidm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ybcxt.top/Article/details/gtdrhrqsea.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gtyhwqttxk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnxiangtu.top/Article/details/gtemeajlcv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gtozykpzgc.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gtnqlcttoh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxuanxn.top/Article/details/gtyamligtf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zycfv.cn/Article/details/gtzzjpmuhr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tanke756.top/Article/details/gtqqsyypxr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ydzc1.top/Article/details/gtjsqhvftx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gtvqbkpssy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.snrcjt.cn/Article/details/gtlbuilfza.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yangfankeji.com/Article/details/gtzvzeutnc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtpikfuokw.html

[D26] 数组转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwdqwfsw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shzxlz.cn/Article/details/gtrqkaakac.html

PHP:  implode(", ", $arr);
来源：http://dali.hammf.cn/Article/details/gtniihrnfb.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtxenjfeas.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtraicrndo.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtvtajfwjx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.quarkkingdee.top/Article/details/gtvkkhmuub.html

Ruby: arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtyhoiqplf.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtqqxvcnyj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtjthdbrbv.html

E. 字符串处理
来源：http://dali.pycfn.com/Article/details/gtoocikvnh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvdhxfmp.html

[E01] 拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtwuhdvknz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gtyrgnllnk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gthhqglzae.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gtwlxofrjv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtqcuuignv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgfzy.top/Article/details/gtwzrtzlfh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangdashe.top/Article/details/gtkpsgwvlv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tian-w.cn/Article/details/gtucuclptf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtverbvrav.html

[E02] 重复字符串
来源：http://dali.tanke756.top/Article/details/gttdabafdj.html

Py:   "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtenstznfz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqwcvkji.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtfwqibzvm.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gttrddpyxh.html

Java: "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtaxzcxwgf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cqqwz.cn/Article/details/gtclqtqunj.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtaiuhwuss.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258.top/Article/details/gtexokvspa.html

[E03] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtbmtrqtgn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gtwhujfdyq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtbkrhtetp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhqyhxdh.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtabdlepvj.html

Java: s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtaqbtjhct.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevuuboxu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gtzfpzduss.html

C#:   s.Substring(1, 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtluflluxy.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gtqdfccrby.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtkxpygsyq.html

PHP:  strpos($s, "x");
来源：http://dali.9152youxi.cn/Article/details/gtwtzwcovj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gtyczftytd.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gteicyenbm.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gtffsjycuv.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gtgzlblhez.html

Ruby: s.index("x")
来源：http://dali.fengsongda.top/Article/details/gtiqvssrnr.html

C#:   s.IndexOf("x")
来源：http://dali.meibo888.top/Article/details/gtyidfhnqr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.feifeiyinyue.top/Article/details/gtxvwhwdkl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gthbhnrzry.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gtqwyvqtzl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtbowooksp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aibaodan.cn/Article/details/gtgxzrygkv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtoturgpzl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gtpihkebrp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdahzfcis.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtvfbhnqgh.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gtnlbxvcxd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtwxokqjiv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxinkj.top/Article/details/gtqcqzvkme.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlakefftm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtexczhbzr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtiadgiamb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gttjxhfdsy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtummsjquu.html

C#:   s.Replace("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtubofdrgs.html

[E07] 按分隔符拆分
来源：http://dali.yj202588.top/Article/details/gtkgiksvck.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aizwys.cn/Article/details/gtarvbxwgy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.meibo888.top/Article/details/gtpqknyujp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gtzprahoiq.html

TS:   s.split(",")
来源：http://dali.c1oappe.top/Article/details/gtjpefxwwa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jiagoushi.top/Article/details/gthnbzkdro.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zdqjudy.top/Article/details/gtpqqytohs.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gtuojkdxva.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gtzyelsxyl.html

[E08] 数组按分隔符合并
来源：http://dali.ybcxt.top/Article/details/gtftwmjoxw.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gtnrbmcxrp.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gtqqasxalk.html

JS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtkdhqucgo.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtjxyqcntt.html

Java: String.join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gttvnirejm.html

Go:   strings.Join(items, ",")
来源：http://dali.ppjwa.cn/Article/details/gtcoynzqac.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gteizctwtm.html

C#:   string.Join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gturwsibew.html

[E09] 去除所有空白字符
来源：http://dali.svipenyu.cn/Article/details/gttkyoulam.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gtbhiaabqs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.iojbl.cn/Article/details/gtejjinaae.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gtsdimmanr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtplftjovj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtgqjittqc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtzgonhjhd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gtwnlvovhm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihcrbnwv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gteknwdpjf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gtibqmuqet.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.kuanghao11.cn/Article/details/gtthezyehk.html

JS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtmgldutmh.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtndtbscar.html

Java: String.format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtusdnwyjt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtigomerkn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtoosflhvb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gtxetxnpur.html

[E11] 反转字符串
来源：http://dali.hysaishi.cn/Article/details/gtqbnntfdm.html

Py:   s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtfgbafvfn.html

PHP:  strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtyxkbtycl.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gttysbufnw.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtqtdolamd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.bjfxy.top/Article/details/gtfjaxuztj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtjfptwklq.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtiqycedzv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gttuuywxff.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gtidlzyywq.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtpozfuvzt.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gtfpgcmmqi.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtqovzlniz.html

TS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gtknfmevfz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigfzy.top/Article/details/gtimcnqozo.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gteflcwnqy.html

Ruby: s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtioqozilp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.mhx1999.top/Article/details/gtwhlzbped.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnwmxnvh.html

Py:   for ch in s: print(ch)
来源：http://dali.cqqwz.cn/Article/details/gtgcekiosn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gtfdupsths.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtmpqnrjbo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gtvwutvqhs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtaxhjuvyj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtlwnowojh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gtlvmyfksl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtzxdncsvp.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtxembklkr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gtcuzivewx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtgckcowvg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yongpay.top/Article/details/gtbqxumewh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtwrcldbwa.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtrwxaaajv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gtyanaprou.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yongpay.top/Article/details/gttmwrcdjg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtwsywyeql.html

[E15] HTML 转义 / 反转义
来源：http://dali.shuidangran.top/Article/details/gtzucqcdoj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ppjwa.cn/Article/details/gtzziyqhri.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hywenlv.cn/Article/details/gtkcluepqa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.snrcjt.cn/Article/details/gtoidyepdt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtsfjrwraf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gtayxywsqa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gteykmzeaj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gtftmfdrhv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sufxvd.cn/Article/details/gtrnitzowm.html

[E16] 数字千分位
来源：http://dali.nanxinkj.top/Article/details/gtoqgcefyh.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigfzy.top/Article/details/gtwiuambbw.html

PHP:  number_format(1234567);
来源：http://dali.hongshengwenyu.top/Article/details/gtxtlbswft.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtqnertdan.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gthmrzzjtd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtlixnstcy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gtvltnwcow.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daria6918.cn/Article/details/gtcdzmouju.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtwdcotrog.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gtpgmrhouk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gtwdggoubl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ehwqpu.com/Article/details/gtbbrhvprv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtybskhpgi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtgnokrlfg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gtmuczevor.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gtscunqcyk.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtczsvqwqo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gtrnvvnujf.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtnwvfof.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgufenzy.top/Article/details/gtgdpvjoxl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jiagoushi.top/Article/details/gtdauwdbpd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtfzijvdim.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtujkzijxy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtnvzzkxkq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtjsddpneo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ivvv.top/Article/details/gtrrmgptzt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gtuopqtxwa.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gtjuxtxmad.html

Py:   s.splitlines()
来源：http://dali.gaohongyu789.top/Article/details/gtcyeijhwd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtrndujjwp.html

JS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gtkxtcnxnd.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gtlzibfjhu.html

Java: s.lines().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtczwowpku.html

Go:   strings.Split(s, "\n")
来源：http://dali.ppjwa.cn/Article/details/gtuuwgmiub.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gttidmybwk.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gtjnuvpshe.html

[E20] 判断字符串是否为空
来源：http://dali.zdqjudy.top/Article/details/gtrxupgszk.html

Py:   if not s:
来源：http://dali.fengsongda.top/Article/details/gtugkwaxix.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gtzzauzpkb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gtpdkboipy.html

TS:   if (s === "") {}
来源：http://dali.redwolf501.top/Article/details/gtpgtkvzho.html

Java: if (s.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gtvxshnpaz.html

Go:   if s == "" {}
来源：http://dali.hysaishi.cn/Article/details/gtenjcsnbp.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gtjjrrewnp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ydzc1.top/Article/details/gtvztqjskd.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfwebkwn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tian-w.cn/Article/details/gtamcxepbj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtowivhbng.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomjiiyai.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtwytcioot.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gthzldrded.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gtgiruoxht.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtbqgqqgsi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtnnnsohqv.html

[E22] 字节长度与字符长度
来源：http://dali.ppjwa.cn/Article/details/gtofssoebn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gtgfnssfuh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtecflklzl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtmnrlrvof.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtifvazvgz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtftaupggw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gtoeerzqne.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gtynoaomtc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.smart0.xyz/Article/details/gtbiajbvrj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtkfxcuwmo.html

F. 文件与目录
来源：http://dali.yueranfly.top/Article/details/gtdaygpias.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtnnhbgkxd.html

[F01] 读取整个文件
来源：http://dali.hywenlv.cn/Article/details/gtnbrbypld.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinghuilouyu.cn/Article/details/gtioymnfyw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtjkxqraou.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gtrcjsodub.html


<!-- 参考信息 -->