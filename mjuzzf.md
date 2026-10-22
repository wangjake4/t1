代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtfcaegsvc.html

Go:   // 手写双层循环
来源：http://dali.haohaochexian.top/Article/details/gtwlhnngve.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxlsisqu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gtbsieczyf.html

[D19] 按字段分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnmegvlq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gtgpncmbou.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gtxdvcsnxp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yueranfly.top/Article/details/gtvnqqcqnx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gtffaeprro.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shangyingyoupin.top/Article/details/gtwyxidwoj.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gtjkflsljn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cheryme.top/Article/details/gteiwuxsuu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gteuqezaic.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtorshwcpa.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gtixkfousx.html

PHP:  array_count_values($arr);
来源：http://dali.sysykeji.top/Article/details/gtyziomeja.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtzsxsfisr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtudsfnxul.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gtjiqumvfx.html

Go:   // 手写 map[T]int
来源：http://dali.bjfxy.top/Article/details/gtmlvbasxa.html

Ruby: arr.tally
来源：http://dali.cqqwz.cn/Article/details/gtajesukrv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj202588.top/Article/details/gtqwmmifnm.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gtsjmchyja.html

Py:   x in arr
来源：http://dali.tianlin.xyz/Article/details/gtoabbxcjr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.haohaochexian.top/Article/details/gtwkesdity.html

JS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gtyvtdndpm.html

TS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gttqiztypz.html

Java: list.contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtkldwedye.html

Go:   slices.Contains(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtbpzeiyef.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gtckazzobo.html

C#:   list.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtfaiuiiaf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yanxiufei.cn/Article/details/gtcffrbmnk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dianchejie.cn/Article/details/gtdbsztmzd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxinkj.top/Article/details/gtzdeusird.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ppjwa.cn/Article/details/gtlahpkxvs.html

TS:   [...arr];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvspodjaj.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gtcpngzuxy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.smart0.xyz/Article/details/gtkfeqvcxi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhoulong.xyz/Article/details/gtspkuenmt.html

C#:   new List<int>(list);
来源：http://dali.yj20258.top/Article/details/gtwmixfoov.html

[D23] reduce 累积计算
来源：http://dali.yj20258.top/Article/details/gtzpartrcv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgfzy.top/Article/details/gtemfpwime.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtxbrvwhoi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gtdxowwuqf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtgtmsrmco.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gtywkmjnal.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtmdtalvyh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aizwys.cn/Article/details/gtjaztprjx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gtwhmzhfcy.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxuanxn.top/Article/details/gtsinasyzi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhoulong.xyz/Article/details/gtlqsvbnkg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jianghu66.top/Article/details/gtagtmjyot.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tian-w.cn/Article/details/gtrwfgpaot.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtrxitgbkz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gtvyykscop.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xinyue.icu/Article/details/gttqaggdni.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yangfankeji.com/Article/details/gtrmksuatd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zdqjudy.top/Article/details/gtsjiuturx.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gtkwecdqjq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.9152youxi.cn/Article/details/gtowpyjavh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shzxlz.cn/Article/details/gtlczwsrxx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gtqvhswapi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shuidangran.top/Article/details/gtbefcaxkz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gtrdtmedwd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gtjuoclvht.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.redwolf501.top/Article/details/gthlesyhxu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yongpay.top/Article/details/gtyvwfkjzw.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gtspwntdee.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hywenlv.cn/Article/details/gtwiddhmve.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gtmfwcytzq.html

JS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtnresknjm.html

TS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtilmmtezz.html

Java: String.join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtdzmengni.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258888.top/Article/details/gtawmjmfxe.html

Ruby: arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtnhtydodx.html

C#:   string.Join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtbcrrdahx.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxsbytezi.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gtpkhkxvsl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlmhpyqbt.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtkntltjsv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gogol.net.cn/Article/details/gtxnpcnija.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gtydasqlxy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gteynnilzx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gtmlvpehga.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daxiang520.top/Article/details/gtmhohdmlc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuanzx.com/Article/details/gtvmjtpkah.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gtwvwscadx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cashguo.top/Article/details/gtkhalgjot.html

[E02] 重复字符串
来源：http://dali.ydzc1.top/Article/details/gtbuvdvtto.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtdfflylzs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jyoumei.cn/Article/details/gtsctfqmba.html

JS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtbjydqfka.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtnmolaael.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtqkufxywm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sweek.top/Article/details/gtabatisev.html

Ruby: "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtukickesd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gaohongyu789.top/Article/details/gtkdxwwwvz.html

[E03] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtnjjwfxsv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pengpengdd.cyou/Article/details/gtqnmvqosn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwtxnxss.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gthxysfhay.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtuvsaewtc.html

Java: s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtjromazdd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtbdabrpgp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.haohaochexian.top/Article/details/gtljcuhdgb.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gtgenwkxvj.html

[E04] 查找子串位置
来源：http://dali.cqqwz.cn/Article/details/gtrmtxukmz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtveoyaiqf.html

PHP:  strpos($s, "x");
来源：http://dali.zhengqikj.top/Article/details/gtblrejnix.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gaohongyu789.top/Article/details/gtnttfosdv.html

TS:   s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtjwjkxism.html

Java: s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gtxsqbthva.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gtnecihwlh.html

Ruby: s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gtgkewoxuu.html

C#:   s.IndexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtxkzxiijq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gtnlczwoqz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtqobbjcnt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nwbrower.top/Article/details/gtngtdwzep.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtfkwkwrew.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.bjfxy.top/Article/details/gtvekvshdk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtvsugpbfz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xziqi.cn/Article/details/gtiuselgun.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jlsjyb.cn/Article/details/gtbsqbfjvj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtabgnpqjn.html

[E06] 替换子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpmskxrj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtagntwhjk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zdqjudy.top/Article/details/gtwhuiucuo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtylabtqep.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtrnoossep.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtbbuztcwt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtohdinhrn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtgkaijehr.html

C#:   s.Replace("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtsfrmtcmr.html

[E07] 按分隔符拆分
来源：http://dali.wangdashe.top/Article/details/gtahxpyare.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhongyouzk.top/Article/details/gtectvwoqd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gtfcmseolu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cqqwz.cn/Article/details/gtvplosgdr.html

TS:   s.split(",")
来源：http://dali.zdqjudy.top/Article/details/gtjcihlrcq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gtenhzolqx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxinkj.top/Article/details/gtzcwiqxtl.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gteslnirqi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ybcxt.top/Article/details/gtqlxgwmdc.html

[E08] 数组按分隔符合并
来源：http://dali.redwolf501.top/Article/details/gtuqklxbbk.html

Py:   ",".join(items)
来源：http://dali.tian-w.cn/Article/details/gtgsoyruru.html

PHP:  implode(",", $items);
来源：http://dali.vqdsnc.cn/Article/details/gtncloowov.html

JS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtxqrjpkdz.html

TS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtnicgvtmd.html

Java: String.join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiavjqsql.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gtxxkrxrao.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gtvwcnnydr.html

C#:   string.Join(",", items)
来源：http://dali.gzhubu.top/Article/details/gtklwwwloi.html

[E09] 去除所有空白字符
来源：http://dali.jinqigfzy.top/Article/details/gtuzypdnkg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cashguo.top/Article/details/gtxxexwotf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtsonxqawd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtqelkraqw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gtqjpnuzhr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gtoswykmzo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tian-w.cn/Article/details/gtukifbcov.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.9152youxi.cn/Article/details/gtqvawspwu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gtpaejeowi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shangyingyoupin.top/Article/details/gtdggshewl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gthhhcqoti.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gtablwujph.html

JS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtbigcopwj.html

TS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtvgmtkzga.html

Java: String.format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtmjqgebvq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtydtoozrj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtifotyxgf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfrevdgc.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtrmlyaero.html

Py:   s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtuilioepg.html

PHP:  strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gtyfpfjwed.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gthcoaofts.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtubwgnrul.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gthpbbqtvz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gtrdnvjrhj.html

Ruby: s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtxxmkcojz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gtfxilvxqh.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdswltoi.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtjcyfdipl.html

PHP:  substr_count($s, "a");
来源：http://dali.sxryk.cn/Article/details/gtbjrgucsh.html

JS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gtsqrofguv.html

TS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtxzxcstpf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gtbtlmeqpc.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gtanfvmjah.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gtvcaqkgab.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fzhhl.top/Article/details/gtgscbcyej.html

[E13] 逐字符遍历
来源：http://dali.ybcxt.top/Article/details/gtzjlutbsj.html

Py:   for ch in s: print(ch)
来源：http://dali.fengsongda.top/Article/details/gtwenmysdb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtvpiutych.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtymfrfrcw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtqnpvypex.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhengqikj.top/Article/details/gthikzhipj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtomxrbfai.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gtidwodatr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj202588.top/Article/details/gtnyoysfoy.html

[E14] URL 编码与 Base64
来源：http://dali.nanxinkj.top/Article/details/gtycdkmugb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.fengsongda.top/Article/details/gtbzmmfrlr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guowangkeji.top/Article/details/gtizzoiixs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuanzhike.top/Article/details/gttxzywnji.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gtjsfaondm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtbsmjxkej.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sxryk.cn/Article/details/gtrztvbgmf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhiwuduotai.top/Article/details/gtenhaspno.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtxxrmojiz.html

[E15] HTML 转义 / 反转义
来源：http://dali.feifeiyinyue.top/Article/details/gtyoscugmy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gtabqepvkx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shuidangran.top/Article/details/gtpvwjpgzt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtumeeqzqi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gtucybgqwb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dianchejie.cn/Article/details/gtcbdshavu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pycfn.com/Article/details/gtqhiqxcxe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gtczacnxix.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pengpengdd.cyou/Article/details/gthxpngiek.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gthcxnmxcr.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gtbkfovznc.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gtkjrfnmvp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybnvvifv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gthlxtlsbc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gtmwglucei.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cqqwz.cn/Article/details/gtdiywbinw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gttelehpgf.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gtkzamfwxm.html

[E17] 首字母大写
来源：http://dali.xylfe.cn/Article/details/gtayqvohvk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gtrnkhdhfa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shzxlz.cn/Article/details/gtmapzhvak.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtlytuxqky.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtoiueypgc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtopcnodcg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gtnziqogah.html

Ruby: s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gtsedpvpon.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuanzhike.top/Article/details/gtxmdjxkvi.html

[E18] 模板占位符替换
来源：http://dali.zdqjudy.top/Article/details/gtwgommtbv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yanxiufei.cn/Article/details/gtkcoppffm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gtjusyfwhw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtoqokwsjk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtutjzjnoa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtdhnniarj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtyuctopmv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.havefunace.top/Article/details/gtwpdycrpy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gtscvdnyds.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gthcxrnqhd.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gtdkkjeeab.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtmzuedrqa.html

JS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtfmnqcazb.html

TS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtgbcptgbj.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqqvxqih.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gtqdimsmnh.html

Ruby: s.lines
来源：http://dali.hnqzz.top/Article/details/gtgqngxjce.html

C#:   s.Split('\n')
来源：http://dali.guowangkeji.top/Article/details/gtgjxpllnp.html

[E20] 判断字符串是否为空
来源：http://dali.ehwqpu.com/Article/details/gtyavqiler.html

Py:   if not s:
来源：http://dali.svipenyu.cn/Article/details/gteozsacbl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zdqjudy.top/Article/details/gtqttjxheo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuanzx.com/Article/details/gtdtfbqvyy.html

TS:   if (s === "") {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpijqhrhv.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtcdlqtjit.html

Go:   if s == "" {}
来源：http://dali.haohaochexian.top/Article/details/gtzxjnfmck.html

Ruby: if s.empty?
来源：http://dali.yuanzhike.top/Article/details/gtfbbwnyky.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hywenlv.cn/Article/details/gtzstymfdj.html

[E21] 超长截断加省略号
来源：http://dali.yongpay.top/Article/details/gttasoomuu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sufxvd.cn/Article/details/gtpjbxeeto.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtwwrgefxe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtbrbeiplz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtinaxwkiy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gthercqqni.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangdashe.top/Article/details/gtnckfxkhj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtfxbnrlit.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gthxkgxnps.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gtikgddzxv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.0kj1m.cn/Article/details/gteayqiygh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtkzriovzm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtarcvanet.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtnjdfzkop.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gtavjypoed.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gtsodttudt.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtkuefoxiy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.c1oappe.top/Article/details/gtmnglkpzf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtlpojzhjf.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gtepmmmaki.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtbnwzvbpx.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtwiyjoraz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jlsjyb.cn/Article/details/gtfxbeovea.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtnaugujfm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xinyue.icu/Article/details/gtdbyehrxm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gtgzhjypal.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtufdxpuho.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gtmoatvffl.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtgenjeung.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtgyrbqgew.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gtrzxlondi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gtdsfmbswt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtntbxadmj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtoupretkl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtobnyfdfx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gtufruozyi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gtrhejttfw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.feifeiyinyue.top/Article/details/gtsidvabdm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhengqikj.top/Article/details/gtynwdewca.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gtehwsebkj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cdnleiting.top/Article/details/gtbpzmfcgc.html


<!-- 参考信息 -->