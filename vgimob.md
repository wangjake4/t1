代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.birdmap.top/Article/details/gt2lavxzjmj.html

[C15] 解构 / 展开参数
来源：http://dali.cheryme.top/Article/details/gt2qjjbjfbi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hywenlv.cn/Article/details/gt2snadtxib.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gt2aejklgea.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bnsiwcxa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2uicrcwkt.html

Java: // 无解构
来源：http://dali.meibo888.top/Article/details/gt2cmvnwhvx.html

Go:   // 无解构
来源：http://dali.yonumen.top/Article/details/gt2drvafggd.html

Ruby: a, b = pair
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxuhaecf.html

C#:   var (a, b) = pair;
来源：http://dali.smart0.xyz/Article/details/gt2nhgsezsj.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gt2bheuexya.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrhiabat.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hilsboao.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gt2rtdausbu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cheryme.top/Article/details/gt2tgmmsoug.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sufxvd.cn/Article/details/gt2tijdpahh.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztdeesmj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fengsongda.top/Article/details/gt2qzqygtzi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuanzx.com/Article/details/gt2keliwuea.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2wnqrdlal.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gt2datdvlyz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmkuzycz.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gt2yhrasaes.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jianghu66.top/Article/details/gt2yrdghfnv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.mhx1999.top/Article/details/gt2ybstzggh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gt2oxuwlzrt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gt2bmqrurhh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gt2gjidcjdg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nwbrower.top/Article/details/gt2tjbfyvgl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oabulvlv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shzxlz.cn/Article/details/gt2xfkefahm.html

[D02] 追加元素到末尾
来源：http://dali.yvedp.cn/Article/details/gt2nawlhqbu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yueranfly.top/Article/details/gt2ksdxklao.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yongpay.top/Article/details/gt2ppwrqirl.html

JS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2lssajfex.html

TS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdbgkdhm.html

Java: list.add(4);
来源：http://dali.yuxming.cn/Article/details/gt2bbnrmtgq.html

Go:   arr = append(arr, 4)
来源：http://dali.zhixingplan.top/Article/details/gt2aiwzjmgi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbhxgbmy.html

C#:   list.Add(4);
来源：http://dali.gogol.net.cn/Article/details/gt2qcmrtpmt.html

[D03] 在指定位置插入元素
来源：http://dali.vqdsnc.cn/Article/details/gt2bplurepe.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2ikqgfvgo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgdtaees.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dyetdvhu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gt2jtojkguo.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfwsnbhf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gt2jiiqvwan.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gt2bwpovcap.html

C#:   list.Insert(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2beuoagmr.html

[D04] 删除元素
来源：http://dali.ehwqpu.com/Article/details/gt2lrxbyjtl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gotoacloud.top/Article/details/gt2xemhdwfq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xinyue.icu/Article/details/gt2xwmjyjzg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gt2byzmjsey.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ydtmkzpv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dashuyun.cn/Article/details/gt2nkrgoxpu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fzhhl.top/Article/details/gt2kktwzuol.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.haohaochexian.top/Article/details/gt2zquangwo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.9152youxi.cn/Article/details/gt2ambflnya.html

[D05] 访问与修改元素
来源：http://dali.hnxiangtu.top/Article/details/gt2uvtieaem.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gt2bxzvnrgb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gt2aaxvvazd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lphjftkv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gt2ifbdgvyy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hywenlv.cn/Article/details/gt2gcyobrvo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gt2bunyyhxa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gt2unkbjxns.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gt2mknfelda.html

[D06] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gt2eddtnndt.html

Py:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gt2aluzgakp.html

PHP:  count($arr);
来源：http://dali.pycfn.com/Article/details/gt2kykzubac.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tahrcwam.html

TS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gt2slltcthx.html

Java: list.size();
来源：http://dali.shzxlz.cn/Article/details/gt2vlezornz.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2afmzwkwn.html

Ruby: arr.length; arr.size
来源：http://dali.birdmap.top/Article/details/gt2efgahduu.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gt2nrtdaxuv.html

[D07] 切片 / 取子数组
来源：http://dali.tanke756.top/Article/details/gt2acflcgpp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ehwqpu.com/Article/details/gt2dzhyperb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ydzc1.top/Article/details/gt2wkomrjuy.html

JS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gt2ufnnnceq.html

TS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gt2quwqyssa.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gt2ylzxtcae.html

Go:   arr[1:4]
来源：http://dali.fzhhl.top/Article/details/gt2ahhffejc.html

Ruby: arr[1, 3]
来源：http://dali.hammf.cn/Article/details/gt2peirxgug.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2wvupgskh.html

[D08] 合并两个数组
来源：http://dali.andypj.xyz/Article/details/gt2tvaxivhs.html

Py:   a + b;  a.extend(b)
来源：http://dali.hywenlv.cn/Article/details/gt2nwmpwybd.html

PHP:  array_merge($a, $b);
来源：http://dali.zhengqikj.top/Article/details/gt2aqdykmeu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fqlonujt.html

TS:   [...a, ...b];
来源：http://dali.daxiang520.top/Article/details/gt2bmzmwhmp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jianghu66.top/Article/details/gt2jfzaebaw.html

Go:   append(a, b...)
来源：http://dali.yongpay.top/Article/details/gt2wcbfkuti.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daxiang520.top/Article/details/gt2cizgagbt.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2zvnwzypt.html

[D09] 排序（升序）
来源：http://dali.aibaodan.cn/Article/details/gt2btvhhecy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gt2fkefzing.html

PHP:  sort($arr);
来源：http://dali.andypj.xyz/Article/details/gt2wknwjsgl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gt2wzpfpomv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gt2fjpntlyw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ivvv.top/Article/details/gt2exadvrsk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2dhvxuvml.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gt2ejtiazmo.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gt2naqbfuhp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gt2kouydlsb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2avbjjlpv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2bnlmxuca.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gt2xhbucqpj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gt2xhlplnyt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aizwys.cn/Article/details/gt2pqhyjkrk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbkhtsnl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.0kj1m.cn/Article/details/gt2hduquyuq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gt2yprvtlat.html

[D11] 反转数组
来源：http://dali.yonumen.top/Article/details/gt2hqmktemx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gt2webbiaib.html

PHP:  array_reverse($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2cmdwsubb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gt2hqppzzuz.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gt2fzpljbew.html

Java: Collections.reverse(list);
来源：http://dali.sufxvd.cn/Article/details/gt2lqsttmrb.html

Go:   slices.Reverse(arr)
来源：http://dali.xziqi.cn/Article/details/gt2vxiozujl.html

Ruby: arr.reverse
来源：http://dali.xylfe.cn/Article/details/gt2clamoxzj.html

C#:   list.Reverse();
来源：http://dali.pycfn.com/Article/details/gt2jnuhrftj.html

[D12] 查找元素下标
来源：http://dali.yj202588.top/Article/details/gt2pzxmfvvt.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhixingplan.top/Article/details/gt2rfgxjjba.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xziqi.cn/Article/details/gt2ayfdvlfa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdmyjjym.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idtqnivs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hammf.cn/Article/details/gt2yurqcqra.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2cnxtdzbh.html

Ruby: arr.index(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2jwquidal.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gt2tsqlpblw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaxnqdt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.birdmap.top/Article/details/gt2hrbsuezx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqvfssba.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkujawbf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2crgmiqvr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xziqi.cn/Article/details/gt2ukszlfsf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnxiangtu.top/Article/details/gt2tquqogjn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.vqdsnc.cn/Article/details/gt2nkdarfer.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sweek.top/Article/details/gt2lhllopoi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aibaodan.cn/Article/details/gt2agpspjft.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2qkddgdrl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gt2uvmpjovn.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tdtrjafb.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gt2lkoierue.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2yxgiezpp.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gt2gcrbkhdq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2vgasymgz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2yzresula.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gt2qgcuzilt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gt2gaudynhz.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2deyzmhda.html

JS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gt2cosaayyj.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gt2cgrnklmm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfgexwzg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.feifeiyinyue.top/Article/details/gt2ecmnxteb.html

Ruby: arr.uniq
来源：http://dali.zhixingplan.top/Article/details/gt2aawzsoer.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2icvjfupg.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gt2krqvbuqh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpjlpqcj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ivvv.top/Article/details/gt2hfakqqjq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2hvgihzbc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gt2qidsyxjn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yangfankeji.com/Article/details/gt2sxrtegyv.html

Go:   // 手写循环累加
来源：http://dali.hysaishi.cn/Article/details/gt2ayqisgbs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.havefunace.top/Article/details/gt2aydnftes.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gt2ivetfaun.html

[D17] 最大值与最小值
来源：http://dali.xinyue.icu/Article/details/gt2dsfshvio.html

Py:   max(arr);  min(arr)
来源：http://dali.tian-w.cn/Article/details/gt2qkytxtyv.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2bevidjvb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gt2rzekbvjj.html

TS:   Math.max(...arr);
来源：http://dali.shzxlz.cn/Article/details/gt2gdrdvlqs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.smart0.xyz/Article/details/gt2izgbtczr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gt2fnrhvzey.html

Ruby: arr.max;  arr.min
来源：http://dali.nwbrower.top/Article/details/gt2cqlzvoih.html

C#:   list.Max();  list.Min()
来源：http://dali.guowangkeji.top/Article/details/gt2hozgowfc.html

[D18] 扁平化嵌套数组
来源：http://dali.wangdashe.top/Article/details/gt2jwykqxnj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jianghu66.top/Article/details/gt2fmxdwswm.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gt2hgqvgkhi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gt2ozhzfxjz.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gt2mndllmpu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.andypj.xyz/Article/details/gt2gwsygfhb.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gt2tuzzlhaz.html

Ruby: nested.flatten
来源：http://dali.zdqjudy.top/Article/details/gt2awtisszo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2uxrgcimi.html

[D19] 按字段分组
来源：http://dali.hywenlv.cn/Article/details/gt2mcgokeed.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xinyue.icu/Article/details/gt2gnmcahro.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ppjwa.cn/Article/details/gt2umhssudi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yueranfly.top/Article/details/gt2tzpxoqce.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guowangkeji.top/Article/details/gt2shouzepy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gt2kuxyyztu.html

Go:   // 手写 map[string][]T
来源：http://dali.havefunace.top/Article/details/gt2ucgthszt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guannengcc.top/Article/details/gt2kbwbgpdn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gt2cgwlfrhn.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gt2wfgcvwqs.html

Py:   Counter(arr)
来源：http://dali.birdmap.top/Article/details/gt2hyhglxmi.html

PHP:  array_count_values($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2cyowjzpw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gt2coyuxqag.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2wkssafka.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zycfv.cn/Article/details/gt2fiucslaf.html

Go:   // 手写 map[T]int
来源：http://dali.zhoulong.xyz/Article/details/gt2nikizhck.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gt2ttbiatke.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gt2lenfszrz.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2eqykskxt.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gt2eonzdnlk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gt2mmprldbe.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bygiwpef.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kxpjvfsu.html

Java: list.contains(x)
来源：http://dali.cdnleiting.top/Article/details/gt2anbihkmr.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2dhzysyym.html

Ruby: arr.include?(x)
来源：http://dali.hfpthk.cn/Article/details/gt2aemrqdsu.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2ujuknzmb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gt2zbgagwqj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.meibo888.top/Article/details/gt2dcyiwhuc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhiwuduotai.top/Article/details/gt2boqapdyk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2akvbnqfa.html

TS:   [...arr];
来源：http://dali.jqgufenzy.top/Article/details/gt2fujncydx.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ucrfzcxy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.snrcjt.cn/Article/details/gt2diapsrnj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gt2vsuulzjf.html

C#:   new List<int>(list);
来源：http://dali.daxiang520.top/Article/details/gt2tuyvqtcw.html

[D23] reduce 累积计算
来源：http://dali.yueranfly.top/Article/details/gt2nuxitfqz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gt2uxsevrfs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdiyikda.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bjwnjnzy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gt2hhncbtku.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.0kj1m.cn/Article/details/gt2yckuwuxq.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gt2zyujabnq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gt2ogcqrfoj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gotoacloud.top/Article/details/gt2eacgbxij.html

[D24] 字典 / Map 基本操作
来源：http://dali.0kj1m.cn/Article/details/gt2zsxloufv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.havefunace.top/Article/details/gt2hsytztmn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2njocvuwq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gt2qhjmmfbt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2kdylnagd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vormqbmd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.0kj1m.cn/Article/details/gt2ccfpvxei.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.birdmap.top/Article/details/gt2ycylfzfb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dashuyun.cn/Article/details/gt2sdrtgelp.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gt2ltbmduog.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yonumen.top/Article/details/gt2edierjjn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gt2pvflubwm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gt2nxpdsuat.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.andypj.xyz/Article/details/gt2skcxtzpe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gt2uskmelwd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xvasgkdp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2diwuybmk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fzhhl.top/Article/details/gt2iylzsxpy.html

[D26] 数组转字符串
来源：http://dali.xinyue.icu/Article/details/gt2rxhuogpk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gt2qwfzfesi.html

PHP:  implode(", ", $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2mponuovu.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gt2magdtiom.html

TS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gt2xcjjzptg.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2nhnrsqjb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gt2camqdiau.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gt2sblpvree.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tmhkbawt.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2uzszeqtj.html

E. 字符串处理
来源：http://dali.gogol.net.cn/Article/details/gt2qrfczsxm.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2fjurnbed.html

[E01] 拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gt2ogdlfayo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sysykeji.top/Article/details/gt2giqedhww.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbjnkzgb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gt2mogwjbrx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gt2ilfamaig.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gt2qidimbch.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gt2djtjlgoc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.meibo888.top/Article/details/gt2ufdomwdy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2tfzbmqrv.html

[E02] 重复字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2dgjuyobn.html

Py:   "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gt2youiqulx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gt2bhxbgaxn.html

JS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2tekqkmcc.html

TS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gt2nocyiagn.html

Java: "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrrxmzgu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxpxheew.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gt2iyjusuzd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shzxlz.cn/Article/details/gt2iitkyhyi.html

[E03] 截取子串
来源：http://dali.xinyue.icu/Article/details/gt2pvrvuxgj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cashguo.top/Article/details/gt2hfomwtpf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gt2hkppcquq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gt2lrrxypkr.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swtdwoey.html

Java: s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gt2fdlxmapf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hammf.cn/Article/details/gt2hppcmwvd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aibaodan.cn/Article/details/gt2zryevkru.html

C#:   s.Substring(1, 3)
来源：http://dali.zhixingplan.top/Article/details/gt2lxndtopx.html

[E04] 查找子串位置
来源：http://dali.dianchejie.cn/Article/details/gt2lvoybtsr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gt2mzlxmyih.html

PHP:  strpos($s, "x");
来源：http://dali.tian-w.cn/Article/details/gt2kzpoqkby.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gt2hlpggdjj.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gt2ecibbnrb.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2nbiifaka.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gt2msabcyau.html

Ruby: s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gt2xrmdpzdi.html

C#:   s.IndexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gt2crsiswnh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.snrcjt.cn/Article/details/gt2uioriccx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yvedp.cn/Article/details/gt2axbzstzi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gt2sqvbosik.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2blanbwga.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sysykeji.top/Article/details/gt2teanirmq.html


<!-- 参考信息 -->