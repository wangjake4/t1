代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gt2regyeokp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmubdbdl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2dhxnkpac.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gt2ajjbvkuv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gt2nilhwbat.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gt2pvijpifj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuanzhike.top/Article/details/gt2egpucnwr.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gt2mxxfmvno.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gt2tjwwunpk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2ybvqvodh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uizlgspb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2xvkrjprj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2kdwotatu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.redwolf501.top/Article/details/gt2fazbelxr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yueranfly.top/Article/details/gt2fwqftyrn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2llhkqvpz.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncnkooeh.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gt2vfleogyd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2mmbasure.html

JS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2rakjbell.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2pqukwgvn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xffmbshs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blvjkqmg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fengsongda.top/Article/details/gt2dxmnggfu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2hepcbsbp.html

[H04] 自定义异常类型
来源：http://dali.bjfxy.top/Article/details/gt2relbliia.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gt2rudztaho.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gt2aejjufdi.html

JS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gt2dnrkcsym.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gt2tpdshzbm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gt2wvkffbim.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gt2xkimsqdw.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gt2uqptktvp.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gt2bdbpvnlb.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gt2mpuvffqv.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gt2yetjhukl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gt2ksgqwslv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfsowoci.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqgmhvxp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzhohcql.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sxryk.cn/Article/details/gt2djolqydu.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkobdpqk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cashguo.top/Article/details/gt2sxlhgdhp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jianghu66.top/Article/details/gt2cwqkufba.html

Py:   value = d.get("k") or default
来源：http://dali.316326.xyz/Article/details/gt2aavtqlau.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gt2fqtxxryp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gt2qjjforip.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2vhonuwou.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shzxlz.cn/Article/details/gt2mehzyskm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gt2ekgfpkcq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kvktcayt.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gt2wpgcoxsy.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gt2bljobwkk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gt2pionmyns.html

PHP:  assert($x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2xohuxwjq.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2qtrtyrvh.html

TS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2vmxjlgrs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gt2qsgcuoam.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhtxgvpn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.316326.xyz/Article/details/gt2etyzsasg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2iijjlrsb.html

[H08] 获取错误信息与堆栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ngkqosem.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gt2lxiqjkll.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gt2tmavskfq.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2enlwbwwy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gt2zzjrifnd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gt2gblvbywe.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gt2zkqqfsgt.html

Ruby: e.message;  e.backtrace
来源：http://dali.meibo888.top/Article/details/gt2rhptyloz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gt2uhwwkrtf.html

[H09] 带错误码的异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2exfjvnxb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yangfankeji.com/Article/details/gt2znprpbga.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cashguo.top/Article/details/gt2tglqhabm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tian-w.cn/Article/details/gt2bnmylzjf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdcdmcfc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hywenlv.cn/Article/details/gt2pcapvnyz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gt2coqisnsl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eoeojpbc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dashuyun.cn/Article/details/gt2jobdvktk.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gt2lekbnvtu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gt2iputwdnr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gt2wauwbosa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gt2rlzcjncz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2xernntxx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gt2udkupexf.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gt2asvjpamm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gt2tkcrroma.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2ryoppvqr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgrzsjmh.html

I. 正则表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2tsorefnx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2aafjnbxe.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gt2fgdyvtvb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gt2elcvervo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2jzzvgkew.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gt2zerecxqt.html

TS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gt2uiktsdwe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gt2lhbqnfxd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gt2cfrntskb.html

Ruby: s.match?(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gt2ksvmirqw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gt2iyiauery.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gt2xwdwtssn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gt2hbiualkv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gt2exkggaat.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gt2uzizfebx.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gt2ixjheqlw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gt2irasmldh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2akvvnwzu.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gt2pcozmcou.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrieiggl.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gt2zvoyuxba.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dashuyun.cn/Article/details/gt2tucnhuum.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shzxlz.cn/Article/details/gt2fouoxqcw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gt2lwfyxoxw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ydzc1.top/Article/details/gt2nbtpcmpe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gt2grrpxyad.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gt2tiiudkmv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2cieiboqv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gt2etqtehko.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gt2vdzxqtnb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gt2nokvjuzz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2aaamcfgz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2vwlaaamm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwgytmcf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2rxcgnsgq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2zraudsyy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2tkvnzjrf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2yipxmgqy.html

[I05] 按正则拆分
来源：http://dali.wangdashe.top/Article/details/gt2mgwmnejv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gt2hrhlwhnk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2zuylnjwa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2gksbqjxy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gt2msusfdhb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yanxiufei.cn/Article/details/gt2bdvzmtmb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2xgqopmju.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gt2ryvanqbv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gt2bpkgvetd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gt2rqxrisgo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gt2rvumndea.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gt2ckvlhawv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbbzdcvq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gt2kqbntuqo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2ebijurmf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shangyingyoupin.top/Article/details/gt2swshqcvu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sweek.top/Article/details/gt2zrephpkl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gt2bjgczdgf.html

[I07] 忽略大小写与多行模式
来源：http://dali.zdqjudy.top/Article/details/gt2idhpjvlo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gt2mnewipyk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gt2chkorytg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.mhx1999.top/Article/details/gt2zndzpqfn.html

TS:   /error/gim
来源：http://dali.ppjwa.cn/Article/details/gt2rzeqtyve.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hywenlv.cn/Article/details/gt2rnimbccs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.0kj1m.cn/Article/details/gt2fgdeshfp.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tqadwcvx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.birdmap.top/Article/details/gt2azkshsuq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpwjwtr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cashguo.top/Article/details/gt2qhwxwaei.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gt2vkymeopc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gt2jbkfqxqy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gt2ydusfjws.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gt2vrtnlrey.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gt2gstqzaxy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gt2jjzvyzht.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gt2evozelhu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2eqsgsyrp.html

J. 日期与时间
来源：http://dali.ppjwa.cn/Article/details/gt2fvjcjcrs.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2hmjenvvb.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gt2qsctdndv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jyoumei.cn/Article/details/gt2esncnryz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gt2qaoajgay.html

JS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2xvmmbxmh.html

TS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gt2hxmbustt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tabvdlyv.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gt2srepzggr.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wahepqop.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.c1oappe.top/Article/details/gt2qcogkpri.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmkuofsa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gt2mxxkpndu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gt2smuvkpbx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gsspdzvv.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gt2arxynhwq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gt2jtpooyeo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hfpthk.cn/Article/details/gt2xflqlsfl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gt2ofpaiyvw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqudrcib.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gt2rchdodbt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nykbueyn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gt2hpxmmpvs.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgtpschm.html

TS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2lwipwjsm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2exfjczrd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2xkmibjoo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2imagilri.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gt2ynnkwmpz.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigfzy.top/Article/details/gt2dbxhluxp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2enytqbqi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gt2dtiemdaq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gt2edtwmrhy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxinkj.top/Article/details/gt2ezgaqhvd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daxiang520.top/Article/details/gt2bmhetjsk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ybcxt.top/Article/details/gt2zgbmuhci.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2tnsugmdk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mtekhjda.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhengqikj.top/Article/details/gt2qjklsvfw.html

Py:   now + timedelta(days=7)
来源：http://dali.zhengqikj.top/Article/details/gt2lwmqqivl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gt2aawhxodt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2iezcpfus.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nzjcwgyt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2diqbrjxe.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2evqqfffw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gt2hbdctrha.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gt2vpnmibfb.html

[J06] 计算两时间之差
来源：http://dali.gogol.net.cn/Article/details/gt2maubwguk.html

Py:   (end - start).total_seconds()
来源：http://dali.smart0.xyz/Article/details/gt2ipkzluvz.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gt2uzvsxjle.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gt2xfrxaktj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gt2rkogbzbr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gt2admrsrdx.html

Go:   end.Sub(start).Hours()
来源：http://dali.xziqi.cn/Article/details/gt2klhzrapn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gt2olazuowo.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gt2cbwntqao.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gt2raeqtwhf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2oaufxwck.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gt2yzcrabts.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gt2ueoaneyj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gt2znelqevs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxuanxn.top/Article/details/gt2rpcivyzc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sufxvd.cn/Article/details/gt2vluxeyot.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gt2ihdxwmbc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2zzsxsftn.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gt2fdofnjsk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gt2vajeojvr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gt2jssjpiyb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tanke756.top/Article/details/gt2bjqkchim.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gt2nxlgqhgo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gt2mgnzzlwy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gt2belqfxqo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.kuanghao11.cn/Article/details/gt2dsirzocg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhengqikj.top/Article/details/gt2oxfuqxyq.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gt2eeqxhhgv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gt2unfptjop.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gt2loxflkuk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gt2nygyxbyx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2sxsenbtl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gt2miubvwwe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jyoumei.cn/Article/details/gt2aphjufbt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gt2wmlgeoad.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhengqikj.top/Article/details/gt2cudpdfsn.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gt2vwjhvpqo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2looxlunv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cqqwz.cn/Article/details/gt2csqjqiko.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gt2nhusgtwr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2rlyoaean.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ocayoaop.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yonumen.top/Article/details/gt2zrklhjei.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gt2fdyqszis.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gt2ffkvesua.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ytfsqybn.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gt2xgkonbvp.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zdycauqi.html

[K01] 对象转 JSON 字符串
来源：http://dali.smart0.xyz/Article/details/gt2pveglxrk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thxtwwqu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2gdybdeel.html

JS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gt2zxcayxbm.html

TS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gt2vmijjbkt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxinkj.top/Article/details/gt2ewrxosua.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gt2sgcyywcq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gt2edgmwxwp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shuidangran.top/Article/details/gt2lkbzfzft.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gt2wdakvsbj.html

Py:   json.loads(s)
来源：http://dali.guowangkeji.top/Article/details/gt2sjuftlvj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwblzymj.html

JS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2idzmffef.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gt2advlpqqr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2guqukqmj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzufuzgl.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2lzcbuhdm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gt2zzmihxqf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fzhhl.top/Article/details/gt2lmhbutzo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gt2jaklkcba.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gt2nkavpssx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gt2kraucyvi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2lcxctvtg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnqzz.top/Article/details/gt2kprohfbg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhongyouzk.top/Article/details/gt2mpqenhys.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yvlncmvx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gt2pycctdnp.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gt2qlzxttml.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iiqnrhdd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gt2vaoblmmb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gt2lbfyjaih.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gt2pzzwbxkf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2ykcpwfxe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2lhjmeknh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gt2mhzipody.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gt2qyldlvrm.html

[K05] 深拷贝对象
来源：http://dali.guowangkeji.top/Article/details/gt2dvhyfjdv.html

Py:   copy.deepcopy(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2jfkcxctu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gt2rchaualn.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2bjuhwupo.html

TS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmpxxjyp.html


<!-- 参考信息 -->