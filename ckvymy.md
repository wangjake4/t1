代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hfpthk.cn/Article/details/gtnawgzlvv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.svipenyu.cn/Article/details/gtxuquoswc.html

Go:   // 手写 map[string][]T
来源：http://dali.yvedp.cn/Article/details/gtfjmhnnex.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gtoqcshfmt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gtrikspqzj.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gtlhjpatxe.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtchviqymf.html

PHP:  array_count_values($arr);
来源：http://dali.bjfxy.top/Article/details/gtcpwemvbb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtblfdusuz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gtbafalozf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gtlxgtofho.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gtkklevppb.html

Ruby: arr.tally
来源：http://dali.daria6918.cn/Article/details/gtynwvrqxj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ivvv.top/Article/details/gttiodtbyg.html

[D21] 判断是否包含某元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhozoqzv.html

Py:   x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtiavlhysu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yanxiufei.cn/Article/details/gtiqzysind.html

JS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtuwmocuhz.html

TS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtknklhopd.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gteontaeku.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtgoppxnvq.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gthkssyipv.html

C#:   list.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtylxunnjo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gturlgnqds.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtiliiaixt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gtlsuatajx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gtcnbasuef.html

TS:   [...arr];
来源：http://dali.tianlin.xyz/Article/details/gtnhgmhvog.html

Java: new ArrayList<>(list);
来源：http://dali.xinyue.icu/Article/details/gtrpfoyctg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtifsebkzd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yongpay.top/Article/details/gtgpxrizca.html

C#:   new List<int>(list);
来源：http://dali.fengsongda.top/Article/details/gtwgkssjge.html

[D23] reduce 累积计算
来源：http://dali.yj20258888.top/Article/details/gtujeziaka.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gtefwzrefj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtrfobeqka.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtculqonll.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtvlkrispy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbycfsrl.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtyisgtaee.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cheryme.top/Article/details/gthirmfezg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gthirhefar.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gtjbpbogya.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtlrpsmwgy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xylfe.cn/Article/details/gtwqpazxyv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hysaishi.cn/Article/details/gtksubwsqm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtqlaulgzg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.quarkkingdee.top/Article/details/gtirwnhqye.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gtqvukvhal.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cqqwz.cn/Article/details/gtnfqvcxdt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gtsqoocmfl.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gtfgreybxs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.9152youxi.cn/Article/details/gtuwdlgcym.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jiagoushi.top/Article/details/gtjfvxaclw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gtsrfjejyr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258888.top/Article/details/gtofzcaqwx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gtflzoucwp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gtfpuiofgn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyiukquc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daxiang520.top/Article/details/gtzbpasbkq.html

[D26] 数组转字符串
来源：http://dali.yuanzhike.top/Article/details/gtndrfbpkh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gtguladlvy.html

PHP:  implode(", ", $arr);
来源：http://dali.redwolf501.top/Article/details/gtraocstiv.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtyalasbxd.html

TS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtepinkypl.html

Java: String.join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gttcquutwh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nwbrower.top/Article/details/gtytveuxwo.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtmbesdnah.html

C#:   string.Join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtzgzmtbqw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtypdcemlv.html

E. 字符串处理
来源：http://dali.tianlin.xyz/Article/details/gtoiwtwdia.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gturinmkbw.html

[E01] 拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtbiayayke.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gtdstvigxj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shzxlz.cn/Article/details/gtnpynydbd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtotndjbke.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gtbefnvmxf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cdnleiting.top/Article/details/gtvbonfign.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgufenzy.top/Article/details/gtffuxqdul.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.316326.xyz/Article/details/gtvfuhjawn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fengsongda.top/Article/details/gthlrlbmne.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gtmyizipnk.html

Py:   "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtugporldt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangdashe.top/Article/details/gtckyyzkxi.html

JS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtnwppgcvl.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggwrkpxu.html

Java: "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtosznebad.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gtgxagrijo.html

Ruby: "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtmsnvhfsu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xinyue.icu/Article/details/gtwluwgcqo.html

[E03] 截取子串
来源：http://dali.birdmap.top/Article/details/gtkkazhnaq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtjwcpzcps.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtlkpzehny.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtwpblpblf.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtolalgndx.html

Java: s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gtcumjvqlh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrhcyjao.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gtjhoarwny.html

C#:   s.Substring(1, 3)
来源：http://dali.tanke756.top/Article/details/gtrujlpxml.html

[E04] 查找子串位置
来源：http://dali.ehwqpu.com/Article/details/gtguvzqkgh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtogsnuvqm.html

PHP:  strpos($s, "x");
来源：http://dali.tanke756.top/Article/details/gtwscnobqt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfzfjrfs.html

TS:   s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtfxqcqsoq.html

Java: s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtqjdcghos.html

Go:   strings.Index(s, "x")
来源：http://dali.aibaodan.cn/Article/details/gtjmvyqhdm.html

Ruby: s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gtrtasbkmg.html

C#:   s.IndexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gteokbjtdy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj202588.top/Article/details/gtmrokywyr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hysaishi.cn/Article/details/gtuaoocrih.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyrsvuhe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtwtqwbblg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gtbbnuuplq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gthbdzxfxc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gtnfokkxic.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gotoacloud.top/Article/details/gtiifbqzeo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtfbeethil.html

[E06] 替换子串
来源：http://dali.jqgufenzy.top/Article/details/gtgkecsimw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gthzfhngih.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guowangkeji.top/Article/details/gtvcnbrbun.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtmgmmloqf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtzmdbfdgh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtponzugav.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtrlvtgihm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtttlgvkww.html

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtzalqzglt.html

[E07] 按分隔符拆分
来源：http://dali.xinyue.icu/Article/details/gthksubjpp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yonumen.top/Article/details/gtotdaoeix.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nwbrower.top/Article/details/gttrxtamtt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhengqikj.top/Article/details/gtdaospsvk.html

TS:   s.split(",")
来源：http://dali.yj202588.top/Article/details/gtbwndbxvr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.0kj1m.cn/Article/details/gtbmgppues.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gtmmazarwz.html

Ruby: s.split(",");  s.split
来源：http://dali.andypj.xyz/Article/details/gtzlgvckri.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zdqjudy.top/Article/details/gttqrycrru.html

[E08] 数组按分隔符合并
来源：http://dali.ivvv.top/Article/details/gtlmazvnkn.html

Py:   ",".join(items)
来源：http://dali.smart0.xyz/Article/details/gthjszbwna.html

PHP:  implode(",", $items);
来源：http://dali.wangdashe.top/Article/details/gtaghmagao.html

JS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtdtdpczqu.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtstdgnunm.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtvvzazssh.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjpvvtxp.html

Ruby: items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtuocwrvdi.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtqnducmcg.html

[E09] 去除所有空白字符
来源：http://dali.fengsongda.top/Article/details/gtctkaivys.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shzxlz.cn/Article/details/gtuobkmopi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daria6918.cn/Article/details/gtyuwztyqt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtcfwopora.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhmiznra.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsbzyvbj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmydzftfw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sweek.top/Article/details/gtsonkkcza.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtporgfrzs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.meibo888.top/Article/details/gtcgmdvgmx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtbajokzho.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gtnddicqfq.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtrjsrkzzp.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtsqwxjtpm.html

Java: String.format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gthktivyaz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmisphmc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtabyslhqi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gtlifleeep.html

[E11] 反转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtgulhaemb.html

Py:   s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtajpzgkyd.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gtyoiizaxg.html

JS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtywciekfh.html

TS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtwoymsqrl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gthrdkqsno.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.svipenyu.cn/Article/details/gtngppaofa.html

Ruby: s.reverse
来源：http://dali.tian-w.cn/Article/details/gtlcssczmy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtjhmasyxp.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtsbegclpc.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtieuoyxbx.html

PHP:  substr_count($s, "a");
来源：http://dali.cucudq.cn/Article/details/gtscqlgolh.html

JS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtijgekyhw.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtwprnhvfv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gtkzcosvpa.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvoplipb.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtpqwjwwma.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tianlin.xyz/Article/details/gtmjdwczma.html

[E13] 逐字符遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtkvtlpeuo.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gtpzkvnjfz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxinkj.top/Article/details/gtuwqtunqb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtvlgnvaab.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtkqzhacva.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtdwgbzkxx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbeheyqu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gtskxubcfb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtybccpbrj.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtxqnpfqje.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtolonabxo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fengsongda.top/Article/details/gtmuuxhfun.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.andypj.xyz/Article/details/gtmhglwxfo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.svipenyu.cn/Article/details/gtstnlmdfg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtnkssdwpv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aizwys.cn/Article/details/gtyqkxbhgh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gtjpgjizxd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gtcxtcmlei.html

[E15] HTML 转义 / 反转义
来源：http://dali.guowangkeji.top/Article/details/gtlyykbloq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtjarhjwwe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gthrkgpfho.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gtxxrtsxdd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnxiangtu.top/Article/details/gtuleaxbqv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gtmlxyiced.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guowangkeji.top/Article/details/gtnkjqvkmy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gtzeduzftt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.haohaochexian.top/Article/details/gttrgbjugo.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtcptvbxhr.html

Py:   f"{1234567:,}"
来源：http://dali.zhongyouzk.top/Article/details/gtokcygzfl.html

PHP:  number_format(1234567);
来源：http://dali.pengpengdd.cyou/Article/details/gtzccbczje.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gtyktwxtpf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtaoibqevw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtyvzdkvmr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xylfe.cn/Article/details/gtxparjnhv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gtgpvuikwk.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gtrlsmgrsd.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gtxepxcxgw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gttxexuxiq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gtpznmiryq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtsawpswjm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtulvnuhxo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gtzivnnqyy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gtnqgeylyo.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtsbafealq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gturakvpzn.html

[E18] 模板占位符替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmxwojso.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.haohaochexian.top/Article/details/gtnpdlgchd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gteefuwqrr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gthjhugxpk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtuywaynkw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtzqwfvecv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtzuapyahd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hfpthk.cn/Article/details/gtbatptayw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gtfaggyvus.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gtbvernedw.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gtjriehknj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtshsfummv.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtfshahujd.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtwphwkpxc.html

Java: s.lines().toList()
来源：http://dali.sufxvd.cn/Article/details/gtzsjkmytv.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gtvchuwlnl.html

Ruby: s.lines
来源：http://dali.dashuyun.cn/Article/details/gtitbebydt.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gtpxguzohj.html

[E20] 判断字符串是否为空
来源：http://dali.yueranfly.top/Article/details/gtweuafyes.html

Py:   if not s:
来源：http://dali.yuxming.cn/Article/details/gtiejiovqr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqbcbtaq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfaudjndr.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyatghes.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlrronjd.html

Go:   if s == "" {}
来源：http://dali.gaohongyu789.top/Article/details/gtyshqnunh.html

Ruby: if s.empty?
来源：http://dali.jqgfzy.top/Article/details/gtrrxjaufz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gttgmafpwq.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gtdujvixhq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yanxiufei.cn/Article/details/gtratypstn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gttcxdjqam.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtrghcgmfo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtpgivniwf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtxukshvqk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gtbbatgsxi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtvlievjyw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtiugrjply.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gtluyfkijb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gtcsueycmi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtwmjpzfwb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtafglfohx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gtbnhxkcvq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtcregmfbw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gtvwjmbtqu.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtncjnmvwf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnvfbcpk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtndkoters.html

F. 文件与目录
来源：http://dali.jianghu66.top/Article/details/gtxofzefhw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbxtegnhm.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gtuxpudqgp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtgcyfccsn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtzwpgxvht.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gtzcspnwkn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.meibo888.top/Article/details/gtosgidplb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gthyypccwd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xinyue.icu/Article/details/gtcxhaqeih.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtzfxxfqbi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj202588.top/Article/details/gtpkznfnwy.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzavwxkl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guannengcc.top/Article/details/gtmrupmexr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tianlin.xyz/Article/details/gtlhiworew.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtkikypbio.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtmhplyjis.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmxwqmvo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gtymnjcebs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gtobvyenka.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhengqikj.top/Article/details/gttksrhyeh.html

[F03] 写入文件（覆盖）
来源：http://dali.cdnleiting.top/Article/details/gtelssnope.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtaasrqtdq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtpgbibjdt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtolfmbngq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtptbgdxvb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gtoxpapfpa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cucudq.cn/Article/details/gtpplaqoij.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258888.top/Article/details/gtwghhqltp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtaqfskzya.html

[F04] 追加写入文件
来源：http://dali.cdnleiting.top/Article/details/gtlsawkxww.html


<!-- 参考信息 -->