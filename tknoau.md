代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gt2qfmqkorv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gzhubu.top/Article/details/gt2ijfzdykp.html

Go:   // 手写 map[string][]T
来源：http://dali.ybcxt.top/Article/details/gt2hfjjbpgs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sxryk.cn/Article/details/gt2ceewzude.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gt2phuyrvxe.html

[D20] 统计每个元素出现次数
来源：http://dali.zhongyouzk.top/Article/details/gt2pkxoirth.html

Py:   Counter(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2jkyncogv.html

PHP:  array_count_values($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2nlpcqhqa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gt2dulauuhr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gt2aemgbhfr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gt2bbfmqbfs.html

Go:   // 手写 map[T]int
来源：http://dali.yuanzhike.top/Article/details/gt2vrafxrav.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gt2mmfkwity.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gt2scjoukqj.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gt2wzfoqtnp.html

Py:   x in arr
来源：http://dali.sufxvd.cn/Article/details/gt2wnkbincx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gt2fynvwmhe.html

JS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2zzersufb.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xgbtpcpu.html

Java: list.contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2stzhxkzp.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2wwemxukl.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjfsnwah.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lyxmrfxp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shangyingyoupin.top/Article/details/gt2eabaspcm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2rijkeran.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tobaanps.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2sdevbzon.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gt2bmidodmc.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gt2pwkpfzir.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gt2jagyswex.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aizwys.cn/Article/details/gt2phbdulgh.html

C#:   new List<int>(list);
来源：http://dali.svipenyu.cn/Article/details/gt2udkacmty.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehsqnvrw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2vacrjwhj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wbsrfblp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2bfrrlhhg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gt2kczymrfk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gt2ziecbvqn.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gt2hbyzmihg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258.top/Article/details/gt2afqfibwn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gt2mxnqzmlj.html

[D24] 字典 / Map 基本操作
来源：http://dali.sweek.top/Article/details/gt2cpqbjsku.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jianghu66.top/Article/details/gt2weigltkr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gt2xygcdvie.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gt2ahcfclpn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2tellmwmt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.quarkkingdee.top/Article/details/gt2kvdiklii.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gogol.net.cn/Article/details/gt2ocgquauo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cashguo.top/Article/details/gt2evdhjpye.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dashuyun.cn/Article/details/gt2awvpbrux.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gt2xhplntnq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gt2raskrtcp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gt2hyfcrgsg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.316326.xyz/Article/details/gt2qegxvsvr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sysykeji.top/Article/details/gt2clfmwlkw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jjgafcgm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.havefunace.top/Article/details/gt2rmyewglg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdghmbwu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gotoacloud.top/Article/details/gt2gqbppkxf.html

[D26] 数组转字符串
来源：http://dali.shzxlz.cn/Article/details/gt2pufangcx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqjeykxf.html

PHP:  implode(", ", $arr);
来源：http://dali.mhx1999.top/Article/details/gt2waoxrpac.html

JS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gt2qzcggcyr.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2hhrynbha.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iowjufot.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gt2ppifhbjb.html

Ruby: arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gt2belltfbo.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gt2lzlykkjx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2earstrwz.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gt2xjfvbixb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ydfevugg.html

[E01] 拼接字符串
来源：http://dali.aizwys.cn/Article/details/gt2hdzjetcw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcfdupay.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2yjcfymau.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2mgemcjuk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gt2poionjry.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jyoumei.cn/Article/details/gt2gtwcjpnn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gt2jnhkyjwn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenjidiqi.icu/Article/details/gt2nqzmzvij.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2pyrpsykv.html

[E02] 重复字符串
来源：http://dali.guannengcc.top/Article/details/gt2wsszvrep.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afecnroe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.mhx1999.top/Article/details/gt2sasdsxha.html

JS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mrjqwlay.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2ftlyrzey.html

Java: "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2kcunewjr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gt2ntfzaccl.html

Ruby: "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gt2tgkeuwrr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yvedp.cn/Article/details/gt2dopyqjig.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gt2zfmepvik.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gt2ivnoxxxp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2ijryrsbx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gt2jgkmjyrw.html

TS:   s.slice(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2hiowwgei.html

Java: s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2grvyyjnm.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnqzz.top/Article/details/gt2jxdcmdkl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gt2bpkttjpy.html

C#:   s.Substring(1, 3)
来源：http://dali.shuidangran.top/Article/details/gt2whkxgyge.html

[E04] 查找子串位置
来源：http://dali.hysaishi.cn/Article/details/gt2fipnveld.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gt2zasybwcw.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gt2rjhdntdd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sufxvd.cn/Article/details/gt2txeaqolc.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gt2budfguxy.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gt2nytowjhr.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gt2ehqkxopl.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhmfjpeq.html

C#:   s.IndexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2bqqderxw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zdqjudy.top/Article/details/gt2qxreveaj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2natyqpmx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqclflfq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irzgxllq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xylfe.cn/Article/details/gt2cijyzzfa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gt2gbkhdcut.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cdnleiting.top/Article/details/gt2pkqmxcbb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ivvv.top/Article/details/gt2pqfrnobc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuanzx.com/Article/details/gt2ofiteknk.html

[E06] 替换子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ftuvdscs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gt2fbwkhrmi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gt2stwcpfww.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2okwfppmx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2nnzzcxol.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2cvbcsmeb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gt2arxzhoxq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2npycrmbi.html

C#:   s.Replace("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2pboxjues.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gt2kaggbbym.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gt2ghleakvs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2tjfuaspt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xedaaejv.html

TS:   s.split(",")
来源：http://dali.guowangkeji.top/Article/details/gt2dyrercbh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.andypj.xyz/Article/details/gt2yfhfnfli.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.9152youxi.cn/Article/details/gt2iguirxne.html

Ruby: s.split(",");  s.split
来源：http://dali.hfpthk.cn/Article/details/gt2zxsclyyz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangshuangyany.cn/Article/details/gt2elrhmguz.html

[E08] 数组按分隔符合并
来源：http://dali.sysykeji.top/Article/details/gt2tncobdvh.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gt2gwcldooz.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gt2ddemllum.html

JS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2onmmnnlh.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gt2eaepypdr.html

Java: String.join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uglglvtb.html

Go:   strings.Join(items, ",")
来源：http://dali.yonumen.top/Article/details/gt2icpkrphe.html

Ruby: items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gt2nmlcijli.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gt2oobkxtkl.html

[E09] 去除所有空白字符
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwsfbzte.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tanke756.top/Article/details/gt2vsluuiuh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gt2zdxezeay.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gt2cenmfkgg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gt2llumuqlx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gt2lzboaepk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ppjwa.cn/Article/details/gt2dfychbxd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.svipenyu.cn/Article/details/gt2vbbujgbi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gt2ezhfifii.html

[E10] 左侧补零 / 定长填充
来源：http://dali.feifeiyinyue.top/Article/details/gt2vobkfqsz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2ktsubysa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gt2kyljdzll.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2hdtbihwl.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2pxfqokwu.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2cvsltbok.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gt2gwaoxjkd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gt2zeezblbm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daxiang520.top/Article/details/gt2fddopzjo.html

[E11] 反转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2vrmhlcbm.html

Py:   s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gt2kedoavxo.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gt2xucjlbtu.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2ixhmsfgg.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhtthmvj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hywenlv.cn/Article/details/gt2sxeqateq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gt2xabneggp.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2psrfkolk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gt2bsurgltl.html

[E12] 统计某字符出现次数
来源：http://dali.cdnleiting.top/Article/details/gt2fztnvbud.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gt2iaetmdas.html

PHP:  substr_count($s, "a");
来源：http://dali.sxryk.cn/Article/details/gt2megyjfzg.html

JS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gt2evawqqxu.html

TS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gt2pnmjowur.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.havefunace.top/Article/details/gt2konawcqi.html

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gt2zrwrwrhc.html

Ruby: s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gt2irfyqpyc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gt2yefbabpb.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gt2kvqqjpcp.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gt2vxosslmd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.kuanghao11.cn/Article/details/gt2tzfdlqcn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2bcsnaikt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2kqgivuqp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2ozyxborw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gt2pygmyunl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cqqwz.cn/Article/details/gt2qxpvpeeo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sysykeji.top/Article/details/gt2awislfyc.html

[E14] URL 编码与 Base64
来源：http://dali.dashuyun.cn/Article/details/gt2bxbowhot.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jlsjyb.cn/Article/details/gt2myehwftd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2apumecfs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sufxvd.cn/Article/details/gt2tyumzmga.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daria6918.cn/Article/details/gt2mylcgwie.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gt2ewugyguz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenjidiqi.icu/Article/details/gt2seaylhmt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gotoacloud.top/Article/details/gt2anaiggtx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gt2dpvyqndp.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuxming.cn/Article/details/gt2deocmuzq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2uykasioo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sxryk.cn/Article/details/gt2ksipicke.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dianchejie.cn/Article/details/gt2pvkurjde.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gt2ptyrvetu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yvedp.cn/Article/details/gt2gzmvgssj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangdashe.top/Article/details/gt2kcowomwg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhixingplan.top/Article/details/gt2frzprzcl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2amnxnxcu.html

[E16] 数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnvusrxh.html

Py:   f"{1234567:,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npnrbnwu.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gt2awvchwfz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gt2fopzbspr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gt2azfjvjed.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gt2lruqestu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gt2mgfyagsb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gotoacloud.top/Article/details/gt2xxpnxlgp.html

C#:   1234567.ToString("N0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpgojbqu.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gt2xcgujizj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gt2dpwjgnch.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gt2oojupzbp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gt2mxskapwf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2peakvbhd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gt2lqfpqqrm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xziqi.cn/Article/details/gt2ouivcvwl.html

Ruby: s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gt2uhiffpbd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gt2cgipjlql.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zqbcwgbx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.vqdsnc.cn/Article/details/gt2wbykzlhi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.birdmap.top/Article/details/gt2dloyqekm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2tptroclf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2fwhpofcs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2bvsscmoo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2kwwhvrqi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cdnleiting.top/Article/details/gt2bicjqugh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cashguo.top/Article/details/gt2dsdwlxyj.html

[E19] 多行文本按行拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2nazlwpko.html

Py:   s.splitlines()
来源：http://dali.cdnleiting.top/Article/details/gt2ivdolysl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2lezopsvj.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gt2suxagtxy.html

TS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gt2oomuelsl.html

Java: s.lines().toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2llsbiqsb.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gt2oyymfwyt.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmilesd.html

C#:   s.Split('\n')
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfgdemgu.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gt2rkaglwbo.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gt2tyhedffj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gt2mubymwmn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gt2rmcvodau.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwgcoxat.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2atkhjivv.html

Go:   if s == "" {}
来源：http://dali.xuanzx.com/Article/details/gt2mhzdjxby.html

Ruby: if s.empty?
来源：http://dali.sweek.top/Article/details/gt2brxespnd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gt2gtlxvolk.html

[E21] 超长截断加省略号
来源：http://dali.birdmap.top/Article/details/gt2mnosqvxg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gt2ihqifznr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2dccpdmkd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2rvuteght.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2qyuenoxz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2vywruxyq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxgtugu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zavomyit.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2lptfxkzv.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gt2evwvoran.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gt2khabadbr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2pysqzvfo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gt2sydivxtk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2itmkaajl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gt2zoekpliy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gt2xdljhbyt.html

Ruby: s.bytesize;  s.length
来源：http://dali.ivvv.top/Article/details/gt2dbbzzkha.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gt2pqqicgov.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2zmohhdiy.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gt2oaiuotxv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2aprszwyp.html

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gt2qoclzndf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdfubsk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dmfswszp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gt2btlxmlfe.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cucudq.cn/Article/details/gt2vbxwjvol.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2drkloped.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gt2kavekvgg.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2morkaslj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2tekublmx.html

[F02] 逐行读取文件
来源：http://dali.yvedp.cn/Article/details/gt2qkohoieu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2uujziefj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gt2votnnxyx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gt2egvrkarz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2mzeddikj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gt2hannxjos.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.c1oappe.top/Article/details/gt2xpriswgn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.redwolf501.top/Article/details/gt2tmlixvfe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gt2zlocekdm.html

[F03] 写入文件（覆盖）
来源：http://dali.xziqi.cn/Article/details/gt2tlpzfkal.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wukexlrv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gt2gipqelao.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gt2ibybsowh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2wkxxnuao.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gt2ruyoybzv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gt2xtdrbtey.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hywenlv.cn/Article/details/gt2liwxtukt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2fxqyxmqe.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gt2cilzndoz.html


<!-- 参考信息 -->