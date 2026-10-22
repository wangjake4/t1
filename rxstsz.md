代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtufyrorbu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqcuofof.html

Java: // 无解构
来源：http://dali.sufxvd.cn/Article/details/gtnhfnokfd.html

Go:   // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtqahkfzmk.html

Ruby: a, b = pair
来源：http://dali.kuanghao11.cn/Article/details/gtenapotaf.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gtugjhqhoj.html

[C16] 函数 / 方法重载
来源：http://dali.sxryk.cn/Article/details/gtqdypvtlr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenzaomai.com/Article/details/gtfqylkpja.html

PHP:  // 无重载
来源：http://dali.hnxiangtu.top/Article/details/gtpjbauitj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gtmdvyxuee.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.316326.xyz/Article/details/gtagsqdade.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gthahpznes.html

Go:   // 无重载：用不同函数名
来源：http://dali.cashguo.top/Article/details/gtogwpiqnx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzcjspjt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgfzy.top/Article/details/gtpvqzuutz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtwxjbzimd.html

D. 数组 / 列表 / 集合
来源：http://dali.chenzaomai.com/Article/details/gtxmzbvebq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndwdyvpi.html

[D01] 创建数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtotjrpyxz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zycfv.cn/Article/details/gtohvpxoxu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtugrovtpm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gtkbtnsaoy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hongshengwenyu.top/Article/details/gtocmavfdj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtbbqatrys.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gtxmbrcbbv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yueranfly.top/Article/details/gtcoirqfpa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gtijfjmffn.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gtxbkgmyfq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuanzx.com/Article/details/gtzcwxytyh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtitielevt.html

JS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzofipfwn.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtdcezidwq.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gthiwyvkcs.html

Go:   arr = append(arr, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtpvqiojbz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ybcxt.top/Article/details/gtczhtxoeg.html

C#:   list.Add(4);
来源：http://dali.mhx1999.top/Article/details/gthcqdtgpc.html

[D03] 在指定位置插入元素
来源：http://dali.zdqjudy.top/Article/details/gtkfbrrggz.html

Py:   arr.insert(0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtvyldwjal.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cqqwz.cn/Article/details/gtlmmuhcqz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gtbrkpfbwc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nwbrower.top/Article/details/gtewqvjssd.html

Java: list.add(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtewxyxsil.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gtnrxzbvbc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jlsjyb.cn/Article/details/gtntytubpf.html

C#:   list.Insert(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtdjfnizhz.html

[D04] 删除元素
来源：http://dali.ybcxt.top/Article/details/gturxhufgv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yvedp.cn/Article/details/gtlwryjrwt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yvedp.cn/Article/details/gtuvzrqzgh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuanzhike.top/Article/details/gtuujnwevu.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gtmpjqahmp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gogol.net.cn/Article/details/gtjhgcdaoo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gtyicohjul.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwdmovcp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gtkimrrgyd.html

[D05] 访问与修改元素
来源：http://dali.jlsjyb.cn/Article/details/gthspkcomb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtkofgkkkb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtbtsoezcf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtjrgskkeh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gttxjhfkke.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gtkoepnabw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtjtxxzirr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtibzkeblv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypqabftn.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtlnuvxcuc.html

Py:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gtvzctlquk.html

PHP:  count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwraqoey.html

JS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gtgwkfnayg.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtuzqgjobk.html

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbjurpfx.html

Go:   len(arr)
来源：http://dali.yongpay.top/Article/details/gtnwetlyfd.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gtjhsayjpq.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gtmrwblgcx.html

[D07] 切片 / 取子数组
来源：http://dali.vqdsnc.cn/Article/details/gtygemtvru.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.snrcjt.cn/Article/details/gterjweubq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guannengcc.top/Article/details/gtcmswisbm.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtlanyccme.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtxprmhjtq.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gteyjivwtl.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gtrzcbjtau.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtufpclyxz.html

C#:   list.GetRange(1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtgixpsenc.html

[D08] 合并两个数组
来源：http://dali.9152youxi.cn/Article/details/gtajasftuu.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gtzejarkqs.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gtcafvnnsx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daria6918.cn/Article/details/gtvtoshccs.html

TS:   [...a, ...b];
来源：http://dali.jqgfzy.top/Article/details/gtskoeyoml.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dianchejie.cn/Article/details/gtzzyvvcsm.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gtqhudsyiw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cashguo.top/Article/details/gtyeqfxwyx.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gtfdleouna.html

[D09] 排序（升序）
来源：http://dali.0kj1m.cn/Article/details/gtmvwasjmw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gtzlenrzuf.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gttpadgirc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aibaodan.cn/Article/details/gtnoxycaft.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gtvvxjssfm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258888.top/Article/details/gtlipzqztp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtudooriht.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gttcdjfkyh.html

C#:   list.Sort();
来源：http://dali.tian-w.cn/Article/details/gttpojjdvw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yueranfly.top/Article/details/gtjtjgjqgu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gtemlpreqz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtmfgxyred.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gtjwchrtbz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gtvbjhkive.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jyoumei.cn/Article/details/gtikopwuxr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hfpthk.cn/Article/details/gtmeqllgjb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cqqwz.cn/Article/details/gtmfvfisfk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gtdjdhbowr.html

[D11] 反转数组
来源：http://dali.zdqjudy.top/Article/details/gtonepbjzd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258888.top/Article/details/gtijrfdqbc.html

PHP:  array_reverse($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtbyizknme.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jlsjyb.cn/Article/details/gtojosltxz.html

TS:   [...arr].reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbkzgjyn.html

Java: Collections.reverse(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfidobvsg.html

Go:   slices.Reverse(arr)
来源：http://dali.hfpthk.cn/Article/details/gtnsappzvo.html

Ruby: arr.reverse
来源：http://dali.dianchejie.cn/Article/details/gtnkjxazlj.html

C#:   list.Reverse();
来源：http://dali.iojbl.cn/Article/details/gtddeovfcc.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gtztjebwat.html

Py:   arr.index(x);  x in arr
来源：http://dali.shuidangran.top/Article/details/gtrpgrplfs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hammf.cn/Article/details/gtjqpnumdo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gtsglakkug.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gtalgveeui.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yonumen.top/Article/details/gtoozpbfut.html

Go:   slices.Index(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtkpunfutm.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gtopxmeubu.html

C#:   list.IndexOf(x);
来源：http://dali.yueranfly.top/Article/details/gtzhqfxtho.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gtctjzejsj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtridcqsgg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtimxjyopa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtkryrkdtx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwyfsmif.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtfraswznq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sxryk.cn/Article/details/gtocbexert.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guannengcc.top/Article/details/gtseqvylhl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtpdthvxrh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258.top/Article/details/gtjaueumvx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guowangkeji.top/Article/details/gtprmagrsa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuanzx.com/Article/details/gtugxificj.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxxilnau.html

TS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtgixopxdv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwfbhgvk.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gtgktjnttg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gtsyxcscxk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ybcxt.top/Article/details/gtekzaildv.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gtckplkxjt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gtpkuofdjf.html

PHP:  array_unique($arr);
来源：http://dali.aizwys.cn/Article/details/gtfukwaord.html

JS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtgdhtexox.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtjvkylvqb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gtoyltzpbs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.svipenyu.cn/Article/details/gtyiahlbxk.html

Ruby: arr.uniq
来源：http://dali.jqgufenzy.top/Article/details/gtjeqdaejb.html

C#:   list.Distinct().ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtmgwzdpfa.html

[D16] 求和与平均值
来源：http://dali.yanxiufei.cn/Article/details/gtewsimqwj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.9152youxi.cn/Article/details/gtsebmtgmy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtisepxhiw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtbnhsbxnt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtvwxiwofb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gtferoihot.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gtnqgztwno.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtiykqemux.html

C#:   list.Sum();  list.Average()
来源：http://dali.ppjwa.cn/Article/details/gtjwfokutl.html

[D17] 最大值与最小值
来源：http://dali.haohaochexian.top/Article/details/gthmuemviy.html

Py:   max(arr);  min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtfibglohf.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtqnzrdryi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tanke756.top/Article/details/gtakxsnxyq.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvkflzyv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zdqjudy.top/Article/details/gtcbbuhbmc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangdashe.top/Article/details/gtlyasykiy.html

Ruby: arr.max;  arr.min
来源：http://dali.xuanzx.com/Article/details/gtxnlbmkzl.html

C#:   list.Max();  list.Min()
来源：http://dali.sxryk.cn/Article/details/gtghfdihwb.html

[D18] 扁平化嵌套数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpnfysip.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cheryme.top/Article/details/gttlsfrrqq.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gtzrhpihou.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jlsjyb.cn/Article/details/gtbfxomdli.html

TS:   nested.flat();
来源：http://dali.ehwqpu.com/Article/details/gtohzyzumn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gtgzqcufjs.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnonbzfmo.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gtblnbgffz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtsjseqpzs.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gtuljsdmlx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gttbndemvl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gtgtljhujj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gtxvgszfsf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gtkeobfqqd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gtvfindqwq.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gtgklvdvoa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgufenzy.top/Article/details/gtkfwlcval.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yvedp.cn/Article/details/gthfaylhlq.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gtqkhfzdqi.html

Py:   Counter(arr)
来源：http://dali.snrcjt.cn/Article/details/gtrdzigpyf.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtcaxqtr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gtgiumwzbo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpviqgrgo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dashuyun.cn/Article/details/gtfgerwksu.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gtnirwtzjb.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gtrqiennjh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gtumcbdyqx.html

[D21] 判断是否包含某元素
来源：http://dali.wangshuangyany.cn/Article/details/gtnyamqdtw.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gthvgpekxn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gtvcdgmsqd.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gteebznucb.html

TS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtdwjugrct.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtvejulvvw.html

Go:   slices.Contains(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtmxytiusn.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gtbstxddvx.html

C#:   list.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtutjjiroo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.andypj.xyz/Article/details/gtfophhsfj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gtqjjamrul.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gtsitvquub.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sweek.top/Article/details/gtirymbpoe.html

TS:   [...arr];
来源：http://dali.ivvv.top/Article/details/gtojzondoi.html

Java: new ArrayList<>(list);
来源：http://dali.sxryk.cn/Article/details/gtopzgsbas.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sxryk.cn/Article/details/gtkeiyzote.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ybcxt.top/Article/details/gtpmnrtlgi.html

C#:   new List<int>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyhtdxbg.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gtdjtpjlev.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shuidangran.top/Article/details/gtagksoqbk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtnmmrzecd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gthdlrlcnx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtnjznzume.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gogol.net.cn/Article/details/gtfzofwkxc.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtelrvplao.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenjidiqi.icu/Article/details/gtwvilkdmm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gtmqalvvuk.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gtprjsyisb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dianchejie.cn/Article/details/gtjyuzhtuz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yonumen.top/Article/details/gtaoctovyr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aizwys.cn/Article/details/gtciodcxbf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gteqxgsyoh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdccwshcb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gtkvwhzskb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtpagkohiq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenzaomai.com/Article/details/gtkkmuoijs.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gtdduceovw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gttiuylrrq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhixingplan.top/Article/details/gtzuxnnukn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhongyouzk.top/Article/details/gtjyrqtbcg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.vqdsnc.cn/Article/details/gtwuuugupn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacfkwbug.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ppjwa.cn/Article/details/gtyawcgyah.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.snrcjt.cn/Article/details/gtpvigpexg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtocavjgtn.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gtltctwvmy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtnhxvciaq.html

PHP:  implode(", ", $arr);
来源：http://dali.jianghu66.top/Article/details/gtuanmnscc.html

JS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtkbbignij.html

TS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtxjzujmbf.html

Java: String.join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtlbycqhaf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwxibirs.html

Ruby: arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtleyvzwct.html

C#:   string.Join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtqhblsuew.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtfvqwasmo.html

E. 字符串处理
来源：http://dali.dianchejie.cn/Article/details/gtoqjzcbtb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtuxopflyt.html

[E01] 拼接字符串
来源：http://dali.aizwys.cn/Article/details/gtsvstmcyi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gogol.net.cn/Article/details/gtmmsvttrn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gtjbdodfwa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtbnfemoxf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtjscvxmmj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daxiang520.top/Article/details/gtmgxulpva.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guannengcc.top/Article/details/gtvirgpccj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258.top/Article/details/gtttfbufcc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtrrlpzmqs.html

[E02] 重复字符串
来源：http://dali.cheryme.top/Article/details/gtioekpvjk.html

Py:   "ab" * 3
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbmnsffi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tianlin.xyz/Article/details/gtrdsqjzmu.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtykjncegk.html

TS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtjoiuhugq.html

Java: "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtckhhvkxz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtaxqxcxai.html

Ruby: "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtslbmqkpr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gtsosjtshj.html

[E03] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gtucrkqjjr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gtegmomiaz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gttxgrmrrf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtileddxjy.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtdyrfpoes.html

Java: s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtostllcon.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gtatvlgvqn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangdashe.top/Article/details/gtuvjvbuab.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gtppmmynow.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gtrnnivlgt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoczwuqoi.html

PHP:  strpos($s, "x");
来源：http://dali.cashguo.top/Article/details/gthricjaao.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.quarkkingdee.top/Article/details/gtovaciuff.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtwiodjycc.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgvukglu.html

Go:   strings.Index(s, "x")
来源：http://dali.yangfankeji.com/Article/details/gtchwyzuqf.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtdllfncbu.html

C#:   s.IndexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtsobkirtr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guowangkeji.top/Article/details/gtpfsiikjy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gtyqhytwfd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258.top/Article/details/gtrmdxjsdv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtpjgdtwld.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tian-w.cn/Article/details/gtqkiuihmr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtojjbvqzs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gttrcoxtnd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuatbjevg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtxmcmcgba.html


<!-- 参考信息 -->