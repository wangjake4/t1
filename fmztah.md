代发 wailian999

[D19] 按字段分组
来源：http://dali.zycfv.cn/Article/details/gttwkdgmzg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxinkj.top/Article/details/gtjjmnpjqc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gogol.net.cn/Article/details/gtpcrprrxk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkydkizq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtgelvtwpa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuanzhike.top/Article/details/gthbeysugt.html

Go:   // 手写 map[string][]T
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsmxwpbb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xziqi.cn/Article/details/gtutzzwvun.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtuzvdqjxi.html

[D20] 统计每个元素出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtfjuymaxg.html

Py:   Counter(arr)
来源：http://dali.tanke756.top/Article/details/gtjczchiro.html

PHP:  array_count_values($arr);
来源：http://dali.daria6918.cn/Article/details/gtoweunaoe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtgtlqsxgs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtdtfyazsj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gtmddaqyer.html

Go:   // 手写 map[T]int
来源：http://dali.chenlongwang.top/Article/details/gtmmwmndna.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gtlumuzkdz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258.top/Article/details/gtzsuxsgtg.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gtsbaysalf.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gtjhwhudew.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gtosvjxxhy.html

JS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtempblwsl.html

TS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtuhtzausa.html

Java: list.contains(x)
来源：http://dali.yuxming.cn/Article/details/gtwllcfaku.html

Go:   slices.Contains(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtpugfmwbh.html

Ruby: arr.include?(x)
来源：http://dali.tanke756.top/Article/details/gtcwidfmln.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gtayrysszx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.kuanghao11.cn/Article/details/gtqkrtuedy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.c1oappe.top/Article/details/gtlbvcrwrb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ppjwa.cn/Article/details/gtpsttrlai.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwkdeuuz.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gtrpnbnshl.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gtbueugyzb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gtkcsvdgik.html

Ruby: arr.dup;  arr.clone
来源：http://dali.andypj.xyz/Article/details/gtqqdheqqk.html

C#:   new List<int>(list);
来源：http://dali.bjfxy.top/Article/details/gtpjmxfeho.html

[D23] reduce 累积计算
来源：http://dali.316326.xyz/Article/details/gtfzgdclij.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cqqwz.cn/Article/details/gtrkxwfmsq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gtojbyehgf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtlxmtlorx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtfyzlbvre.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shzxlz.cn/Article/details/gtsfzybvki.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtmnwfzadr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyhjfsro.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhiwuduotai.top/Article/details/gtldnfmsxy.html

[D24] 字典 / Map 基本操作
来源：http://dali.yongpay.top/Article/details/gtislehgef.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigfzy.top/Article/details/gtrhxkxlzc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fengsongda.top/Article/details/gtwchxward.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yvedp.cn/Article/details/gtelbefhqr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtvtbqxjne.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhoulong.xyz/Article/details/gtaksuwqtc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.andypj.xyz/Article/details/gtbctahhwi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tian-w.cn/Article/details/gtbelkmbur.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gtembcdyhe.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gtmoqjhvzx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gtycryllnm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.iojbl.cn/Article/details/gtavzhmiaq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xziqi.cn/Article/details/gtcirefwxz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aibaodan.cn/Article/details/gtyjzuviwn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fengsongda.top/Article/details/gtiuxtvadw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daxiang520.top/Article/details/gtetgunini.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gtfunptfrg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daria6918.cn/Article/details/gtzjcptkvu.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gtbyppdmio.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jianghu66.top/Article/details/gtghgntzhf.html

PHP:  implode(", ", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtplecwphb.html

JS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtpnykcdnp.html

TS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtzflaeyrn.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtgizdwqll.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jianghu66.top/Article/details/gtfchkprof.html

Ruby: arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtndkkgmqm.html

C#:   string.Join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtejjzlorn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdqegynmm.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gtaqtflrhq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtwaewjrrn.html

[E01] 拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtkgxnjibz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dianchejie.cn/Article/details/gtfwnrqzco.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gtwzieeoqr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gtaoppvyqj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtvpkquomf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxuanxn.top/Article/details/gtlxaakxxf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gtpdpadmaj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gthxrfmiqc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtnfgfqtin.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gthmewbjru.html

Py:   "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtadwtznjs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigufen.top/Article/details/gtaoxlzoss.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtcwgfmuow.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtkailnlgm.html

Java: "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtlxyhbsyx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aibaodan.cn/Article/details/gtfizxjqav.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbvqqtwz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgfzy.top/Article/details/gtdmomthpj.html

[E03] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtndynmvbw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigfzy.top/Article/details/gtldljrfsa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtflnnxavq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gthueuxgml.html

TS:   s.slice(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtickdxuph.html

Java: s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtnwheeeot.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtoielrivw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwoxfstpy.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gttvtvicvg.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gtbmrhcpoz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gtlkitueic.html

PHP:  strpos($s, "x");
来源：http://dali.wangdashe.top/Article/details/gtlzaecyok.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gthpadlezg.html

TS:   s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtrsbqfhto.html

Java: s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtfcjzpaay.html

Go:   strings.Index(s, "x")
来源：http://dali.svipenyu.cn/Article/details/gtvxatlcra.html

Ruby: s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtesgycmmk.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gtcwufjxfk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuanzx.com/Article/details/gtldzelthc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtnwreaedq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xylfe.cn/Article/details/gtzsejhugj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gttvhfkksf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yanxiufei.cn/Article/details/gtnspfmmib.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtumrginhp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.feifeiyinyue.top/Article/details/gtxnqtsxbu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gtwgudpxit.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtbckodkxy.html

[E06] 替换子串
来源：http://dali.jqgfzy.top/Article/details/gtojmhinmf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtawfhsjrz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yonumen.top/Article/details/gtozxedoho.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtsjzklizj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqdzvyzl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtzlcdsjhf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtliikfcib.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtslzkhgsw.html

C#:   s.Replace("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtyisharzk.html

[E07] 按分隔符拆分
来源：http://dali.zdqjudy.top/Article/details/gtjycckjgu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jiagoushi.top/Article/details/gtcfozsrpv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtsypgopog.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258.top/Article/details/gtyymdmyny.html

TS:   s.split(",")
来源：http://dali.mhx1999.top/Article/details/gternwnavl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jiagoushi.top/Article/details/gtdnhnvmdx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtflxippyx.html

Ruby: s.split(",");  s.split
来源：http://dali.fengsongda.top/Article/details/gtoubryacn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawbcwwdd.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gtmwtpyrdl.html

Py:   ",".join(items)
来源：http://dali.hysaishi.cn/Article/details/gtzdcxejoo.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gtiyfuaajm.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtlczhtbfk.html

TS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtzmenpmey.html

Java: String.join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtnmbmkmau.html

Go:   strings.Join(items, ",")
来源：http://dali.chenlongwang.top/Article/details/gtglgharlm.html

Ruby: items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtqsjkxaio.html

C#:   string.Join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gttnbrqobm.html

[E09] 去除所有空白字符
来源：http://dali.redwolf501.top/Article/details/gtjjygmlln.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gtegjwmuae.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yueranfly.top/Article/details/gtrqigimod.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtyepgcycs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtiratilpb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtsmyhsnly.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xylfe.cn/Article/details/gtrwvakasm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dianchejie.cn/Article/details/gtyqkjwmbr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtrcmwspvk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuanzx.com/Article/details/gtxfpnegva.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuruagmu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.snrcjt.cn/Article/details/gtbckyzcsw.html

JS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtktuozbnw.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gthhmetjhs.html

Java: String.format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gthnoiwpmh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gttqjoetwe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gttftkurnm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gtvpoumwum.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gticnoafbu.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtqnlxinot.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtaahxgewf.html

JS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gttfadgqhq.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtjwsoonks.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nwbrower.top/Article/details/gtjgdpkcfk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gtavfnuiok.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtbhcrznif.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtkcqnvrbp.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gtmonjaejl.html

Py:   s.count("a")
来源：http://dali.hnqzz.top/Article/details/gttfwvbkib.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gtqbucgdie.html

JS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtmulgxdrp.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtnknrqvcs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gtbmikdfei.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gtznavhzva.html

Ruby: s.count("a")
来源：http://dali.ivvv.top/Article/details/gttrtvboef.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gtngqmpfgv.html

[E13] 逐字符遍历
来源：http://dali.gaohongyu789.top/Article/details/gtkmxpfdlp.html

Py:   for ch in s: print(ch)
来源：http://dali.daria6918.cn/Article/details/gtpnxzndei.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tian-w.cn/Article/details/gtnouyorww.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtxrsyiwdq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtimmjtzng.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtcdxhdhwk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yanxiufei.cn/Article/details/gthvsgvwcg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jianghu66.top/Article/details/gtturpxzwn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtqwippzxm.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoljjfmvk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gttfmgkhtx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuanzx.com/Article/details/gtlrdljqnd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gtujvymhiv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigfzy.top/Article/details/gtiwerxyiu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ivvv.top/Article/details/gttjizgmto.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgfzy.top/Article/details/gtkhjflyfo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gtcozdgdaa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xinyue.icu/Article/details/gtikgghhpr.html

[E15] HTML 转义 / 反转义
来源：http://dali.c1oappe.top/Article/details/gtxnqyugux.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxuanxn.top/Article/details/gtatzbbexk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gtvvogvnmz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gtgyvuplfg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gtwspaspjq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gtdzafuowp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztoiekwc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gtihhyatji.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gtetnsvabm.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gtlnijotny.html

Py:   f"{1234567:,}"
来源：http://dali.wangdashe.top/Article/details/gtckkzygmn.html

PHP:  number_format(1234567);
来源：http://dali.xinyue.icu/Article/details/gtegnfsere.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtzdlaampa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtqvyyhppu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gtbwyydouo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthycwbmrm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gtzwtopeat.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gtszqhamue.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gtwplqhjuk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypufcdwl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbvgmcvg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtlnagtgql.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gtwykqpgav.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gtcropsyjj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gtsoitmftl.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gtdbooyisn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gtjdginfzv.html

[E18] 模板占位符替换
来源：http://dali.vqdsnc.cn/Article/details/gtcakwqypk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangdashe.top/Article/details/gtatlsdawx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gteampglhp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtmipyzcdv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtnwwwohlr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtyzmusijo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfstuzur.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gtrzgbmrod.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgufenzy.top/Article/details/gtihztflkw.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258.top/Article/details/gtquihfode.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gtyvnnzalg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.havefunace.top/Article/details/gtladvemoz.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtglvehcrc.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtfmaqjblq.html

Java: s.lines().toList()
来源：http://dali.guannengcc.top/Article/details/gtfszljurp.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhoulong.xyz/Article/details/gtqfoijvxd.html

Ruby: s.lines
来源：http://dali.svipenyu.cn/Article/details/gtebcacirx.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gtkeaubzja.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gtipymyjnu.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmuojxar.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gtfprihefv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shzxlz.cn/Article/details/gtdrnrrjsp.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gtdttcknwc.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtiqbeaygf.html

Go:   if s == "" {}
来源：http://dali.pengpengdd.cyou/Article/details/gtprgogupn.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gtsivtslwv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtyacwysib.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gtoaigiqhq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gtlfkihcqw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtxarvmval.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmumapca.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtlzcdvqsh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprhoamdg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gtifsljdwe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtlperrztk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtuiqrqtxv.html

[E22] 字节长度与字符长度
来源：http://dali.pengpengdd.cyou/Article/details/gtfwmjatye.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gtemrplhxy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtebtgehxr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtmnienudr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtarsrqfqd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258888.top/Article/details/gtouxuiyrm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gtwnyvpfsv.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtrtzbbgvh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daria6918.cn/Article/details/gtqrzalcer.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtofidbhir.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gtvewepopx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkaiiophi.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gtieupfghd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gtqrdovjhg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtditnyghe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shzxlz.cn/Article/details/gtawuonuol.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gttojnncbi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtxaqpzsop.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gtimqucfba.html

Ruby: File.read("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gttjyfkjuk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtgyrvjelz.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gtrqwvncvp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj202588.top/Article/details/gtkgdemegn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jyoumei.cn/Article/details/gtfvptqteg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gteixrncot.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gttszvored.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtmxbwfuwz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gttgoekqie.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gtegsxnxpe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cashguo.top/Article/details/gtcdntuvxr.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gtmvofboao.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zdqjudy.top/Article/details/gtnptcnhlz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtxleccyga.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtrwyqwtob.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyswxihqd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gtmzxsbaim.html


<!-- 参考信息 -->