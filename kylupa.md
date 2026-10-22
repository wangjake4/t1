代发 wailian999

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gtvsqrqejv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gthzejfxdu.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gtseloeeei.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gtoloqfunz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gtictvwzyd.html

JS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtckaddesk.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfrbtaaw.html

Java: list.contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtoxyfhjoc.html

Go:   slices.Contains(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtfbaxynbn.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gthxdyznml.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtzcrfdidb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gtgfvgpbva.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yueranfly.top/Article/details/gtleilarli.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosutnbcc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fzhhl.top/Article/details/gtaqgakhnr.html

TS:   [...arr];
来源：http://dali.jinqigfzy.top/Article/details/gtzozrqsvk.html

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gtmtgtqohq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cashguo.top/Article/details/gtsauzdupg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gtxjzuesry.html

C#:   new List<int>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtibqmksuv.html

[D23] reduce 累积计算
来源：http://dali.9152youxi.cn/Article/details/gtdzzzqbtj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.iojbl.cn/Article/details/gtqcijvaha.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.andypj.xyz/Article/details/gtsdifecuq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxmwxece.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtmydxftzu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gaohongyu789.top/Article/details/gtsnasqujb.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gtvsmhcnoa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gtogkzwnpo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gttfdhbtiz.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuetiantiany.cn/Article/details/gtthixfrrt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zycfv.cn/Article/details/gtmycmtlpx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jlsjyb.cn/Article/details/gtcalvanbp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hammf.cn/Article/details/gtyljkpdop.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtrihheyuq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gtblgyuobf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jianghu66.top/Article/details/gtaxgfjpow.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jyoumei.cn/Article/details/gtuizpdkxj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuanzhike.top/Article/details/gtkjwukdzy.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gtzeogpfxe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sweek.top/Article/details/gtbkndyvcu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258888.top/Article/details/gtxcbbfcjw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gtxcdshqup.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gtcyfivddo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gtuzatzwqa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gtlocncosk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nwbrower.top/Article/details/gtjogicmwy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtuueluehv.html

[D26] 数组转字符串
来源：http://dali.ehwqpu.com/Article/details/gthugtzmfj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthstoqyt.html

PHP:  implode(", ", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtkcmrouam.html

JS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtjhbksxde.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtlrwozkpd.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtdbtjxvaq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aizwys.cn/Article/details/gtqjhxsmah.html

Ruby: arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gtvyouenzl.html

C#:   string.Join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gtjruzqvpx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjilghkxq.html

E. 字符串处理
来源：http://dali.yonumen.top/Article/details/gtxmkizyfk.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtonylluqy.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtkwmitaug.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gtccwmenea.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gaohongyu789.top/Article/details/gtmbjrpqeh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtnthwglxv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtbpvjmlrg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hammf.cn/Article/details/gtizddwddr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtziwxlper.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tianlin.xyz/Article/details/gtjlhksqlg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cheryme.top/Article/details/gtuwjktyba.html

[E02] 重复字符串
来源：http://dali.yj202588.top/Article/details/gtygclovrq.html

Py:   "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtzhvoftbs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gtcjaurchk.html

JS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtixszkify.html

TS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtnlojsmwp.html

Java: "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gttpimyhnf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtmjjofdth.html

Ruby: "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gtnpiqfeax.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hfpthk.cn/Article/details/gtjcwlzoey.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gtdrekuues.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gogol.net.cn/Article/details/gthurytkyu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtmagkokdj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtmencvcat.html

TS:   s.slice(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtrkyykxqu.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtuahyqifd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtbsshjhvk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hywenlv.cn/Article/details/gtdbgoumyg.html

C#:   s.Substring(1, 3)
来源：http://dali.guannengcc.top/Article/details/gtchemshuz.html

[E04] 查找子串位置
来源：http://dali.cashguo.top/Article/details/gtsobiraje.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtqsoamgwm.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gtzdfvkjuh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.c1oappe.top/Article/details/gtleyglaxj.html

TS:   s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtmuglrsho.html

Java: s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtufdsisbn.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgufenzy.top/Article/details/gtjukxzspy.html

Ruby: s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrjmhdpi.html

C#:   s.IndexOf("x")
来源：http://dali.aizwys.cn/Article/details/gthklwiemp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zycfv.cn/Article/details/gtsvhxffqb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258.top/Article/details/gtdropunho.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj202588.top/Article/details/gtlseyzsih.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtzakjrtom.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gtzylnyofb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gttupuqzht.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.iojbl.cn/Article/details/gtqobhfisg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gtsgngjdnt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtkxccamwr.html

[E06] 替换子串
来源：http://dali.zycfv.cn/Article/details/gtvjjytfgh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtzvapyblk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtjmeguhvq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtsamvhibf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtxqcfqxkk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtibnnhmbb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gtcxhjimuw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtnguelequ.html

C#:   s.Replace("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtyabmakuc.html

[E07] 按分隔符拆分
来源：http://dali.kuanghao11.cn/Article/details/gtxrwvidov.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnxiangtu.top/Article/details/gtllkexqqd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtwanlisor.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhoulong.xyz/Article/details/gtyfrlatrv.html

TS:   s.split(",")
来源：http://dali.hammf.cn/Article/details/gthnawzryw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.haohaochexian.top/Article/details/gtnyykmxpd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nwbrower.top/Article/details/gtknyyrbhr.html

Ruby: s.split(",");  s.split
来源：http://dali.vqdsnc.cn/Article/details/gtqdbvrfel.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cqqwz.cn/Article/details/gtczabaqgx.html

[E08] 数组按分隔符合并
来源：http://dali.gzhubu.top/Article/details/gthzqroxix.html

Py:   ",".join(items)
来源：http://dali.chenjidiqi.icu/Article/details/gtweijiygk.html

PHP:  implode(",", $items);
来源：http://dali.dianchejie.cn/Article/details/gtrepipwea.html

JS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtrjxzptnf.html

TS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtklkpqmec.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtwyhsfqge.html

Go:   strings.Join(items, ",")
来源：http://dali.gaohongyu789.top/Article/details/gtefgaycja.html

Ruby: items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtuihlpdcv.html

C#:   string.Join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gtqnwzkpcm.html

[E09] 去除所有空白字符
来源：http://dali.jyoumei.cn/Article/details/gturluyixe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnqzz.top/Article/details/gtcoziefwn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ppjwa.cn/Article/details/gtfotdvejw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gttkolwtyf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gttlwyethj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tian-w.cn/Article/details/gtzrdvqjtx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtylrhmcfe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gtuvlfnmpo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtcrqjytkm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuanzhike.top/Article/details/gtwfezdinc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtbgjegqet.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sufxvd.cn/Article/details/gtucwfnbao.html

JS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtotxjlovv.html

TS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gthojabudh.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtmtvjkstj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtgklpwmtd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtmrjirrlp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gtyxndisli.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gttosslavf.html

Py:   s[::-1]
来源：http://dali.nwbrower.top/Article/details/gtxpcstbwv.html

PHP:  strrev($s);
来源：http://dali.sxryk.cn/Article/details/gtcditbhwx.html

JS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtrvfzogyx.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtbrswdlau.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgfzy.top/Article/details/gtqubdocxi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gtbyowknce.html

Ruby: s.reverse
来源：http://dali.yvedp.cn/Article/details/gtkaxcmisw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtrbxnyhsc.html

[E12] 统计某字符出现次数
来源：http://dali.xziqi.cn/Article/details/gtoblhkave.html

Py:   s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtfbxekwuw.html

PHP:  substr_count($s, "a");
来源：http://dali.hnxiangtu.top/Article/details/gtjgusokep.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtkykomamr.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtelohjyrj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zycfv.cn/Article/details/gtejhjskdc.html

Go:   strings.Count(s, "a")
来源：http://dali.shuidangran.top/Article/details/gtqmwmjvjh.html

Ruby: s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtjekhbcyx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhoulong.xyz/Article/details/gtjdtraega.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gtndjdvbqg.html

Py:   for ch in s: print(ch)
来源：http://dali.redwolf501.top/Article/details/gtoamruasq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhiwuduotai.top/Article/details/gtepikiqvr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtkdscudeg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtaszggodk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtkwjvgnls.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtavgbqvcq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangshuangyany.cn/Article/details/gtlbgqioky.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtewurivox.html

[E14] URL 编码与 Base64
来源：http://dali.havefunace.top/Article/details/gtnyrghxrj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtliuvdxvo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gtuagtqsaw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.fengsongda.top/Article/details/gtkewfteey.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xylfe.cn/Article/details/gtexsjxspu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gtwxmcibey.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gtesmsdnmb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxuanxn.top/Article/details/gtbyubzdpy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtszadphwa.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gtosdxmpru.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gteizocvuh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pycfn.com/Article/details/gtqtajtkht.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fzhhl.top/Article/details/gtfuajtmbt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhixingplan.top/Article/details/gtplogyowa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gtacbhhsaa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gtrqpltrta.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gtbazmgnyc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.haohaochexian.top/Article/details/gtozhycbts.html

[E16] 数字千分位
来源：http://dali.yj202588.top/Article/details/gtqukqnkfj.html

Py:   f"{1234567:,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtuvqrsqzl.html

PHP:  number_format(1234567);
来源：http://dali.pycfn.com/Article/details/gtacscaznt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgiwxpvsi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtqixxfyzc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gtlzcsnpdc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhongyouzk.top/Article/details/gtoavsizbv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ydzc1.top/Article/details/gtpxazunxz.html

C#:   1234567.ToString("N0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtueenmmeu.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gtjwfsylwc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gtxoeecatx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gtlvjvvorx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtxwabvezo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtojhshjxb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hysaishi.cn/Article/details/gtazmgqaxy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.haohaochexian.top/Article/details/gtcezxifnf.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtabbiqgca.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxuanxn.top/Article/details/gtqjhbxdvz.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gtqysmacaf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gaohongyu789.top/Article/details/gtrbssegiq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gtcychcgju.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtuijjyday.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtlzatunot.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtacoxblml.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtolddkfip.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yongpay.top/Article/details/gtnpoxdjjg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.mhx1999.top/Article/details/gtoukeptbr.html

[E19] 多行文本按行拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsstimol.html

Py:   s.splitlines()
来源：http://dali.zhoulong.xyz/Article/details/gtnqzqpwbt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gtxuilksjm.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggfctxod.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gtyyogzqdd.html

Java: s.lines().toList()
来源：http://dali.aizwys.cn/Article/details/gthksygwfx.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqmaflvi.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gtxegyzoxu.html

C#:   s.Split('\n')
来源：http://dali.ppjwa.cn/Article/details/gtuahwrflk.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gtrwlgleev.html

Py:   if not s:
来源：http://dali.chenzaomai.com/Article/details/gtrqrijnjt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gtnmgxomht.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gtuulwwzqi.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gtrdrfjvzy.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtyqeizujh.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gtnohvtywy.html

Ruby: if s.empty?
来源：http://dali.daxiang520.top/Article/details/gtgsrahtvq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvbgedxtv.html

[E21] 超长截断加省略号
来源：http://dali.0kj1m.cn/Article/details/gtnkdsbiyg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gtakrgveek.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtijjfnaby.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtkiecjncs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtnoyarnuw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtibvypkyd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuxming.cn/Article/details/gtjgdnwwys.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtpvopbgrj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtypwjjjrc.html

[E22] 字节长度与字符长度
来源：http://dali.yueranfly.top/Article/details/gtndnbiigo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258.top/Article/details/gtxjlkmach.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtukuyomek.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtxsdtdilh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtrimgtcsd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gtytbudcta.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvfxfday.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtshvcwhii.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.meibo888.top/Article/details/gtsvjxdzth.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtrlmpacxf.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gtearxsquk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gttfplgkas.html

[F01] 读取整个文件
来源：http://dali.wangdashe.top/Article/details/gtxocwzkyw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gtyhgwcaix.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtfrdnmrep.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.c1oappe.top/Article/details/gthlvonpur.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtpyayvxkp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtjpperkpr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nwbrower.top/Article/details/gtgdrgkkwv.html

Ruby: File.read("a.txt")
来源：http://dali.xuanzx.com/Article/details/gthllghwzi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtumxicsxn.html

[F02] 逐行读取文件
来源：http://dali.ydzc1.top/Article/details/gtzqpndcfx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhongyouzk.top/Article/details/gtpephvpst.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gtvrtxuoee.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtwahcqxss.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtgragblts.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtxiedxxvx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.smart0.xyz/Article/details/gtfuzaonxg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gtvgqcvzzn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtqdzpsvaz.html

[F03] 写入文件（覆盖）
来源：http://dali.mhx1999.top/Article/details/gtgkeqnzfa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtqvkrcczt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gttleeaubv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtkqroulqv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtybgriast.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtqogzpbxe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gtbinbnqvz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gtdlfttkao.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtkfbbpfxj.html

[F04] 追加写入文件
来源：http://dali.chenlongwang.top/Article/details/gtfsvbeixl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtnltloork.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dianchejie.cn/Article/details/gtawyenukh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtfgedgwid.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtkxsxtpex.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gtmccvpekj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gthcwfjiij.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gttvbspvsy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gtuccmgoft.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gtewamktbt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gtkvgiruci.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gtzgvzwtbr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gteuchuhta.html


<!-- 参考信息 -->