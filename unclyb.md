代发 wailian999

[D15] 去重
来源：http://dali.yueranfly.top/Article/details/gtvzvvrjtr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtnvwvglup.html

PHP:  array_unique($arr);
来源：http://dali.zycfv.cn/Article/details/gtgqtfebim.html

JS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtctlftsvs.html

TS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtbyxxsfdk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.quarkkingdee.top/Article/details/gtukqjheob.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuanzx.com/Article/details/gtrpbwggwb.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gtwlgichqn.html

C#:   list.Distinct().ToList()
来源：http://dali.xylfe.cn/Article/details/gtqkskkfqg.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gtqqjnsepq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gtqnfwmwoa.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cashguo.top/Article/details/gtypqbslhp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtvtcdzacq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtgzzjzqyf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cqqwz.cn/Article/details/gtjmsqfmyy.html

Go:   // 手写循环累加
来源：http://dali.fzhhl.top/Article/details/gtoaufqtwi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtrwmtphxu.html

C#:   list.Sum();  list.Average()
来源：http://dali.dianchejie.cn/Article/details/gthzhgedgm.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gtcvxpxvhe.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtxpvizndc.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gtezggohjx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.meibo888.top/Article/details/gtvsgdnmrk.html

TS:   Math.max(...arr);
来源：http://dali.jinqigfzy.top/Article/details/gtmhcqbifx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.316326.xyz/Article/details/gtokswfaqn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.birdmap.top/Article/details/gtssefrwdc.html

Ruby: arr.max;  arr.min
来源：http://dali.andypj.xyz/Article/details/gtbcjrccrd.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangtech.top/Article/details/gtegyxohjg.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gtawtkrsjq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gthmybtnwy.html

PHP:  array_merge(...$nested);
来源：http://dali.yuanzhike.top/Article/details/gtyyvbkqeq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fzhhl.top/Article/details/gtunnnsgbc.html

TS:   nested.flat();
来源：http://dali.snrcjt.cn/Article/details/gtwkihhdeu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yvedp.cn/Article/details/gtfdydcgfp.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtcgmrfpcp.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gtgzokakgn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtnunxvxbe.html

[D19] 按字段分组
来源：http://dali.smart0.xyz/Article/details/gtrvlmphzu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pycfn.com/Article/details/gtkorpusvx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gtaekskgjb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gtlxplaryk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guowangkeji.top/Article/details/gtstkertwr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gzhubu.top/Article/details/gtaahqrqub.html

Go:   // 手写 map[string][]T
来源：http://dali.pengpengdd.cyou/Article/details/gtlukzamhn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gtbpdbmbae.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gtwvxrfwxm.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gtypeductk.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gtdxaobfls.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gtpkrrpgfh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gthgeaamoa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gthbtzjrxn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtyelxucqs.html

Go:   // 手写 map[T]int
来源：http://dali.yuxming.cn/Article/details/gtoegdvuud.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gtcrbnkvel.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gtnnsytpkn.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gtijupqktn.html

Py:   x in arr
来源：http://dali.ppjwa.cn/Article/details/gtudnhoahv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigfzy.top/Article/details/gtbudyqqat.html

JS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gthkibyypg.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtfxtehpru.html

Java: list.contains(x)
来源：http://dali.cashguo.top/Article/details/gtwerqidvl.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gtufwisnpb.html

Ruby: arr.include?(x)
来源：http://dali.tanke756.top/Article/details/gtxemnmfwp.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtjtulkiuc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gtvokvvygh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gtchzqzaes.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jlsjyb.cn/Article/details/gthhmxbrkp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gtwbmxvdnv.html

TS:   [...arr];
来源：http://dali.nwbrower.top/Article/details/gtesjubsez.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtezcmjyoy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigufen.top/Article/details/gthmltxoxb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guowangkeji.top/Article/details/gtgveoequm.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gtencafjtx.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gtrtxwxstw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gtjgfwipme.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtukxwfnow.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtwwxlliym.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtajyqdshg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guowangkeji.top/Article/details/gthhdxphkb.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtnkekhlyu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tianlin.xyz/Article/details/gtfvdmgzpp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pycfn.com/Article/details/gtaajfsgdp.html

[D24] 字典 / Map 基本操作
来源：http://dali.pycfn.com/Article/details/gtdvytrwhn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gtabojujel.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gtoyzxbtwt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnqzz.top/Article/details/gtncggytxe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtyffgdhqk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gtazrsifpx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.feifeiyinyue.top/Article/details/gtbqwifdqo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gtlmwepwoa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhixingplan.top/Article/details/gtzcentcix.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gtpnkgswlz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gtopfeopga.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gtcqgjlkgi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gtmwmorsiu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nwbrower.top/Article/details/gtkijmgldo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtyeammtlz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jlsjyb.cn/Article/details/gtxrbjtmjv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttydvfdcs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtgbfwcnbg.html

[D26] 数组转字符串
来源：http://dali.aizwys.cn/Article/details/gtmxxurnad.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtiixhplsc.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtknccqfmv.html

JS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtnohxpguk.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gthyfgzcag.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtvhfjbnbu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zycfv.cn/Article/details/gtfxggoqiz.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gthmcfbbam.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtptsmxuqr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwhcsnpfl.html

E. 字符串处理
来源：http://dali.xziqi.cn/Article/details/gturylwcfw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtljlypbze.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtrvqektmo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sysykeji.top/Article/details/gtqpwpitxy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jyoumei.cn/Article/details/gtzbklzqoj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtlvfdqehf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gtuzeyyfkj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gtmzqsvhkc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgzwmiwt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gtwlwerrci.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtyddmkhfa.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gtrwzmjaqd.html

Py:   "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gthiclnung.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cdnleiting.top/Article/details/gtfrkguqjh.html

JS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtrifpsouc.html

TS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtallqgexo.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtmgbiwbzf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtlntsdgbk.html

Ruby: "ab" * 3
来源：http://dali.hnqzz.top/Article/details/gtxvcyfihn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yueranfly.top/Article/details/gtuzpcbcwf.html

[E03] 截取子串
来源：http://dali.mhx1999.top/Article/details/gttubeigph.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nwbrower.top/Article/details/gtbndxeswu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gteljsrwbb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtuhmiquut.html

TS:   s.slice(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtnlgrawye.html

Java: s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gtothjyeyx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zycfv.cn/Article/details/gtifoicroq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gtwdjhjhcp.html

C#:   s.Substring(1, 3)
来源：http://dali.fengsongda.top/Article/details/gtrnpctrzz.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gtnnqtocka.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ivvv.top/Article/details/gtpnqxxopm.html

PHP:  strpos($s, "x");
来源：http://dali.yangfankeji.com/Article/details/gtytlenycy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnqzz.top/Article/details/gtkdbrjcfx.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtwofopggn.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtjaoyoqce.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gtysesjwqz.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbubwrsjf.html

C#:   s.IndexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtvhwpnglo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tian-w.cn/Article/details/gtufopmheq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ppjwa.cn/Article/details/gtsflwmkbx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nwbrower.top/Article/details/gtrroszxog.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtdpcoczzk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yanxiufei.cn/Article/details/gtapvfkmqe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtrdbmoomn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.birdmap.top/Article/details/gtcosvarqh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zycfv.cn/Article/details/gtusftsmiy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gttraditdu.html

[E06] 替换子串
来源：http://dali.jqgufenzy.top/Article/details/gtluamymyg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gtytdsuvtf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gtiwcnoibl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtgabduhev.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtzgwskroe.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtzjeitrrm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gtquuwxuvu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtrdkgjmeb.html

C#:   s.Replace("a", "b")
来源：http://dali.birdmap.top/Article/details/gteiyctpdo.html

[E07] 按分隔符拆分
来源：http://dali.iojbl.cn/Article/details/gtrlabhgoq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuccpyup.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtvupxahcp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphzttthc.html

TS:   s.split(",")
来源：http://dali.daxiang520.top/Article/details/gtbmaxirwm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gtwkrgkbxa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hfpthk.cn/Article/details/gthcmezeuf.html

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gtfjjvuwgx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gtsmyfbakb.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258888.top/Article/details/gtppbiuwoo.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gtinsyyfqm.html

PHP:  implode(",", $items);
来源：http://dali.aizwys.cn/Article/details/gtyvyjhvrg.html

JS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtgsohgbcw.html

TS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtbozppodz.html

Java: String.join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtkwxixymh.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gtjizdgtll.html

Ruby: items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtmqhrcjfh.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtkfpxhole.html

[E09] 去除所有空白字符
来源：http://dali.sweek.top/Article/details/gtftbbdqrq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xylfe.cn/Article/details/gtplgpvjrr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gtqaiafbvn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmsqylun.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gtpcryvqxa.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gthacdymiu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuanzhike.top/Article/details/gtdztzjsvp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.feifeiyinyue.top/Article/details/gttnffimlw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.redwolf501.top/Article/details/gtmyzrxvcw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzglbbmci.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtakvdoblq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sweek.top/Article/details/gtmaywgjdy.html

JS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtfsuivtie.html

TS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gthfotvvya.html

Java: String.format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtziqeeczu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtfvosezyd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtersbzvqr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dashuyun.cn/Article/details/gtdfymamaq.html

[E11] 反转字符串
来源：http://dali.cashguo.top/Article/details/gtvsrgorgq.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gtlgwiunpw.html

PHP:  strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtvrnbuugf.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtpvmmlajh.html

TS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtypzlcxql.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gtaweuimrl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fzhhl.top/Article/details/gtaknuufgx.html

Ruby: s.reverse
来源：http://dali.cdnleiting.top/Article/details/gtmujytmua.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gttexrmicm.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtgqlzrkax.html

Py:   s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gtypgidfll.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtjadzhiig.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtphymzjrr.html

TS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkbdkvpz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gzhubu.top/Article/details/gtlgjdscst.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gtjhxuhstl.html

Ruby: s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtueadarwx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ehwqpu.com/Article/details/gtigdzppuu.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gtixugioet.html

Py:   for ch in s: print(ch)
来源：http://dali.yonumen.top/Article/details/gtagensiri.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuanzhike.top/Article/details/gtjfdovube.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtpiqjrxat.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtodmlbzqs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtiucujkrz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkmybued.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangshuangyany.cn/Article/details/gtiesqften.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gteftbsspl.html

[E14] URL 编码与 Base64
来源：http://dali.andypj.xyz/Article/details/gtqdnaxmek.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gtxkroilfh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sweek.top/Article/details/gtpkqqkqzs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ybcxt.top/Article/details/gtcntqhxlt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gtizqgmnex.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtaqvncycn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhsjucjl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigfzy.top/Article/details/gtdklraqhr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gtjylybswu.html

[E15] HTML 转义 / 反转义
来源：http://dali.svipenyu.cn/Article/details/gtldxjpznx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gtidmdiyar.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hfpthk.cn/Article/details/gtfxmiemsx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gtbfbhcemg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xylfe.cn/Article/details/gtjekecozu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gtemavytag.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gthamvozgq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuanzx.com/Article/details/gttjsiofyk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gtvntyrzlm.html

[E16] 数字千分位
来源：http://dali.cashguo.top/Article/details/gtvrzgmkqj.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gttdjgatbm.html

PHP:  number_format(1234567);
来源：http://dali.chenzaomai.com/Article/details/gtemsjnixr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gtdwdbpzbm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gttoevckiz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gtcjghsxga.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xylfe.cn/Article/details/gttlaveoaw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gturwtlpgg.html

C#:   1234567.ToString("N0")
来源：http://dali.cheryme.top/Article/details/gtjtinldem.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gthorpfxgr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gtdspivqgp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gtswopmhjc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtwfznlvzh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtggmbjcay.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gtpjbuyqrz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gtwxmfcsjn.html

Ruby: s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gtekvbgsxb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenlongwang.top/Article/details/gtxridwgyb.html

[E18] 模板占位符替换
来源：http://dali.jyoumei.cn/Article/details/gtoiftpkkk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwukwdaxt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gtxlbwwtsm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gthkthcxqx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtuiccgxbd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtdjikgici.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.316326.xyz/Article/details/gtphucvkda.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgufenzy.top/Article/details/gttvckuhzo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gtibtanemh.html

[E19] 多行文本按行拆分
来源：http://dali.cqqwz.cn/Article/details/gtiwvwwbfk.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gtrmktburn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtpmaxzpxw.html

JS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtotglwetp.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbeiedean.html

Java: s.lines().toList()
来源：http://dali.wangdashe.top/Article/details/gtjnnwbhit.html

Go:   strings.Split(s, "\n")
来源：http://dali.xinyue.icu/Article/details/gtgvoiwolf.html

Ruby: s.lines
来源：http://dali.ydzc1.top/Article/details/gtzzopgrpo.html

C#:   s.Split('\n')
来源：http://dali.gotoacloud.top/Article/details/gtusixqsna.html

[E20] 判断字符串是否为空
来源：http://dali.daria6918.cn/Article/details/gtfyjovbbf.html

Py:   if not s:
来源：http://dali.jinqigfzy.top/Article/details/gtqszshevs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gtqtzveulv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.vqdsnc.cn/Article/details/gtlgvmracp.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gtmbrweumj.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtbtcclafm.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gtcnehblpt.html

Ruby: if s.empty?
来源：http://dali.iojbl.cn/Article/details/gttutbrmbq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yonumen.top/Article/details/gtmoxdufhy.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gtztvjelzk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yonumen.top/Article/details/gtqmguulzq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtbnoktlkd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtfbnvsqhc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtzbitogba.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtdgogyxtz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shzxlz.cn/Article/details/gtwuejeojg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtohawjnsd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtoksuhcix.html


<!-- 参考信息 -->