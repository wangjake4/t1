代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.meibo888.top/Article/details/gt2twoxlhhf.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gt2qwxnnkrd.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gt2bofsmzjg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2fdnwwgef.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gt2hyyszkww.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zycfv.cn/Article/details/gt2bqukbpih.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tanke756.top/Article/details/gt2owdrbwfr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gt2ltfebysb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gt2rjjdaxto.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gt2qsigcpnv.html

Go:   // 手写 map[string][]T
来源：http://dali.xziqi.cn/Article/details/gt2lbqppmai.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jlsjyb.cn/Article/details/gt2cehexjsa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gt2hxlarcic.html

[D20] 统计每个元素出现次数
来源：http://dali.andypj.xyz/Article/details/gt2nzkkqoni.html

Py:   Counter(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2iiiilvcc.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gt2sxwpwlih.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gt2bgbkekwp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gt2rcacyqdg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhoulong.xyz/Article/details/gt2owmrpaif.html

Go:   // 手写 map[T]int
来源：http://dali.sxryk.cn/Article/details/gt2wlewdxen.html

Ruby: arr.tally
来源：http://dali.tanke756.top/Article/details/gt2jmxefjnu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gt2ewsjyduq.html

[D21] 判断是否包含某元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfszlhuy.html

Py:   x in arr
来源：http://dali.zdqjudy.top/Article/details/gt2pffiydgt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tanke756.top/Article/details/gt2ieoljlej.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gt2jaxtthff.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqxvvgz.html

Java: list.contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2dcbfkaje.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2tcvufxjh.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gt2urryowiz.html

C#:   list.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlxilppc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gt2raegonit.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gt2hcheraay.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xinyue.icu/Article/details/gt2kxhupcmg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.316326.xyz/Article/details/gt2lxwwxadh.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gt2fsxmwnva.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gt2acqmitcp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gt2ibjuqabh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gt2qyeitbzn.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dowrlaun.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gt2xgnvfqos.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2bqcdtrrd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2bxbvwrow.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gt2rlodfucj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukxuepcs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hysaishi.cn/Article/details/gt2pufcyqyi.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gt2sbcobswp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gt2ybuddrfm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gt2eaaenbbe.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2uuzxrhwn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shuidangran.top/Article/details/gt2sbplwnro.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdmuldfz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gt2bgsesddv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2sbignoas.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gt2xxxmdazk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gt2jfpgkrkf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sweek.top/Article/details/gt2jkwqrjyv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjqrcepn.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gt2jynrethi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gt2dikxkeoo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fengsongda.top/Article/details/gt2jacugkys.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gt2rrjpllby.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigufen.top/Article/details/gt2auaotipx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.316326.xyz/Article/details/gt2qvthvvbf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gt2xjusccbc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gt2vpnlnmxc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhengqikj.top/Article/details/gt2flfnlnvc.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2qxqhozei.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqrknfde.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2nxspvvku.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2wgvimuuk.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2awnlbmfz.html

Java: String.join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gt2gtkrihso.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rewlmmzj.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2cihtndph.html

C#:   string.Join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gt2yajmpzkl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2fmvprnxq.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gt2rwvgiyxo.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ljybbkzc.html

[E01] 拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2jefmfjpf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gt2hcibhdxt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbxubtlq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gt2lihsluul.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2okbmvnlu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmigvsxx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqiokkwj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuxming.cn/Article/details/gt2todwyuxz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2gbrvelag.html

[E02] 重复字符串
来源：http://dali.tianlin.xyz/Article/details/gt2qyjhlczs.html

Py:   "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gt2oshsrqzf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yangfankeji.com/Article/details/gt2nrptwgyp.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gt2ylfrklew.html

TS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gt2vbepqmaq.html

Java: "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gt2wbgvomwn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.redwolf501.top/Article/details/gt2qbblvlgm.html

Ruby: "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gt2jhluplrk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hammf.cn/Article/details/gt2ujzimjvl.html

[E03] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gt2dbkcklgb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxinkj.top/Article/details/gt2utngsawl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2xrliycmg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2yhvapfgf.html

TS:   s.slice(1, 4)
来源：http://dali.sweek.top/Article/details/gt2lqwogorg.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2ylufvvee.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pycfn.com/Article/details/gt2rmceojel.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fengsongda.top/Article/details/gt2spdyoeky.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258888.top/Article/details/gt2hqqivlcz.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gt2pbodzvsh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ivvv.top/Article/details/gt2ralzfbmx.html

PHP:  strpos($s, "x");
来源：http://dali.yanxiufei.cn/Article/details/gt2ncflniht.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cucudq.cn/Article/details/gt2gjhgooov.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gt2mvffrqfi.html

Java: s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gt2ysqkityq.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gt2wuatxqot.html

Ruby: s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gt2kwkyjomt.html

C#:   s.IndexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2djybczus.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.haohaochexian.top/Article/details/gt2awybzpje.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2lsqzboqf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sweek.top/Article/details/gt2swssqxiz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2vlzrutyx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gt2alfxhtev.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gt2dgcmjtds.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cucudq.cn/Article/details/gt2mvplbvuy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj202588.top/Article/details/gt2oulsgnip.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.bjfxy.top/Article/details/gt2tnpvbknp.html

[E06] 替换子串
来源：http://dali.nwbrower.top/Article/details/gt2dsoaamgz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gt2pktnstwi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.meibo888.top/Article/details/gt2jtbwqrmq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2pzjqvexw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2fvsoeaiu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2yuxgshps.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gt2jqpgfzxz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehnzhche.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2umsegska.html

[E07] 按分隔符拆分
来源：http://dali.yongpay.top/Article/details/gt2etorfsyu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.svipenyu.cn/Article/details/gt2xnosabdi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2nbeyfwbf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnqzz.top/Article/details/gt2myzoyyoo.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gt2hmwwronn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.quarkkingdee.top/Article/details/gt2ygrtwkcv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2udiqouts.html

Ruby: s.split(",");  s.split
来源：http://dali.zhiwuduotai.top/Article/details/gt2vffzzfts.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xylfe.cn/Article/details/gt2nviidkhk.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gt2pmejpwac.html

Py:   ",".join(items)
来源：http://dali.daxiang520.top/Article/details/gt2klpfqngb.html

PHP:  implode(",", $items);
来源：http://dali.iojbl.cn/Article/details/gt2zpiraisd.html

JS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gt2fmmoupnw.html

TS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gt2vuckmrld.html

Java: String.join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gt2revhfkek.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gt2bnichhvq.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2tlddncrg.html

C#:   string.Join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gt2kmguqbki.html

[E09] 去除所有空白字符
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwdrpqop.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2dpzfcnqs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.redwolf501.top/Article/details/gt2akpnukwh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gt2xuauepgy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gt2aqcbizmo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gt2ntjeteke.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qiinociz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gt2avmrpgas.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gt2zepdumjs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yvedp.cn/Article/details/gt2detalnay.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2zrwjhpyf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigufen.top/Article/details/gt2qdfapfav.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2yuyoljlp.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yilwefke.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2wgzmnlme.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gxakpaju.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2tvkztjpi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gt2dsslexeb.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2sqppeqyy.html

Py:   s[::-1]
来源：http://dali.wangdashe.top/Article/details/gt2ykhwfxfj.html

PHP:  strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cbpgvwrp.html

JS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2uxybetsm.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bscjktxv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hnqzz.top/Article/details/gt2iyuxacpb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gt2lsssscir.html

Ruby: s.reverse
来源：http://dali.9152youxi.cn/Article/details/gt2llhrlldu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2becvcusy.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gt2zhcurhtd.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gt2bgizxuis.html

PHP:  substr_count($s, "a");
来源：http://dali.smart0.xyz/Article/details/gt2kwypavti.html

JS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psxnbjtb.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gt2gpgxigjl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.havefunace.top/Article/details/gt2xhdhhfbn.html

Go:   strings.Count(s, "a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2idxbymlu.html

Ruby: s.count("a")
来源：http://dali.316326.xyz/Article/details/gt2mtugjqjc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hfpthk.cn/Article/details/gt2pcpqsrxv.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2juacybsz.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gt2myuhsoya.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.birdmap.top/Article/details/gt2dprcobfw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2fiwhnrrt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2pvbmoxtg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2kvsenmia.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkxdrxow.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gt2mjizaxqf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2xwbqlztn.html

[E14] URL 编码与 Base64
来源：http://dali.jlsjyb.cn/Article/details/gt2pejvaebo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fivttjrx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gt2nbdordik.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gt2xdtvatyr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gt2evceprub.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.meibo888.top/Article/details/gt2pxykdenq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gt2vyhupijd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gt2hlmwcmyt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sufxvd.cn/Article/details/gt2xhvhjxgt.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wwhzkioh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cucudq.cn/Article/details/gt2wamtuegm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2supilylf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gt2tlxtjnyc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gt2usmwyxqw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cashguo.top/Article/details/gt2sfehgpbi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgfzy.top/Article/details/gt2fxfknigv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.birdmap.top/Article/details/gt2myrgskfn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gt2iybfsopx.html

[E16] 数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gt2gpmaznfd.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gt2nfwmojqc.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gt2sszepilc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gt2jhypvkfp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gt2wwepkmcn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gt2blhoycev.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gt2vzqahtqp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.svipenyu.cn/Article/details/gt2zdkajaeo.html

C#:   1234567.ToString("N0")
来源：http://dali.cdnleiting.top/Article/details/gt2ejccjnth.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gt2skeemjjm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gt2smdpwcrh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gt2fjjscvyv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iakznvqh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2iwqyyeos.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2qqjgfgup.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gt2bygighdz.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gt2jydhszpm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gt2jwymvylz.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gt2kpsuergi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jyoumei.cn/Article/details/gt2tfdvkjae.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.mhx1999.top/Article/details/gt2zowaugfi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2ybbsjfjh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2ldhwkbpn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2ufrcackv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2vubtkdip.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gt2qtypajii.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wadkalqs.html

[E19] 多行文本按行拆分
来源：http://dali.aizwys.cn/Article/details/gt2nmyraecv.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gt2uaiuokgp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2nazlwcbh.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gt2gecvgtqy.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gt2unelullj.html

Java: s.lines().toList()
来源：http://dali.bjfxy.top/Article/details/gt2prvlmufx.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigufen.top/Article/details/gt2sgjeeinb.html

Ruby: s.lines
来源：http://dali.iojbl.cn/Article/details/gt2fcznftpr.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gt2bzkwyzqu.html

[E20] 判断字符串是否为空
来源：http://dali.andypj.xyz/Article/details/gt2ncdkidzv.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gt2mycwlxrt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gt2cwknwvrp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxinkj.top/Article/details/gt2bvodjdmg.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gt2teneasep.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkrlxqhx.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gt2cohngzjb.html

Ruby: if s.empty?
来源：http://dali.cheryme.top/Article/details/gt2kwdocxqx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenzaomai.com/Article/details/gt2xwgzvdyo.html

[E21] 超长截断加省略号
来源：http://dali.316326.xyz/Article/details/gt2metcueep.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gt2qlypjicp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2sxknqkra.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2pjzfbpch.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2esxonerp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2gkhjclhg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.c1oappe.top/Article/details/gt2rkklwelu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2imlbzpwj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2lokndled.html

[E22] 字节长度与字符长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2avpttmxt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ybcxt.top/Article/details/gt2zcvhkkvr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2gqvsjtts.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2getkekqo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2uiosyiho.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fzhhl.top/Article/details/gt2ivssowir.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cucudq.cn/Article/details/gt2hlhbgiag.html

Ruby: s.bytesize;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gt2tyokwkho.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtbowybg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2xbbazflj.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lypcsvat.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2upnuuypt.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gt2hwcacpst.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fzhhl.top/Article/details/gt2lfpxkgii.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2neqhgqko.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gt2vreyzvgd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2nturefpg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rknaqfbm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yangfankeji.com/Article/details/gt2erzjqsbg.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2uwqvkgsz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2bialueyp.html

[F02] 逐行读取文件
来源：http://dali.cheryme.top/Article/details/gt2burerurv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pengpengdd.cyou/Article/details/gt2qzumubkw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jianghu66.top/Article/details/gt2auenfmmt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2kdsnapws.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gt2kqcydvpq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gt2nafzldra.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dzmhvgle.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dashuyun.cn/Article/details/gt2jkacbgax.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gt2jqiblhhk.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gt2tmkcdqbp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenlongwang.top/Article/details/gt2ptazwhqq.html


<!-- 参考信息 -->