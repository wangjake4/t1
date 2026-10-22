代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gthjoqompg.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtqgkjkbth.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtbtwfmbuq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.birdmap.top/Article/details/gtgvhzygjs.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gtdpngldle.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gtxhxnuhrb.html

PHP:  array_unique($arr);
来源：http://dali.xuanzx.com/Article/details/gtxvlofrhm.html

JS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gttqupxsjj.html

TS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtohufmlqa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jyoumei.cn/Article/details/gtuogxvffx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zycfv.cn/Article/details/gthwqithsi.html

Ruby: arr.uniq
来源：http://dali.sweek.top/Article/details/gtovoztxht.html

C#:   list.Distinct().ToList()
来源：http://dali.hysaishi.cn/Article/details/gtiiapbshs.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gtffwjyteq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtkmnkeamx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtefenrojd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtzmmajega.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtzyjrrjde.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cqqwz.cn/Article/details/gtzygjfgle.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangtech.top/Article/details/gtszsfples.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gtkwusmubs.html

C#:   list.Sum();  list.Average()
来源：http://dali.jlsjyb.cn/Article/details/gtbsxrgati.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gthylfcmbs.html

Py:   max(arr);  min(arr)
来源：http://dali.zhengqikj.top/Article/details/gtlyzyoclf.html

PHP:  max($arr);  min($arr);
来源：http://dali.andypj.xyz/Article/details/gtkrgmpijo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gtqfxyxrfe.html

TS:   Math.max(...arr);
来源：http://dali.zhixingplan.top/Article/details/gtinonizxm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.c1oappe.top/Article/details/gtywcsotqi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.svipenyu.cn/Article/details/gtuzyqmqxp.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtkedwnavc.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gtzvlbagvy.html

[D18] 扁平化嵌套数组
来源：http://dali.xuetiantiany.cn/Article/details/gttzigkdgt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnkmwxqo.html

PHP:  array_merge(...$nested);
来源：http://dali.yangfankeji.com/Article/details/gtvkuyrfvm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gtfcpxeqid.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gtojfqogjy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hfpthk.cn/Article/details/gtpwdrkpvt.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfvputnz.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gtiuzrwiav.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtrnzwomoy.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gtpvzpxhln.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtaitujera.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hywenlv.cn/Article/details/gtuuaatysu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jqgufenzy.top/Article/details/gteqvgaqie.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gtjmqcbdwf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xinyue.icu/Article/details/gtlmfoewrk.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gttjhxthnt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shuidangran.top/Article/details/gtofnaubmi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gtakhfycfj.html

[D20] 统计每个元素出现次数
来源：http://dali.ivvv.top/Article/details/gtkrcqfssu.html

Py:   Counter(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtyzxqsfcy.html

PHP:  array_count_values($arr);
来源：http://dali.daria6918.cn/Article/details/gtxeeuylrc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gttlccvhdy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gtezqxgjmi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.snrcjt.cn/Article/details/gtvsuddbjh.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gthirraaic.html

Ruby: arr.tally
来源：http://dali.jlsjyb.cn/Article/details/gthqinsafi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgfzy.top/Article/details/gtmtlxroev.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazffhvcy.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtybxssyny.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fengsongda.top/Article/details/gtnqambrdu.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtmxuwxqzm.html

TS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtinbdzsir.html

Java: list.contains(x)
来源：http://dali.yvedp.cn/Article/details/gtstcmkfcf.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtulmapnwo.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtgmjlggfj.html

C#:   list.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtpwarxrin.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yvedp.cn/Article/details/gtljwtlepp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aibaodan.cn/Article/details/gtpkwaclio.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.c1oappe.top/Article/details/gtujesypeo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gtvbjsjykq.html

TS:   [...arr];
来源：http://dali.9152youxi.cn/Article/details/gtgznixrre.html

Java: new ArrayList<>(list);
来源：http://dali.ppjwa.cn/Article/details/gthjpqlofa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gtefzsmvjs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvrkmiau.html

C#:   new List<int>(list);
来源：http://dali.jqgfzy.top/Article/details/gtkafbnqyh.html

[D23] reduce 累积计算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjxxcffq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtzqmyxkcb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gtfeluslnh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtbqamckoh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gtpjvrhpvs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gtxfpimdsm.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtypkjueib.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgfzy.top/Article/details/gtugcwucpr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gtkbdgkgvg.html

[D24] 字典 / Map 基本操作
来源：http://dali.hywenlv.cn/Article/details/gtkljxejki.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hammf.cn/Article/details/gtazonjejh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gtzxvgvzyz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gtfoxugidl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtmvjsbohu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gtdkxtfhgu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hammf.cn/Article/details/gtmwypnxha.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gtygnrkgla.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gtohfdlcco.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgfzy.top/Article/details/gtwmcidhwu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gtzhwgyfun.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gtntivegjj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gtvgwtxvtd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhengqikj.top/Article/details/gtuahfgnyx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtoecopqbc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gtebinppgg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gtgdgtvubo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtufbyvvhb.html

[D26] 数组转字符串
来源：http://dali.yuanzhike.top/Article/details/gtsuoatvex.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzrpxqna.html

PHP:  implode(", ", $arr);
来源：http://dali.xziqi.cn/Article/details/gtopdctsbc.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtrvknjygm.html

TS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtjpwnfypp.html

Java: String.join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gtyyibenxj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtquqczufz.html

Ruby: arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtjhpovtyl.html

C#:   string.Join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtshbhmktj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtiwlrubfi.html

E. 字符串处理
来源：http://dali.gotoacloud.top/Article/details/gtxuogfwlb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtotazhdes.html

[E01] 拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtyqvhbgyu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gtovsxweyy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shzxlz.cn/Article/details/gtmpfzgvpg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtphrlfoou.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqaoaqwi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gtzdalgzjv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ybcxt.top/Article/details/gtlxedlqgr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cdnleiting.top/Article/details/gtbcnxabqe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtfqdzspqp.html

[E02] 重复字符串
来源：http://dali.tanke756.top/Article/details/gtlgkiqjsc.html

Py:   "ab" * 3
来源：http://dali.sweek.top/Article/details/gtnwdryqcg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.snrcjt.cn/Article/details/gtosygvaea.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtscpvgbuh.html

TS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtzwjcuaoz.html

Java: "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtujagdhzt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gtdhxbugne.html

Ruby: "ab" * 3
来源：http://dali.316326.xyz/Article/details/gtjhftfnzt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gtlexclcnf.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtuuzlotew.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gtorlwhrpg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtwwsozmcy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtcvzbaanh.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gttryiklyh.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtndywrujj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gteulcxnfx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shuidangran.top/Article/details/gtemoflewc.html

C#:   s.Substring(1, 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnihqfao.html

[E04] 查找子串位置
来源：http://dali.vqdsnc.cn/Article/details/gtmcbffqla.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtmcnpwnzb.html

PHP:  strpos($s, "x");
来源：http://dali.jiagoushi.top/Article/details/gtlpycyeie.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.havefunace.top/Article/details/gtdfrtahbx.html

TS:   s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtfweftekn.html

Java: s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtlgdxqnwc.html

Go:   strings.Index(s, "x")
来源：http://dali.guannengcc.top/Article/details/gtkkjdirve.html

Ruby: s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtzmhjsfsn.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtljfjwcvi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gtqcawflcp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtmmcyfyrd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guowangkeji.top/Article/details/gthcovvwug.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtrohrobxt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yueranfly.top/Article/details/gtnzhhombj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtvqxdvzrl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigufen.top/Article/details/gtwrtcgpsv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gtwxwobhei.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtouebqsvo.html

[E06] 替换子串
来源：http://dali.feifeiyinyue.top/Article/details/gtodsitoor.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepbyhseq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtaptwsvxb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtuagxjhqk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtixlszenn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirxwqexv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtenbirsqi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pycfn.com/Article/details/gtmowkggwy.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gtbzfkobwp.html

[E07] 按分隔符拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtrlcbedcn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangshuangyany.cn/Article/details/gtswuptspv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtrnzosupf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ehwqpu.com/Article/details/gtywejvyzv.html

TS:   s.split(",")
来源：http://dali.ppjwa.cn/Article/details/gtkxweceno.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gtlviowcbb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ydzc1.top/Article/details/gtckqalnqz.html

Ruby: s.split(",");  s.split
来源：http://dali.ydzc1.top/Article/details/gtssqdoeff.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gtpmkjynhx.html

[E08] 数组按分隔符合并
来源：http://dali.wangdashe.top/Article/details/gthyvzqghi.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gtlyonowcj.html

PHP:  implode(",", $items);
来源：http://dali.aibaodan.cn/Article/details/gtmwlhnmdc.html

JS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtntqmoeyu.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtzcoantgp.html

Java: String.join(",", items)
来源：http://dali.havefunace.top/Article/details/gtvllzficc.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gtgpighkvd.html

Ruby: items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtmaoejtto.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gtbzlassqj.html

[E09] 去除所有空白字符
来源：http://dali.yanxiufei.cn/Article/details/gtgeetyppz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hammf.cn/Article/details/gtvgsxwlbc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.0kj1m.cn/Article/details/gtayhuxhez.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gtxduobkrp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gtylutqvbr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guannengcc.top/Article/details/gthxafwwdz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gtbeydgxxu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cdnleiting.top/Article/details/gtvmzyptbz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gtvslgxqww.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gtvkaofyxg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtixqdtgvi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgfzy.top/Article/details/gtcpscvjvh.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtcdojhhsl.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtpejinkra.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtbikstoju.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gthqwldwdo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gttmtdrdyd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gtgojwhihi.html

[E11] 反转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtokcnrvlt.html

Py:   s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtpbcyxyyb.html

PHP:  strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtwruzrvqv.html

JS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtdqintedg.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtkfhhtsxs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gtxqvtzcod.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tian-w.cn/Article/details/gthsxnouwk.html

Ruby: s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlcayrbb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gtdpxydmmr.html

[E12] 统计某字符出现次数
来源：http://dali.hfpthk.cn/Article/details/gtacsmqkqt.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvcksvvp.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gtuexemvjx.html

JS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtyxpbomnd.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtyxzjofav.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gtzxormemv.html

Go:   strings.Count(s, "a")
来源：http://dali.iojbl.cn/Article/details/gtuhcywhpk.html

Ruby: s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtoaxquktg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinghuilouyu.cn/Article/details/gtjujiezty.html

[E13] 逐字符遍历
来源：http://dali.xinyue.icu/Article/details/gtysjapdax.html

Py:   for ch in s: print(ch)
来源：http://dali.zdqjudy.top/Article/details/gtdxijqnwk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258.top/Article/details/gtbredqndw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtzvpwnwxv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngxcxboj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtzpjxrjcw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gtnrchduft.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.snrcjt.cn/Article/details/gtivtafuna.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtijvntdgf.html

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gtudxhqwut.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.kuanghao11.cn/Article/details/gtzbhvnwyp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gtjicemfqa.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gotoacloud.top/Article/details/gtthaxojaa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gtdgepbfqp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwmjkwvh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gtvxesstto.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nwbrower.top/Article/details/gtqgfwizbs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.bjfxy.top/Article/details/gtvntxzscv.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gthbmxqipd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gtlxizqctr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gtrfhxtlzy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gtmgzoclwa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gtewkqpsqx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sxryk.cn/Article/details/gtjpugktaw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnqzz.top/Article/details/gtnckraaan.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjghmzlov.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.haohaochexian.top/Article/details/gtygobnmja.html

[E16] 数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gtnwwsckia.html

Py:   f"{1234567:,}"
来源：http://dali.hywenlv.cn/Article/details/gtmijqxsri.html

PHP:  number_format(1234567);
来源：http://dali.jyoumei.cn/Article/details/gtezvednkz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtcrykxkwu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrmstsuy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkknklyi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgufenzy.top/Article/details/gtutgrtmpc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gtdsvqqbqi.html

C#:   1234567.ToString("N0")
来源：http://dali.aibaodan.cn/Article/details/gthqprqmfv.html

[E17] 首字母大写
来源：http://dali.gzhubu.top/Article/details/gtyjmohbib.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gthsengxzv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gtqpseqdmi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtxnyexleq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtzkacamya.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gtpcpoordm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hywenlv.cn/Article/details/gtqbtfeijw.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gtsjvoyzgc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sysykeji.top/Article/details/gtzuxwkala.html

[E18] 模板占位符替换
来源：http://dali.gzhubu.top/Article/details/gtuqhetebb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuoapdkm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnygibep.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtewcoezdk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtegvrxrys.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtfuhwwray.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtqfiihvad.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmcfradm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gtnepkymyk.html

[E19] 多行文本按行拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutncswjm.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gtejrzreya.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daxiang520.top/Article/details/gtjonfnpgs.html

JS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtsphgwvoh.html

TS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gtwtgyfouv.html

Java: s.lines().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtyycikuhu.html

Go:   strings.Split(s, "\n")
来源：http://dali.dashuyun.cn/Article/details/gtpwsjjfxn.html

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gtlquuzrcy.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gttlhkqiav.html

[E20] 判断字符串是否为空
来源：http://dali.smart0.xyz/Article/details/gtsfsbcndz.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gtlcyizjyk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gtxaeaquix.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgubzveyc.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gtgemqfviy.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtpudjsrjt.html

Go:   if s == "" {}
来源：http://dali.wangdashe.top/Article/details/gtdtpcqoqw.html

Ruby: if s.empty?
来源：http://dali.mhx1999.top/Article/details/gtmiwopgph.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ydzc1.top/Article/details/gtmngwuobu.html

[E21] 超长截断加省略号
来源：http://dali.jqgfzy.top/Article/details/gtdtnvfuzo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzrbditk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gthayditey.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtokiuarlp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtvrsmxfwm.html


<!-- 参考信息 -->