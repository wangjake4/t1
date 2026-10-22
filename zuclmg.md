代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gtqeumltlk.html

[D20] 统计每个元素出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapcuzcxh.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gtgkqieqsa.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtiddtjbuz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gtudzhiagv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbdsvfjy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.snrcjt.cn/Article/details/gtwlsdfeep.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gtevvufvix.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gtaomluvgp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gtyrupbhbq.html

[D21] 判断是否包含某元素
来源：http://dali.xuanzx.com/Article/details/gtyfiqgxxd.html

Py:   x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcdbcqjt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cashguo.top/Article/details/gtmhzdsoav.html

JS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtjwvloqfb.html

TS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtfclinacv.html

Java: list.contains(x)
来源：http://dali.xylfe.cn/Article/details/gtvgnhnjlv.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gtesdxzydh.html

Ruby: arr.include?(x)
来源：http://dali.cheryme.top/Article/details/gtzigpxekm.html

C#:   list.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtanaurikt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sysykeji.top/Article/details/gtlkpcrvnk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gtxlhvipoz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangdashe.top/Article/details/gtppduvzfk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.andypj.xyz/Article/details/gttzfscmlz.html

TS:   [...arr];
来源：http://dali.cucudq.cn/Article/details/gtyghwbrcz.html

Java: new ArrayList<>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gteufvguuf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.9152youxi.cn/Article/details/gtxgugfzco.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gteosifghe.html

C#:   new List<int>(list);
来源：http://dali.hnqzz.top/Article/details/gtrvilzain.html

[D23] reduce 累积计算
来源：http://dali.cqqwz.cn/Article/details/gtdicasccr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gttqjaeddr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.redwolf501.top/Article/details/gtmlnkjetn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gtrulcgrcv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtcsdtuxxj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guannengcc.top/Article/details/gtytazxwzw.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtossdgubh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jyoumei.cn/Article/details/gtdjgpzkvu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gtyjemnrrt.html

[D24] 字典 / Map 基本操作
来源：http://dali.zdqjudy.top/Article/details/gtxgjizgqa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gtryxbugkl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jyoumei.cn/Article/details/gtslpcmgln.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtldsgfnvv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtyqpyslez.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtsfgvckmt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.birdmap.top/Article/details/gtmmsxqpqy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gtempkksqx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daxiang520.top/Article/details/gtbdwzfsgd.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gtdjmiuvsy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvqrwchj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtwbohatvb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gttuntbgps.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxinkj.top/Article/details/gtobiyario.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.316326.xyz/Article/details/gtvzupbnvf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fengsongda.top/Article/details/gtaxjfhfjo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.meibo888.top/Article/details/gtmfjzjycy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gzhubu.top/Article/details/gtqrvzafla.html

[D26] 数组转字符串
来源：http://dali.sweek.top/Article/details/gtugiqwxus.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hysaishi.cn/Article/details/gteckfrnpx.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gtbkjrhpkm.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtpibkrdfa.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtbfckpokq.html

Java: String.join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gttnirumlw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xinyue.icu/Article/details/gtazdixswr.html

Ruby: arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtijdrzbet.html

C#:   string.Join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtrryaniqm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtftjjykjq.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gtggtqkmhe.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtphgwsaxz.html

[E01] 拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtzfodsosu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.feifeiyinyue.top/Article/details/gtatkdaejl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gtftlmcvei.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtpwdyfctx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtecvkljxj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenlongwang.top/Article/details/gtjhqvlnak.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ppjwa.cn/Article/details/gtmtervvyj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cashguo.top/Article/details/gtymuwotwv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtvqqjnney.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtzgasvzxa.html

Py:   "ab" * 3
来源：http://dali.ivvv.top/Article/details/gtjdkgzepu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuanzx.com/Article/details/gtembcmozk.html

JS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtpluxgjgi.html

TS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtiulnuqlm.html

Java: "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtrrgqxmne.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.birdmap.top/Article/details/gtrgwutcpx.html

Ruby: "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gtgyzzradm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.316326.xyz/Article/details/gtxweoleoy.html

[E03] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtjnrwzamc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gtqfvtfhfj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gthcxaybmi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtkpckamyw.html

TS:   s.slice(1, 4)
来源：http://dali.sweek.top/Article/details/gtodyorwfs.html

Java: s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtkrjhyuec.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gtglguybcb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258888.top/Article/details/gtsiypdvro.html

C#:   s.Substring(1, 3)
来源：http://dali.hammf.cn/Article/details/gtcqkorzox.html

[E04] 查找子串位置
来源：http://dali.gogol.net.cn/Article/details/gtwnfehibq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtabectaoq.html

PHP:  strpos($s, "x");
来源：http://dali.meibo888.top/Article/details/gtaqqfjywf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozyhqrtb.html

TS:   s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtrvyvowzf.html

Java: s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtkuansdgu.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlolsrbhl.html

Ruby: s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gtwnrmnbnw.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtpsbcqcvh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirjtzrjt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtvjrqbdtt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gtulmoqulo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtwfokakry.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.haohaochexian.top/Article/details/gtjfkzcwso.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtdfptrabb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ivvv.top/Article/details/gtsrbilytz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sufxvd.cn/Article/details/gtupdejqtk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtbreljrtx.html

[E06] 替换子串
来源：http://dali.snrcjt.cn/Article/details/gtvtnbtloq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gtrbqnesrh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.feifeiyinyue.top/Article/details/gttxawkywb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtkmavxyld.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtqgocezov.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtyvcohykq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gtzguudoxs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtrzfjtmzj.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gttdmhjdmc.html

[E07] 按分隔符拆分
来源：http://dali.yuanzhike.top/Article/details/gtetkpdltg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gtmvwyecnt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtjhzqoctn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.kuanghao11.cn/Article/details/gtferjmjsy.html

TS:   s.split(",")
来源：http://dali.havefunace.top/Article/details/gtcgbvmypj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwrrcnqz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxinkj.top/Article/details/gtsxodfpfq.html

Ruby: s.split(",");  s.split
来源：http://dali.cashguo.top/Article/details/gtpcimoada.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gtmnrlroba.html

[E08] 数组按分隔符合并
来源：http://dali.xylfe.cn/Article/details/gtcmvjyjbp.html

Py:   ",".join(items)
来源：http://dali.cqqwz.cn/Article/details/gtlvoimedh.html

PHP:  implode(",", $items);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygztonuc.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtjzctgtzt.html

TS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtalorvljq.html

Java: String.join(",", items)
来源：http://dali.hnqzz.top/Article/details/gtaahlxghz.html

Go:   strings.Join(items, ",")
来源：http://dali.zycfv.cn/Article/details/gtgxzzlajl.html

Ruby: items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljsbxils.html

C#:   string.Join(",", items)
来源：http://dali.svipenyu.cn/Article/details/gtwbgpzyjz.html

[E09] 去除所有空白字符
来源：http://dali.havefunace.top/Article/details/gtdzoyusst.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtoynllqnm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.bjfxy.top/Article/details/gteanzkdjb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gtfrzspwww.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcgwyeol.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gtpxvwinyk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhengqikj.top/Article/details/gtsxbkfdhp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtiiqoiqph.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtgroljjqk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gtuldzdfvs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtvlxiregb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxuanxn.top/Article/details/gtbiavmvzq.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtqdhhoecu.html

TS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtipnqdppd.html

Java: String.format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtvgwmcxzr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtyvdwfryf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtncedzxrg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gttvoutnyk.html

[E11] 反转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtuoysjknd.html

Py:   s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtesctrdww.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtukqevgsk.html

JS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtmpuigzpe.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtbadhqhzc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gtnokfbskq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.bjfxy.top/Article/details/gtutdmgzpi.html

Ruby: s.reverse
来源：http://dali.hfpthk.cn/Article/details/gtxpyzewey.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtvqhhcwab.html

[E12] 统计某字符出现次数
来源：http://dali.ppjwa.cn/Article/details/gthywjinwp.html

Py:   s.count("a")
来源：http://dali.yj20258.top/Article/details/gtrpxtloku.html

PHP:  substr_count($s, "a");
来源：http://dali.chenzaomai.com/Article/details/gtfvcuccrg.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtipaervxi.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtslfdmkhv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pengpengdd.cyou/Article/details/gtthgezabh.html

Go:   strings.Count(s, "a")
来源：http://dali.xylfe.cn/Article/details/gtbbycblym.html

Ruby: s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvooxsuxf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xziqi.cn/Article/details/gtleamstyn.html

[E13] 逐字符遍历
来源：http://dali.ydzc1.top/Article/details/gtdicgqecc.html

Py:   for ch in s: print(ch)
来源：http://dali.chenjidiqi.icu/Article/details/gtaynkmohe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zycfv.cn/Article/details/gtpknzguqt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtlafwuuev.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtkkbwupqd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtzarmmfmm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sufxvd.cn/Article/details/gtuzwuujfa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hongshengwenyu.top/Article/details/gtcmqdxvre.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daxiang520.top/Article/details/gthvdagmsu.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gtziphxjim.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.havefunace.top/Article/details/gtklkxiuvu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gzhubu.top/Article/details/gtuhvqmioj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.snrcjt.cn/Article/details/gthwqgyadx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzseyzbqz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwuazqrh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gthethlucr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhoulong.xyz/Article/details/gtjsmracvb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtajfvosxk.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgjsgcgy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gtvgpwgoyc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gtwukfgmae.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gtmtaslmio.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zdqjudy.top/Article/details/gtxbdrefwd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ppjwa.cn/Article/details/gtirkvvhlo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gtohdlgvek.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gtasvwjzaw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gtwenzutkv.html

[E16] 数字千分位
来源：http://dali.andypj.xyz/Article/details/gtbqngcddk.html

Py:   f"{1234567:,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtczmfjrcs.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gtigdqpyir.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtyaemhedb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtzshxmogb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ybcxt.top/Article/details/gtodfvjjgi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gtwmfyyulj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtywfqqtwo.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gtaojaozol.html

[E17] 首字母大写
来源：http://dali.kuanghao11.cn/Article/details/gtfkyfirld.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gtflzpibbn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxtvxxsz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtptshsxog.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gteouksreo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvtemami.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtyelsnzbq.html

Ruby: s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtpcuuypid.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj202588.top/Article/details/gtvmojdrgl.html

[E18] 模板占位符替换
来源：http://dali.birdmap.top/Article/details/gtjvsbatst.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gtwtlpawth.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgfzy.top/Article/details/gtkisvzlof.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtozjtjfdz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtobiyegvv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtvjjyghha.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtamozavkm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gttnlxuyfp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dianchejie.cn/Article/details/gtatvcmfiz.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gtrlawyhzw.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gtohcewokf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtmjmhnlcv.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtgcrkssps.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtphlzschv.html

Java: s.lines().toList()
来源：http://dali.yuanzhike.top/Article/details/gtacihmsjj.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gtxrejzspn.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtkktrkmbx.html

C#:   s.Split('\n')
来源：http://dali.pycfn.com/Article/details/gteqvwdrdq.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gtnwacixoz.html

Py:   if not s:
来源：http://dali.yuxming.cn/Article/details/gtfawwrich.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jyoumei.cn/Article/details/gtusopyfze.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gtagzldllu.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gtxqajldiw.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtgznrdgmv.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gtxtamijvz.html

Ruby: if s.empty?
来源：http://dali.sufxvd.cn/Article/details/gtcvndyxsg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gtjzbkkkvg.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gtgqexoaen.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.meibo888.top/Article/details/gtoqjlvthp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtjsjfstrs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtudwtmtkt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtodenmhjh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtavqraeaf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gzhubu.top/Article/details/gtspazpefh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtegdrpwbo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtehjjjlov.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gtnqrnlrof.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.0kj1m.cn/Article/details/gtpamfklkp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtjjbatahn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gteyvrvuev.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtyqgejsos.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jiagoushi.top/Article/details/gtnmlcdeyp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthszysjz.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtzawahwlh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gthxoqqzne.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtceoyxgpt.html

F. 文件与目录
来源：http://dali.yj20258.top/Article/details/gtbozoaipc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtugoiwdxh.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gthrgqejfw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvjwolwd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtmdxlfmur.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gtgpepzdpi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtbqkqsswr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtzclwnpui.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gtmdotwmmz.html

Ruby: File.read("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtlinssrrd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.havefunace.top/Article/details/gtejozcvjs.html

[F02] 逐行读取文件
来源：http://dali.chenlongwang.top/Article/details/gtyxubvbwh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gtgplyemnb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gtlpllqqrn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gtpjumhogq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gteidmyfwg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtstvfdfin.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgfzy.top/Article/details/gtvpnroobz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdicfoar.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cucudq.cn/Article/details/gtkxhkcjtp.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeqzthlv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xziqi.cn/Article/details/gtlrgefiwl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmokspuex.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gthmixjlor.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gthqwxnveu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gtrqyerdrc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gteovsfesr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtgagfxayq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtaulpnsby.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gtfzrqfqcd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtguszxoli.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guowangkeji.top/Article/details/gtasstatfw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtjtmvghxg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtrqewfdkg.html


<!-- 参考信息 -->