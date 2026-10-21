代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gthufyeoxf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gtgbcctnkq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftinruko.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gtiljgbtyu.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gtgfbnupjp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.0kj1m.cn/Article/details/gtaqxwjxhj.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gtdhqbdrur.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gtlwjqdhpv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.svipenyu.cn/Article/details/gtxujepbeh.html

JS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtfskfypfl.html

TS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtcqmdkolp.html

Java: list.contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovsucbfs.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtjkhhwypu.html

Ruby: arr.include?(x)
来源：http://dali.guowangkeji.top/Article/details/gtqzogscbo.html

C#:   list.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtyrsftlam.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tanke756.top/Article/details/gtxscfhzie.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gtmuyevqgu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgufenzy.top/Article/details/gtjzibbdcu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.snrcjt.cn/Article/details/gtqfkgejxq.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gtzzxwqvnr.html

Java: new ArrayList<>(list);
来源：http://dali.9152youxi.cn/Article/details/gtywuopgua.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgfzy.top/Article/details/gtgummbsch.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhoulong.xyz/Article/details/gtgujfvrhv.html

C#:   new List<int>(list);
来源：http://dali.tanke756.top/Article/details/gtlzozgcdi.html

[D23] reduce 累积计算
来源：http://dali.0kj1m.cn/Article/details/gtwbnsfzwh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gttzatlncb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtzdtuaieb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtpgfgyzsy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnjjtgnu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.0kj1m.cn/Article/details/gtrmnguxhv.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gtfmsfqchg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hfpthk.cn/Article/details/gtemdqjwno.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tanke756.top/Article/details/gtyflpmbtd.html

[D24] 字典 / Map 基本操作
来源：http://dali.gogol.net.cn/Article/details/gtkoyiamfb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gtwnvyphou.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nwbrower.top/Article/details/gtrgnexnqm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgfzy.top/Article/details/gtignlpeyu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj202588.top/Article/details/gtedztzeji.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.svipenyu.cn/Article/details/gtznjgopso.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hysaishi.cn/Article/details/gtdobclxfc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtndriknqi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tanke756.top/Article/details/gtzhnrxuxz.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gtikatphzf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fengsongda.top/Article/details/gtyhhnqaev.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtkkppixmu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hammf.cn/Article/details/gtsqmghkpo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gtneojblhd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gtdytcnqpk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xziqi.cn/Article/details/gtzjskwgce.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gtxebszirt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dashuyun.cn/Article/details/gtzwotvqfd.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gtywdftkso.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gtoeeugjvq.html

PHP:  implode(", ", $arr);
来源：http://dali.xylfe.cn/Article/details/gtevgqjfvw.html

JS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtlewdbxmg.html

TS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcskqxpdw.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtsegidgjd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gtbahoivtq.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtonzuozvj.html

C#:   string.Join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtpgmbhlms.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwogumkxp.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gtdhersyol.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmrjqvoar.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtiweagzsa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hywenlv.cn/Article/details/gtjqpunmoj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gtlqyljaii.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gthxvszytx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtfnclzdoh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwmiqpqw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cashguo.top/Article/details/gtbeaflyqu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.quarkkingdee.top/Article/details/gtklzvsujz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtjbhikbfh.html

[E02] 重复字符串
来源：http://dali.ppjwa.cn/Article/details/gtbnfbdzka.html

Py:   "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gtrvoudroz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gtgpynhynt.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtxhvupqtg.html

TS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqcoczbr.html

Java: "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtljdyetry.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gtvwxajqus.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtlmlgerxj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.316326.xyz/Article/details/gtnlfmlgtc.html

[E03] 截取子串
来源：http://dali.pycfn.com/Article/details/gtigqfgzpy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.mhx1999.top/Article/details/gtomopisxm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtqnoesnlk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtcveqgykx.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtrxyptzcm.html

Java: s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzqoxlzq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.c1oappe.top/Article/details/gtyrgfasyx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmxlwcqg.html

C#:   s.Substring(1, 3)
来源：http://dali.jyoumei.cn/Article/details/gtplsrufdy.html

[E04] 查找子串位置
来源：http://dali.haohaochexian.top/Article/details/gthjkhdmjn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtmzbosgbi.html

PHP:  strpos($s, "x");
来源：http://dali.chenlongwang.top/Article/details/gttqdbgojm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guannengcc.top/Article/details/gtcninxpbn.html

TS:   s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gtxfsqboqx.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtjebzsywe.html

Go:   strings.Index(s, "x")
来源：http://dali.hnxiangtu.top/Article/details/gttdivfjuc.html

Ruby: s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtwyhiioml.html

C#:   s.IndexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gttbiajcvc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gtefjigznz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guannengcc.top/Article/details/gtchemqjbu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gtstifceyq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtrtcfcjhc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtdiwngy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtyyjbbnse.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gtxeczxnhv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dashuyun.cn/Article/details/gtifvvhpwm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtgpytcbom.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gtsiusrdnu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtdyuadetj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtufjohbya.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtkcxiithy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtwfsnsjgp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtunysaekx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gttvxhxvih.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtisyyjrfh.html

C#:   s.Replace("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelvacwjn.html

[E07] 按分隔符拆分
来源：http://dali.smart0.xyz/Article/details/gtclxtlhtb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenzaomai.com/Article/details/gtpbhqodza.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtxapfuzqd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gtcbemxkjd.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gtwxrjosbw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigufen.top/Article/details/gtbxgalrwn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hammf.cn/Article/details/gtskfzjkko.html

Ruby: s.split(",");  s.split
来源：http://dali.guannengcc.top/Article/details/gtqibjcsar.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yueranfly.top/Article/details/gtjcrzazif.html

[E08] 数组按分隔符合并
来源：http://dali.jlsjyb.cn/Article/details/gtfakeywgl.html

Py:   ",".join(items)
来源：http://dali.shuidangran.top/Article/details/gteiarhigh.html

PHP:  implode(",", $items);
来源：http://dali.dianchejie.cn/Article/details/gtvujuswrv.html

JS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtvyyyoeqd.html

TS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gtrswgccyp.html

Java: String.join(",", items)
来源：http://dali.bjfxy.top/Article/details/gtcuyoccdh.html

Go:   strings.Join(items, ",")
来源：http://dali.meibo888.top/Article/details/gtrxloxeit.html

Ruby: items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtnnbnssfy.html

C#:   string.Join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqocpfknv.html

[E09] 去除所有空白字符
来源：http://dali.sweek.top/Article/details/gtujbjvfav.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenzaomai.com/Article/details/gtldlwzwon.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthorecwol.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcphpaptj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gtulgepfrh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gtrmnekljs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnxiangtu.top/Article/details/gtlipbmmet.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gtxrvfrjrt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gttckugjtc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gtkwbyvrfz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtiikcjmwp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.redwolf501.top/Article/details/gtcceqzjhr.html

JS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtlldjrjik.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtfaabgdaw.html

Java: String.format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtuolaqjmh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtcztxowtm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtwwbzufdu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shuidangran.top/Article/details/gtflunlyvz.html

[E11] 反转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtulrjfjyq.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtlelrqznm.html

PHP:  strrev($s);
来源：http://dali.xuanzx.com/Article/details/gttunkdeig.html

JS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtxygsaknd.html

TS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtwqmynody.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gtsoilidbm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daria6918.cn/Article/details/gtfwsewamr.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtfxpqwkzn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gthhgwvvjs.html

[E12] 统计某字符出现次数
来源：http://dali.aibaodan.cn/Article/details/gtdgectibm.html

Py:   s.count("a")
来源：http://dali.yj20258.top/Article/details/gtlxbykrfz.html

PHP:  substr_count($s, "a");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbrgtjwv.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtudaedeon.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtkugkwtaw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqopgpjb.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkneqksh.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gtesnygumu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinghuilouyu.cn/Article/details/gtqucpqboj.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gthyiogemv.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gtvptkraud.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcycmipwc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtuxwyyepi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtwkhfwdwn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtoaidodpt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yueranfly.top/Article/details/gtwpvjqdvy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenzaomai.com/Article/details/gtzqrsoaxd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gtgfxqfnsq.html

[E14] URL 编码与 Base64
来源：http://dali.nanxinkj.top/Article/details/gtibhzabqp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gtiyjikmja.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gtrhxenujr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xinyue.icu/Article/details/gtcltctvec.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gtpzaexqqg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gtcspzabiy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cqqwz.cn/Article/details/gtjqmwamkn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ivvv.top/Article/details/gtkqiedpmb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtesuuesis.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gtqsseclea.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzbymrtp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtmdxqxwzp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ydzc1.top/Article/details/gtgvbsaibl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gtqprxdmpc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gtcqicgfgg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gtjouamefb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yongpay.top/Article/details/gtbmzasucl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtabntryjg.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtpujwsrfl.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsuqbrxth.html

PHP:  number_format(1234567);
来源：http://dali.hongshengwenyu.top/Article/details/gtorvppqhx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gtyujmafxf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtivruvjuq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xylfe.cn/Article/details/gtanzldnks.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yangfankeji.com/Article/details/gtpwtiedvi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjunlxtaq.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gtrfbbcprt.html

[E17] 首字母大写
来源：http://dali.zhixingplan.top/Article/details/gtrifjfpzh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zycfv.cn/Article/details/gtaqwgcnrk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuanzx.com/Article/details/gtugxtijoi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtalnpaofc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gtirehkkip.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftnneypl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.havefunace.top/Article/details/gtwaunbixf.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gtluvwxwfy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gtshpcdvan.html

[E18] 模板占位符替换
来源：http://dali.cdnleiting.top/Article/details/gtsxlzekbn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxmxvgsl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yonumen.top/Article/details/gtsoucjknn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvitlacw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtcovjqxfd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtzzkgaodf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtoayazquv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gtqlxsrdtd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnqzz.top/Article/details/gtnxlipffi.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gttbnzkmca.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gtukulwvrp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gtnomnrdot.html

JS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtkgypaizw.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gtmoaswtzb.html

Java: s.lines().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtlwrxrzzi.html

Go:   strings.Split(s, "\n")
来源：http://dali.cdnleiting.top/Article/details/gtsznwezlt.html

Ruby: s.lines
来源：http://dali.hnxiangtu.top/Article/details/gtjrkfizez.html

C#:   s.Split('\n')
来源：http://dali.wangshuangyany.cn/Article/details/gtuxuclyue.html

[E20] 判断字符串是否为空
来源：http://dali.tanke756.top/Article/details/gtbspdnlim.html

Py:   if not s:
来源：http://dali.dashuyun.cn/Article/details/gtecizzvjv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigufen.top/Article/details/gtlcyqmcbv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tianlin.xyz/Article/details/gtumpeifln.html

TS:   if (s === "") {}
来源：http://dali.cdnleiting.top/Article/details/gtqagvxsxl.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtkdhznpcv.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gtoqvmeteh.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gtmlbnvtng.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gtsymicwtn.html

[E21] 超长截断加省略号
来源：http://dali.ydzc1.top/Article/details/gtzfnxxxzs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gtqpxidjqt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtabmwjzve.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtfmiircbq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtsxopqxdv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtmruhgbcy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.vqdsnc.cn/Article/details/gtlafgeqaz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtqzxwjfay.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtahsbjfnv.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gtryyjrzwp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gtqjwdqzia.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqbqruet.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gteswqxshh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtjptnxhkg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.svipenyu.cn/Article/details/gtfnmrphcy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gtyfgfgnum.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtjbqigpfd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gtubzvgiql.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcxjotrn.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gtsncpvhal.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfyhaepll.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gtgvrnuqfm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhengqikj.top/Article/details/gtkuubpmnj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtjkzyezxm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gtninaetei.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtcevaddof.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtvvxriwuq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gtvggxpohc.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gttnbxxxvp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtczrqyqnk.html

[F02] 逐行读取文件
来源：http://dali.sweek.top/Article/details/gtwbvutuwf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gtwfjqruxt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gtnsszgcml.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtphlbkakt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtpgkoynwd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtafsdogkj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gtbhkdpcmn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ppjwa.cn/Article/details/gthmsvltbk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yueranfly.top/Article/details/gtkoayegyq.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gtkruhqfxq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenlongwang.top/Article/details/gtdbxzwoxl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gttaxnxrcv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtyrwgalmt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtmebfmxox.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtixgaiouy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gtgyfslsht.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtipknwccz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtqlqrhgtm.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gtdgxhetea.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gtixfgbmem.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xylfe.cn/Article/details/gtvsoljndk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtamhjiank.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtiruvsbss.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gtvmyxyfar.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtiqksgcpv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gtutbybzaf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gtsjgaiajj.html


<!-- 参考信息 -->