代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gtoocwyhkn.html

JS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtyumguogq.html

TS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gtidxbfxvy.html

Java: list.contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtzurluxli.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gtvasqzeux.html

Ruby: arr.include?(x)
来源：http://dali.aibaodan.cn/Article/details/gtyfoeswjd.html

C#:   list.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtdbdeefik.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ybcxt.top/Article/details/gtvprbhztc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtsyzlifso.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.andypj.xyz/Article/details/gtwdaccbwb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gtgxjcghhj.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gtglxwjtdz.html

Java: new ArrayList<>(list);
来源：http://dali.c1oappe.top/Article/details/gtjnztoxrd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gtceyficij.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gtlpbcehqi.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gteennoezg.html

[D23] reduce 累积计算
来源：http://dali.xuanzx.com/Article/details/gtshqsrvca.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangdashe.top/Article/details/gtrsteqsmw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yangfankeji.com/Article/details/gtbjeuwvwv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gtukzxkbwg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtgqrkhbnl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhixingplan.top/Article/details/gtwxnawgnm.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtrmyrzwbi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nwbrower.top/Article/details/gttalpkjka.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gtychsbxau.html

[D24] 字典 / Map 基本操作
来源：http://dali.kuanghao11.cn/Article/details/gtrxinpnit.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gtrnwstyrl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gzhubu.top/Article/details/gtobfblzny.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gtwifywqze.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtfjegqzax.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gtozagvxsv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gttcrvunww.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.mhx1999.top/Article/details/gtvworexst.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gtznenrzza.html

[D25] Set 集合去重与交并差
来源：http://dali.guowangkeji.top/Article/details/gtyplukscy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtecrvofnw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.snrcjt.cn/Article/details/gttrhvchwc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aibaodan.cn/Article/details/gttzkqpknq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hongshengwenyu.top/Article/details/gtclogljrd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xziqi.cn/Article/details/gtgtyjadyl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.haohaochexian.top/Article/details/gtnelfsszn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.svipenyu.cn/Article/details/gtrylmqrlz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gtrcvswtnr.html

[D26] 数组转字符串
来源：http://dali.xylfe.cn/Article/details/gtzmwupliw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gteolafylq.html

PHP:  implode(", ", $arr);
来源：http://dali.chenzaomai.com/Article/details/gthvbpdhob.html

JS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtacwiccck.html

TS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtpkbzolje.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gtmiqfgruw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcamgtghg.html

Ruby: arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtollehplh.html

C#:   string.Join(", ", list)
来源：http://dali.cheryme.top/Article/details/gtwfujnyal.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtndvldhov.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gtdvfgevnb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtilqlzkou.html

[E01] 拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtjfnrwahm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.snrcjt.cn/Article/details/gtoorxdrha.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.havefunace.top/Article/details/gtlsgnmznd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtgfxtiwew.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtwtmoduzs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ehwqpu.com/Article/details/gtyzjtujtl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hywenlv.cn/Article/details/gtpjpfaynf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gotoacloud.top/Article/details/gtuavizepl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.havefunace.top/Article/details/gtydiqpfod.html

[E02] 重复字符串
来源：http://dali.redwolf501.top/Article/details/gtddprjuao.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtuyzylzwu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfogyvqek.html

JS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtamdnocnd.html

TS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtigkgmnfq.html

Java: "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtphnxmver.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ppjwa.cn/Article/details/gtiquahamc.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gthizexxry.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.bjfxy.top/Article/details/gttugocvnd.html

[E03] 截取子串
来源：http://dali.ydzc1.top/Article/details/gtkoialjqp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhongyouzk.top/Article/details/gtbgqnsaxi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtclasobja.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtjfaciwca.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtuchrswny.html

Java: s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtslwegpwg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtuxfftknc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gzhubu.top/Article/details/gtimufeane.html

C#:   s.Substring(1, 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbtymebo.html

[E04] 查找子串位置
来源：http://dali.chenjidiqi.icu/Article/details/gtegqphhak.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtyvrwrufh.html

PHP:  strpos($s, "x");
来源：http://dali.316326.xyz/Article/details/gtrfjjjtxa.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gtpxeydalr.html

TS:   s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtyangrsuo.html

Java: s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtssychont.html

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gtrlooepuu.html

Ruby: s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtktwvkgpa.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtsiwgkxzx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ppjwa.cn/Article/details/gtyekirogn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.mhx1999.top/Article/details/gtdikhhgfh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuanzx.com/Article/details/gtcfygdctt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtpmmpnaxd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtoyuaaxrd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtluplxjke.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258.top/Article/details/gttbfnfkpg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gtghrjygne.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtjgtrreos.html

[E06] 替换子串
来源：http://dali.yuxming.cn/Article/details/gtxubsdixt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gttcrzrzfw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dashuyun.cn/Article/details/gtqodirnds.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtvqizylps.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtaqualpyv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtsuowsbvk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtdfefftew.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrrnkjza.html

C#:   s.Replace("a", "b")
来源：http://dali.pycfn.com/Article/details/gtyvfgdqcm.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gtrosdckpm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gtzkeoehyh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtjyjgymwy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cqqwz.cn/Article/details/gtdbtllwro.html

TS:   s.split(",")
来源：http://dali.fzhhl.top/Article/details/gtglukfpak.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pengpengdd.cyou/Article/details/gtvatforwi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hysaishi.cn/Article/details/gtmzktfoif.html

Ruby: s.split(",");  s.split
来源：http://dali.gotoacloud.top/Article/details/gtwrsauxkv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.birdmap.top/Article/details/gtzginpgai.html

[E08] 数组按分隔符合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxtqhxqp.html

Py:   ",".join(items)
来源：http://dali.cucudq.cn/Article/details/gtfhbqliac.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gtpudvftjz.html

JS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtxpjubkaz.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtfjiuheaf.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtkaykneiv.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttokpbckb.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwqyrmwl.html

C#:   string.Join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtceseioks.html

[E09] 去除所有空白字符
来源：http://dali.cashguo.top/Article/details/gtstwdxupo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xylfe.cn/Article/details/gtxbdbmdfc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ppjwa.cn/Article/details/gtykgifoev.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gtxuotovpp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtpcvmskpu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gtdihkxyoz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangdashe.top/Article/details/gtommnllpj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtkaukbkrp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xinyue.icu/Article/details/gtpeholpnu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.svipenyu.cn/Article/details/gtwhdrhhdo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtebmerbqy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zycfv.cn/Article/details/gtlqlxunij.html

JS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtnkjigbpk.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtehhqpmyj.html

Java: String.format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtyacawwbx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gthknhvdoz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtoilppcyn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gaohongyu789.top/Article/details/gtgrjuujgy.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gtfeyzfadj.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtjcdijvfp.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtngdivemv.html

JS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtveaddcts.html

TS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtsftrlfhw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gttuinnjnj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zycfv.cn/Article/details/gtmrxhplqr.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtdvxvimxn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtbuczkjey.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gtoqpmtdih.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtqqznlnag.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gtnnqrhkzj.html

JS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtnrpkyxee.html

TS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gteyciuyxv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gtvuenpyxx.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gtfbcdrnbm.html

Ruby: s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtbyapdebx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yvedp.cn/Article/details/gtyercoyfi.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gtylwcfbkk.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gtiiqvlodm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gtnbchrypl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gtgtzzdrem.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtbvuzkrcz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtgrowawth.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cqqwz.cn/Article/details/gtlmxwruqc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gtbxjwerjx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gtnbldzpmc.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gtqwsrmcin.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guannengcc.top/Article/details/gtvbdkrjqf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gtrbpjlils.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ehwqpu.com/Article/details/gtpjwrxprd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gtnxfhrulg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtmqarksfn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gtnjrpbvmm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuxming.cn/Article/details/gtonacdswj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtjychrwnl.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gtnkoukium.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gtgqtqqvao.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gtbidnjwqp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gtidjvoljm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gthhphbztr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gtoxyoslgn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gtzyececax.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gtcuwwxpoc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gtktyiftlg.html

[E16] 数字千分位
来源：http://dali.jianghu66.top/Article/details/gtioazkcgr.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gtheprxdih.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gtxzfkuzce.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtbyllzlmx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtsjliezwb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gtskixvlng.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aizwys.cn/Article/details/gtfequgxtb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guowangkeji.top/Article/details/gtufvwyawz.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gtkmmtyijb.html

[E17] 首字母大写
来源：http://dali.nanxuanxn.top/Article/details/gtteprtfja.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhixingplan.top/Article/details/gttzeaocfu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cashguo.top/Article/details/gtpgznrmpt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtinqqrkyw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtrprbrelk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gtncuysbsl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsybbcmde.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqidcufgl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gtotipawkn.html

[E18] 模板占位符替换
来源：http://dali.yangfankeji.com/Article/details/gtveycjxaz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nwbrower.top/Article/details/gtpfbzhqsl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuanzhike.top/Article/details/gtvklchelm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtpupamefm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtjehlgoqq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtnacrzdmr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtnztwyvgr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gtynuhbqwu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gtyuboevtm.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gtpjyiaqdr.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gtuqjqhdru.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtazmadzei.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtcxcotzjk.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtlohctnec.html

Java: s.lines().toList()
来源：http://dali.jlsjyb.cn/Article/details/gteoskfguu.html

Go:   strings.Split(s, "\n")
来源：http://dali.yangfankeji.com/Article/details/gtunzhrcjq.html

Ruby: s.lines
来源：http://dali.birdmap.top/Article/details/gtkkraihku.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gtsrjkvfft.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gtrvngrlfa.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gtocqwxdgd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gtwfjxwqsp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyvdthfa.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gtlahidohy.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzxckdvje.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gtwdefwuep.html

Ruby: if s.empty?
来源：http://dali.jianghu66.top/Article/details/gtpareqiqb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnqzz.top/Article/details/gttzoxyblv.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gtfhfqezbn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shuidangran.top/Article/details/gtjxbwxknv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtvmfaqpbi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gthzomnvqz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtdlqcnfyt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtqvwebzau.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gtdrdvxyyb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gteqsunehs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtlaihyfgg.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gtfrrqiskv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuhehpcj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtccsirumy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtkyzyhhib.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtejjabimw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258.top/Article/details/gtsxvnooxe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gtgpezaldy.html

Ruby: s.bytesize;  s.length
来源：http://dali.sweek.top/Article/details/gtxzhozwgt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hfpthk.cn/Article/details/gtazwcunoo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtkuzquqpc.html

F. 文件与目录
来源：http://dali.meibo888.top/Article/details/gtqcfznaib.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtslevzfzs.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlvipnjb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gtqsgfzkwf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cheryme.top/Article/details/gtleuayane.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gtktfxjtog.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gthqaevovx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtrwrfcgib.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinghuilouyu.cn/Article/details/gtjigjskoe.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtxhxphxyy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtwatrfrjn.html

[F02] 逐行读取文件
来源：http://dali.xinyue.icu/Article/details/gtkdtavkeq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gtwwwxvblx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gtwadqokqr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtbqrfygbk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gtokllbpzo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtuqksosnh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gtvnwotasl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gtrxyitots.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gtvlciphqq.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuuoigcwk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sufxvd.cn/Article/details/gtsgkmkjro.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtyuiulgjy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gtitnhyruo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtbgegbcmk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtufqeptst.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gtdfkggska.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtndntcytt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtovkycpex.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gtnnriyrra.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sweek.top/Article/details/gtcymgnyia.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gthomgcfaq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtqqcuyihm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtolfywxhn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gtagxhfdtb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gtmjpvygev.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gogol.net.cn/Article/details/gtvjenayme.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtxyvrenni.html

[F05] 判断文件或目录是否存在
来源：http://dali.smart0.xyz/Article/details/gtmlcekhpk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gtdwcmzoov.html

PHP:  file_exists("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtcqghvovd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtowvmyofn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtjfvyjnwz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gthicxwbaq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gtmvpkpwwm.html

Ruby: File.exist?("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtqqktaxqb.html


<!-- 参考信息 -->