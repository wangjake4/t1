代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fgwzqjgg.html

JS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2mrkifylv.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtatngun.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2afchvhyb.html

Go:   slices.Contains(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2jxleuexw.html

Ruby: arr.include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zueotwuv.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gt2uvuhdrgt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.birdmap.top/Article/details/gt2cvirffrr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2baobxdan.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gt2crhjtzul.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.316326.xyz/Article/details/gt2lvuckrpe.html

TS:   [...arr];
来源：http://dali.jianghu66.top/Article/details/gt2sjxmxidf.html

Java: new ArrayList<>(list);
来源：http://dali.tian-w.cn/Article/details/gt2ctycvvzg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xinyue.icu/Article/details/gt2ovqlwbfc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gt2hlptriem.html

C#:   new List<int>(list);
来源：http://dali.yueranfly.top/Article/details/gt2rrbfvzih.html

[D23] reduce 累积计算
来源：http://dali.cqqwz.cn/Article/details/gt2dpwrjndo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2zaibsawu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2pomrvjmr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2iuivzurk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2zjtknvkv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gaohongyu789.top/Article/details/gt2vfiyspvh.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gt2wfyprvrt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shangyingyoupin.top/Article/details/gt2mpzefgpq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jiagoushi.top/Article/details/gt2ftrmmgol.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gt2qgqvctzi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2ohdhiwjo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gt2wjpldfyh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qabtktxd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sxryk.cn/Article/details/gt2vmdfhlsw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shuidangran.top/Article/details/gt2wpndqboi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.andypj.xyz/Article/details/gt2fbhoglhw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.bjfxy.top/Article/details/gt2vupkfitz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gt2vsefyrsv.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gt2trhknrfa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shuidangran.top/Article/details/gt2jxalhcrb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlcsyrcx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daxiang520.top/Article/details/gt2aolslewh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kdbenajf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ppjwa.cn/Article/details/gt2ysgnawzf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gt2napbqmbp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gt2ppydhqpp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gt2xklghhdc.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2kgzrfidn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2uucocaog.html

PHP:  implode(", ", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2mfsrtehu.html

JS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gt2twhaudpt.html

TS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gt2okgjzdzy.html

Java: String.join(", ", list)
来源：http://dali.meibo888.top/Article/details/gt2wrdmvuqg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxinkj.top/Article/details/gt2tyubvpbg.html

Ruby: arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2jadhkrpa.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gt2uwlxkpnp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2vbynmuiy.html

E. 字符串处理
来源：http://dali.ybcxt.top/Article/details/gt2oeydbnil.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2nysnyyxd.html

[E01] 拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gt2aiawvqha.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aizwys.cn/Article/details/gt2dsrrdusm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yangfankeji.com/Article/details/gt2njypjvrm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gt2ufjvsyat.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gt2zpqgljhx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxinkj.top/Article/details/gt2kuqtjeda.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnqzz.top/Article/details/gt2pmwfuaxy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangshuangyany.cn/Article/details/gt2bbnmqdbj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2zrqbiyxc.html

[E02] 重复字符串
来源：http://dali.jinqigufen.top/Article/details/gt2fuuczkga.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gt2ittgopxk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwgbjava.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gt2brixarqa.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gt2zkahbkaq.html

Java: "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2scuoerll.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2anxfuqws.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gt2ezbcesnk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gt2dpjyxrbh.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gt2orpbngsi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gt2sgwswzrc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2smtpmceu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2hbrmmspm.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2cpjronmf.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2gmkahbzi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2vvvgnyjo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytyelces.html

C#:   s.Substring(1, 3)
来源：http://dali.dianchejie.cn/Article/details/gt2fahsuozg.html

[E04] 查找子串位置
来源：http://dali.shzxlz.cn/Article/details/gt2lkusxtbv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gt2pqvsepua.html

PHP:  strpos($s, "x");
来源：http://dali.zdqjudy.top/Article/details/gt2lvbdqnro.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.kuanghao11.cn/Article/details/gt2kgwqksov.html

TS:   s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2pungtsbe.html

Java: s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2melykaky.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gt2bljklvtc.html

Ruby: s.index("x")
来源：http://dali.andypj.xyz/Article/details/gt2uqpfhfmg.html

C#:   s.IndexOf("x")
来源：http://dali.yuxming.cn/Article/details/gt2rshejqlc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cqqwz.cn/Article/details/gt2zscfoavp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangdashe.top/Article/details/gt2msyzjfft.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shzxlz.cn/Article/details/gt2grodsrus.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gt2gumtwgeg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nanxinkj.top/Article/details/gt2mqrvpafp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2bvhdzzqp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgfzy.top/Article/details/gt2zchgafvk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2glgfsrds.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2esblqimo.html

[E06] 替换子串
来源：http://dali.xuetiantiany.cn/Article/details/gt2jrymdpwt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gt2xzlxrfvo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenzaomai.com/Article/details/gt2osftbegq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2eqicttic.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2pnqdpurl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2rvlhuuvp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2iyurzciy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2ugzhfxbr.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2ytuzhgjo.html

[E07] 按分隔符拆分
来源：http://dali.sxryk.cn/Article/details/gt2aykzhrlj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gt2ozjcxlld.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2mhpbwywh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cqqwz.cn/Article/details/gt2rvwirrga.html

TS:   s.split(",")
来源：http://dali.ydzc1.top/Article/details/gt2pafsdodp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gt2clnrdvif.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2sdgbzbfo.html

Ruby: s.split(",");  s.split
来源：http://dali.ehwqpu.com/Article/details/gt2kggraias.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gt2icdbucxo.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gt2cpljzyot.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gt2wjtlalbe.html

PHP:  implode(",", $items);
来源：http://dali.yongpay.top/Article/details/gt2owvdzxgf.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrkshra.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gt2avdjxpbu.html

Java: String.join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gt2xpeqwevs.html

Go:   strings.Join(items, ",")
来源：http://dali.xinyue.icu/Article/details/gt2djhfxoby.html

Ruby: items.join(",")
来源：http://dali.yj20258888.top/Article/details/gt2lvqqytfo.html

C#:   string.Join(",", items)
来源：http://dali.pycfn.com/Article/details/gt2gjkgezwy.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gt2rlmycvjf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.redwolf501.top/Article/details/gt2gmlafpas.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2pmzmqbng.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymkpfoyc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gt2cuzhhlot.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cheryme.top/Article/details/gt2gnialqlq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zblzngna.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tanke756.top/Article/details/gt2gzkstbgu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gt2lbdzcrhb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gt2ovyhbcqu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.c1oappe.top/Article/details/gt2gocvajtx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hysaishi.cn/Article/details/gt2gomofplq.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2weybdezn.html

TS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gt2wiwqdctb.html

Java: String.format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bckhozos.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2gqgbmptt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2dveupigz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gt2atutltcn.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnbkxdl.html

Py:   s[::-1]
来源：http://dali.smart0.xyz/Article/details/gt2cihpzxzl.html

PHP:  strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2eoywmlmd.html

JS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xurawihe.html

TS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2awgpzevc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzefhuqu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gt2urgwizor.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gt2ujgtbcmf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gt2aidklirq.html

[E12] 统计某字符出现次数
来源：http://dali.fzhhl.top/Article/details/gt2vshjckyh.html

Py:   s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gt2uefmtmoh.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gt2bugkdkvh.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2orqwwxsu.html

TS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gt2iezavqqq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gt2gwbqolkc.html

Go:   strings.Count(s, "a")
来源：http://dali.daria6918.cn/Article/details/gt2vvxvbhlc.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gt2prjtbocc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.bjfxy.top/Article/details/gt2gkvnkefl.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gt2iyifvdzu.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gt2qwiwcrok.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.redwolf501.top/Article/details/gt2djkuavtk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2dobluewv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gt2sxuokdqe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sufxvd.cn/Article/details/gt2jnsgyouz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2krtycajm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sxryk.cn/Article/details/gt2sdzfeeym.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hyluvozr.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gt2rsfikbiv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dianchejie.cn/Article/details/gt2mqvtahde.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2hwucfdaj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.c1oappe.top/Article/details/gt2gvsqhhrv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgfzy.top/Article/details/gt2yjkfzmrh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.smart0.xyz/Article/details/gt2edtcqykg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yonumen.top/Article/details/gt2kolistfe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dashuyun.cn/Article/details/gt2lhcgvfld.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gt2cpyxlivj.html

[E15] HTML 转义 / 反转义
来源：http://dali.jlsjyb.cn/Article/details/gt2fizkdmcz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2knovuedc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gt2eeusndyu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hysaishi.cn/Article/details/gt2tbhnvwpv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gt2riqrrycm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gt2kapklzyb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2xtyaparg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwesusyl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuanzx.com/Article/details/gt2tpwljkpv.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gt2ufrgpgjg.html

Py:   f"{1234567:,}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2dlokqlhe.html

PHP:  number_format(1234567);
来源：http://dali.xylfe.cn/Article/details/gt2gadnfijh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gt2tnhkjflc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gt2rxlnuabb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sysykeji.top/Article/details/gt2oczemqfl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2fzhbhbza.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gt2xeejugcc.html

C#:   1234567.ToString("N0")
来源：http://dali.xuanzx.com/Article/details/gt2wgmoonqz.html

[E17] 首字母大写
来源：http://dali.chenjidiqi.icu/Article/details/gt2szmghgtc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gt2ttjogzng.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gt2rttlidik.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fmwuxzgs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdjunvfs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.316326.xyz/Article/details/gt2kvqtbkis.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2gcfojzwc.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gt2cpcpcmpz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gt2qhnboyma.html

[E18] 模板占位符替换
来源：http://dali.jiagoushi.top/Article/details/gt2ufdgjyem.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gotoacloud.top/Article/details/gt2moordahh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tian-w.cn/Article/details/gt2ztajjuee.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gt2jabvkfxt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yinxlvxq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2cpofyfux.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2wysnkwrv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gotoacloud.top/Article/details/gt2zeqhkouj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gt2khtxtwsq.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gt2guawfkim.html

Py:   s.splitlines()
来源：http://dali.yj20258.top/Article/details/gt2ghgkzoma.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2bvlrnhzh.html

JS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gt2zepivgbm.html

TS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gt2iuzkkjsl.html

Java: s.lines().toList()
来源：http://dali.sufxvd.cn/Article/details/gt2pnssubrt.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gt2ssrohvgn.html

Ruby: s.lines
来源：http://dali.fengsongda.top/Article/details/gt2gfnajzlj.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2knrionqm.html

[E20] 判断字符串是否为空
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnmiqltl.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gt2ohlcrpwf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oggunzfr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kytzshwp.html

TS:   if (s === "") {}
来源：http://dali.tian-w.cn/Article/details/gt2igwbcnjb.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jffmalbb.html

Go:   if s == "" {}
来源：http://dali.gotoacloud.top/Article/details/gt2acpqvmmj.html

Ruby: if s.empty?
来源：http://dali.zdqjudy.top/Article/details/gt2njvirbdt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ehwqpu.com/Article/details/gt2zmcdxtno.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gt2iztmdrlq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fzhhl.top/Article/details/gt2smltmncj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2anyjuccy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2rnvxeaig.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gt2qelowdxy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2jzsfnkdt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gt2cxezttrp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2xwicacdn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2tcpkcirx.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gt2mebgjjua.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zycfv.cn/Article/details/gt2qajzwdka.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2sitefjoe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gt2xiclazyh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2akypuxon.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gt2lfofvykl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gt2zfzbkcak.html

Ruby: s.bytesize;  s.length
来源：http://dali.dashuyun.cn/Article/details/gt2durjshtu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gt2vihygtkc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2sihrwjbu.html

F. 文件与目录
来源：http://dali.daria6918.cn/Article/details/gt2lraewfzt.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmzztjco.html

[F01] 读取整个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2inqbmxrp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gt2yzqrqjyg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2paotzffw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shuidangran.top/Article/details/gt2qzizavhz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2haxewepu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2mpvedesb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gt2lqbjvfvn.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2dobdjgdz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2pzbuuiin.html

[F02] 逐行读取文件
来源：http://dali.jiagoushi.top/Article/details/gt2hutzqdhq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guannengcc.top/Article/details/gt2gohgazmc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gt2iiptxjqt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gt2norsqzgy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gt2nszcopns.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gt2mcipiogh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gt2mnicimlv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ilitbtlv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2advhokva.html

[F03] 写入文件（覆盖）
来源：http://dali.zdqjudy.top/Article/details/gt2lycmknsd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shzxlz.cn/Article/details/gt2cyhlyzps.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gt2poqedivz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcpwlggg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gt2xwvvnqkv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjnqrild.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.mhx1999.top/Article/details/gt2fpopzoql.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2lqggzlsv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2xouiiwrt.html

[F04] 追加写入文件
来源：http://dali.redwolf501.top/Article/details/gt2dfpzskfb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2ceimigwe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gt2xconmqxg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gt2euncvkvy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zarhclud.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tanke756.top/Article/details/gt2feoiuhae.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2qjourcqy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gt2paiepero.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shhromcv.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gt2toyhbceh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2trcjzkzw.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2antblihy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2nrhnyuwm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2nejrgfdf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2wfwdskkf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pycfn.com/Article/details/gt2pzkelukr.html

Ruby: File.exist?("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2wgszaeaj.html


<!-- 参考信息 -->