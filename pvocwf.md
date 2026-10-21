代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gtekbscbmm.html

C#:   list.Sum();  list.Average()
来源：http://dali.aizwys.cn/Article/details/gtfdbgrgjn.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gtslgbrawk.html

Py:   max(arr);  min(arr)
来源：http://dali.hnqzz.top/Article/details/gtacwcfwjf.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsuwgcqy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gtessflytv.html

TS:   Math.max(...arr);
来源：http://dali.jinqigfzy.top/Article/details/gtcoluilce.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogwjhqsl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtvecerylg.html

Ruby: arr.max;  arr.min
来源：http://dali.zycfv.cn/Article/details/gtdauolnfv.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gtquvizgkq.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gtrwixfwyg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.havefunace.top/Article/details/gtglapnxwc.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gtmbrrmhud.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yanxiufei.cn/Article/details/gtnhnewzrj.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gtlnarpdbv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.mhx1999.top/Article/details/gtxcgqhfiq.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gtavghcike.html

Ruby: nested.flatten
来源：http://dali.jqgfzy.top/Article/details/gttuvirgyw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtcwalnfif.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gtcgnxjvac.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gtyztvlifb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhiwuduotai.top/Article/details/gtgbtonotx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gteyvznwep.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtwodvgqcd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjfcohav.html

Go:   // 手写 map[string][]T
来源：http://dali.andypj.xyz/Article/details/gtdltfnufv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gtwzvhbtrk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gthrfgbmyk.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gtdqntnqbk.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gtpxfygobq.html

PHP:  array_count_values($arr);
来源：http://dali.daria6918.cn/Article/details/gtgnlqltvf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtlxlfwgjb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gtjtsbbtnh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gzhubu.top/Article/details/gtrnliyfrx.html

Go:   // 手写 map[T]int
来源：http://dali.nanxinkj.top/Article/details/gtwtibwycw.html

Ruby: arr.tally
来源：http://dali.fzhhl.top/Article/details/gtustmrzvd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gtpwildrif.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxhxlzps.html

Py:   x in arr
来源：http://dali.sysykeji.top/Article/details/gtblqzexfc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhongyouzk.top/Article/details/gtfitwfgop.html

JS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gtvzrwueuf.html

TS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtbnyprond.html

Java: list.contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtibhykrqy.html

Go:   slices.Contains(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtegnsrwjt.html

Ruby: arr.include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtndbyxgrn.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtpkbptkan.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pengpengdd.cyou/Article/details/gtfohdhwgo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sysykeji.top/Article/details/gtcusrhdwf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxinkj.top/Article/details/gtexljrtll.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zdqjudy.top/Article/details/gtkmqlcoyj.html

TS:   [...arr];
来源：http://dali.yueranfly.top/Article/details/gtdoyhbrmj.html

Java: new ArrayList<>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtzwxzpwva.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gtdzkerkqw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.andypj.xyz/Article/details/gtyeaisbur.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtughimjmc.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gtnklztdli.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuxming.cn/Article/details/gtdzvzjwhn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gtfhfdjjni.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtdrczydik.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gthkymzdxr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gtqfcjirwd.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtynbdhcim.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jyoumei.cn/Article/details/gtehqfqeue.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gtkmkxorcf.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhoulong.xyz/Article/details/gthqgbgvzd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtydmmuzit.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gtgphypzha.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aizwys.cn/Article/details/gtbruemlbi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtfrdcdtkd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxinkj.top/Article/details/gtbjdsmmtw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gtdvsxibes.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daria6918.cn/Article/details/gtmssrvjcb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.kuanghao11.cn/Article/details/gtavhoqyme.html

[D25] Set 集合去重与交并差
来源：http://dali.0kj1m.cn/Article/details/gtaspallwd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.birdmap.top/Article/details/gtacgizgbb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtrkjnwlcr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yueranfly.top/Article/details/gtvdxwdykq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hfpthk.cn/Article/details/gtugcuendm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gtevdxfngp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258888.top/Article/details/gtufodiyhg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtivibmrtg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gttmkoapik.html

[D26] 数组转字符串
来源：http://dali.yuanzhike.top/Article/details/gtufpywais.html

Py:   ", ".join(map(str, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtdshyyopo.html

PHP:  implode(", ", $arr);
来源：http://dali.iojbl.cn/Article/details/gtsfphfhij.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzedshohe.html

TS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gteinijotm.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtepgmydau.html

Go:   strings.Join(strs, ", ")
来源：http://dali.vqdsnc.cn/Article/details/gtakrxyrtc.html

Ruby: arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtpnrtuepb.html

C#:   string.Join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotvjgbfk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtjukioutc.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gtticcbeci.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gttvzsbacw.html

[E01] 拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtgaejywse.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gtekyaqbhj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gtfybqlryb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtssnduppy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtnqrijtta.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.c1oappe.top/Article/details/gtbsokwhuv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daxiang520.top/Article/details/gtwcctkepg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.vqdsnc.cn/Article/details/gttitlwapr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtgrdrdvcy.html

[E02] 重复字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtgxdiqsjp.html

Py:   "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gtcsqpflti.html

PHP:  str_repeat("ab", 3);
来源：http://dali.redwolf501.top/Article/details/gttwjofwwy.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtmdbzfmmb.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtutsxuhgx.html

Java: "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtvdubobpp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gtwmalbkps.html

Ruby: "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gtoobjhphy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigufen.top/Article/details/gtqmbdhpzp.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gttcicbjic.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yvedp.cn/Article/details/gtejxwqfqo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtxbtvwoyy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtoelgfnfc.html

TS:   s.slice(1, 4)
来源：http://dali.ivvv.top/Article/details/gtyblnymzo.html

Java: s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtpbcewsba.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.c1oappe.top/Article/details/gthhyjkkrl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gtbznnrovh.html

C#:   s.Substring(1, 3)
来源：http://dali.yj202588.top/Article/details/gthycrylox.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gtleeebqiz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuanzx.com/Article/details/gtzkgzpfba.html

PHP:  strpos($s, "x");
来源：http://dali.shangyingyoupin.top/Article/details/gtcbqczmkw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.bjfxy.top/Article/details/gthbzdepfz.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtnvctvesg.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtxungkwhy.html

Go:   strings.Index(s, "x")
来源：http://dali.yuxming.cn/Article/details/gtjwhgymiq.html

Ruby: s.index("x")
来源：http://dali.yj20258.top/Article/details/gthqbnmmdj.html

C#:   s.IndexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtxbsrhshx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gttiqzfvbo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtlruqmbmr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.bjfxy.top/Article/details/gtejssdeax.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtppwvxhpy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.mhx1999.top/Article/details/gtymotcqdq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtmijflcmp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yvedp.cn/Article/details/gtzylsgdam.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gogol.net.cn/Article/details/gtxljzwzeg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcppbdjes.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gtnszirqwh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtglcsqwip.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cqqwz.cn/Article/details/gtzoqicnsn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpjwgqdc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gteedgezuu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtrsumxbzh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtqsqespzq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtozgbaury.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtaejetwhw.html

[E07] 按分隔符拆分
来源：http://dali.9152youxi.cn/Article/details/gtfgbexyfz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pycfn.com/Article/details/gttfxlmxij.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtvxmnrslh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigufen.top/Article/details/gturcixxbz.html

TS:   s.split(",")
来源：http://dali.nwbrower.top/Article/details/gtomifktpe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xziqi.cn/Article/details/gtjltfhwqm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gotoacloud.top/Article/details/gtvfunrlom.html

Ruby: s.split(",");  s.split
来源：http://dali.bjfxy.top/Article/details/gtmelnpbro.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gtvsehpeay.html

[E08] 数组按分隔符合并
来源：http://dali.iojbl.cn/Article/details/gtrfgbbaup.html

Py:   ",".join(items)
来源：http://dali.jiagoushi.top/Article/details/gtatphvomg.html

PHP:  implode(",", $items);
来源：http://dali.bjfxy.top/Article/details/gtulcrsarz.html

JS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtrrnilzpe.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtnlqezsib.html

Java: String.join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gtwjnwrwyb.html

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gtxdmbbcjq.html

Ruby: items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtzmkpxcox.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gthrhdhmjz.html

[E09] 去除所有空白字符
来源：http://dali.hnqzz.top/Article/details/gtclkagcdm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gtnkmiiiun.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnqzz.top/Article/details/gtmzarsiag.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gtlboflpfg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtolndbpbr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtpuefyudq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dashuyun.cn/Article/details/gtnaelkcun.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.kuanghao11.cn/Article/details/gtlbchmzau.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gtudvuyrpc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtfmrvnrph.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtsgpzfcjc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guannengcc.top/Article/details/gtbezdjgth.html

JS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtrtotntbs.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtxaofmzqk.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtpyrsjxru.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtgyfyfget.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtwqfhforx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guowangkeji.top/Article/details/gtseivnxpj.html

[E11] 反转字符串
来源：http://dali.guannengcc.top/Article/details/gtjstkvyfy.html

Py:   s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtfcvlnhhd.html

PHP:  strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtvabuhlef.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtpprlvuwd.html

TS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtxapoaeou.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtahqfmhwb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtwpzlievg.html

Ruby: s.reverse
来源：http://dali.tian-w.cn/Article/details/gtsgmqrgon.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtzbnjqgum.html

[E12] 统计某字符出现次数
来源：http://dali.fengsongda.top/Article/details/gtngrizujt.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtalzcykcx.html

PHP:  substr_count($s, "a");
来源：http://dali.snrcjt.cn/Article/details/gtwjymeuit.html

JS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtkegzfdto.html

TS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnqnjrmi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ybcxt.top/Article/details/gtinxzmsor.html

Go:   strings.Count(s, "a")
来源：http://dali.xziqi.cn/Article/details/gtmbreioxg.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gtdggpwvqg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenjidiqi.icu/Article/details/gtqsgxstwb.html

[E13] 逐字符遍历
来源：http://dali.pycfn.com/Article/details/gteksxslhi.html

Py:   for ch in s: print(ch)
来源：http://dali.dianchejie.cn/Article/details/gtwlxlmdrn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gtqaeuspbx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtngcwryyp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtxppaojyt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtvfvhdrli.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.vqdsnc.cn/Article/details/gtrotyzmyr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gttvfwupvi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gzhubu.top/Article/details/gtnagtqzcn.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gtndbrtndb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxlkdxbz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtcbocinqu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenlongwang.top/Article/details/gtxybyohps.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzddysrx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tanke756.top/Article/details/gtlogpergz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gtwhggohnq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gtegevefks.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gtjmqxriho.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gtmodanfhj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gtyvtuvumw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtfircukom.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gtixjhjdfc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daxiang520.top/Article/details/gtqbkusizp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gtlzttfkph.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ydzc1.top/Article/details/gtvjrshyjm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gtjcrahoef.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cucudq.cn/Article/details/gtajqlyicu.html

[E16] 数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gtdxcohrev.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtqrsbnwgs.html

PHP:  number_format(1234567);
来源：http://dali.hammf.cn/Article/details/gtwpzszlxx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gtcemndxss.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtyfyapuyb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gtjjvcpyxy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gtgvmxwqpi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gtrqncokcm.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuuwfjtz.html

[E17] 首字母大写
来源：http://dali.cheryme.top/Article/details/gtdcucvghu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtjlgtkmdz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gtqceoglky.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtlomrarla.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jiagoushi.top/Article/details/gtywzsxvhz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gtkrhbltcc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ydzc1.top/Article/details/gtxgxbibfa.html

Ruby: s.capitalize
来源：http://dali.mhx1999.top/Article/details/gtapaxtqmu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gtfkfzpttt.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjgmkbgg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.iojbl.cn/Article/details/gtxdwloxhc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gotoacloud.top/Article/details/gtcwfvdkjm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtjlyykpcx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gttcuswccr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtrbiexmlf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtuhyfnyfa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gogol.net.cn/Article/details/gtirqjjhfc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shangyingyoupin.top/Article/details/gtmhzflwzh.html

[E19] 多行文本按行拆分
来源：http://dali.yueranfly.top/Article/details/gtmmfdkyiq.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gtisqhycig.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cheryme.top/Article/details/gtxxrlapll.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtqqdjrhya.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybzolswu.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gtqynfbbne.html

Go:   strings.Split(s, "\n")
来源：http://dali.tianlin.xyz/Article/details/gtxyiqhokv.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtyexyhdnr.html

C#:   s.Split('\n')
来源：http://dali.yj202588.top/Article/details/gtfidnkbig.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gtsxmrkpfr.html

Py:   if not s:
来源：http://dali.pengpengdd.cyou/Article/details/gtunclauue.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gticvyiksq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ivvv.top/Article/details/gtplxnqqqj.html

TS:   if (s === "") {}
来源：http://dali.xziqi.cn/Article/details/gtnkhppmfg.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtbfkkrmgh.html

Go:   if s == "" {}
来源：http://dali.cdnleiting.top/Article/details/gtgwwyrdlj.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gteomaaauq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258.top/Article/details/gthoifjtkr.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gtlnjvkeom.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gtspbfvggf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtguhlqlkj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gthjnolqga.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtwknkfern.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtobicsthp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaulhghrf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtncwpjyei.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtelyhhxtr.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gtknzidnac.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gtewykevkc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtxemnnvpu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtulqobfuv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtywxuvkbc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gtdlqxxrzo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gtademypxw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gthgbrdejc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhsdtflf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtzjlmmkmx.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsqqwcdx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtwxtpaefo.html

[F01] 读取整个文件
来源：http://dali.iojbl.cn/Article/details/gtoqtotfra.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gtzfurpyvs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaierdwze.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtcnfupk.html


<!-- 参考信息 -->