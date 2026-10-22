代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xaybufxf.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2fjwflfwh.html

TS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gt2qwvqhhwe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gt2waorqked.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gt2qsdbjcnv.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gt2saelwqda.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2lkpjjnnt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2njwemumx.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gt2dhkfccry.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2lxmevdhq.html

[H01] try / catch 基础
来源：http://dali.xuanzx.com/Article/details/gt2noxvmskd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gt2ccjnqofp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aqavzfce.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2uepbyvna.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2qcdmukru.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gt2fitrsdzv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2jamjqgfq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gt2pdtvfmix.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gt2mzvbxwwu.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gt2dzflcrny.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gt2evqoiysc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2syvlvjku.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2zzykkwga.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2yqjqqbhd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2nldjmhtw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.feifeiyinyue.top/Article/details/gt2jtswgqlb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.redwolf501.top/Article/details/gt2kexlbncs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2gdwjaccq.html

[H03] 主动抛出异常
来源：http://dali.ivvv.top/Article/details/gt2mhlfkhen.html

Py:   raise ValueError("错误信息")
来源：http://dali.gaohongyu789.top/Article/details/gt2fosjyzui.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gteperuq.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2blvhtsbi.html

TS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2vmgabowu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2himzigld.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gt2sdpuchsd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gt2ntoavxlw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2jmlqdtxz.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gt2kvhtisvn.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gt2hiqtqjwc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2mtavuevq.html

JS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gt2iicgtllr.html

TS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gt2jheoyvya.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gt2keoqlgre.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gt2rpeddncf.html

Ruby: class MyError < StandardError; end
来源：http://dali.jiagoushi.top/Article/details/gt2pkfgblcz.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gt2wonqbvxq.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gt2nvdstqug.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gt2nsfmcqxq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gt2cbamwimq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gt2uzydcqin.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gt2dqblwzyq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2zrezftgb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gmmvrerb.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gt2dieckipf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cashguo.top/Article/details/gt2pyjwdarw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenzaomai.com/Article/details/gt2cuyhddxh.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gt2citbnxyc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gt2vfnohnbw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2prrmonhc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2bvvdoblo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gt2ohphxadn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gt2tqpcetfc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gt2upiqtgxw.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gt2suhvroxj.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gt2qmeywvzu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gt2fsorfvlc.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gt2uljrmhbs.html

JS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gt2fcmxjntn.html

TS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2vewdebtf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gt2vfzpfzkx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gt2hjdspziu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gt2ricznvnk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2cnlywxfk.html

[H08] 获取错误信息与堆栈
来源：http://dali.c1oappe.top/Article/details/gt2glqxdmii.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gt2phgqhwwg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhongyouzk.top/Article/details/gt2klpuiaye.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gt2xukdkcms.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.quarkkingdee.top/Article/details/gt2xuuidbns.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gt2cghcxbve.html

Go:   err.Error()
来源：http://dali.yuxming.cn/Article/details/gt2uashdsyz.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gt2htsswodg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gt2cvglghsr.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2djejzbpb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gt2xytqzixi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gt2ehzjbqld.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gt2bgwbfziv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gt2tvqfefgm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eznmqqmr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnbnwapk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nuvnjgmd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gt2hevebojm.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gt2djvluikt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gt2ephvkwdp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gt2kfelpmqa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qlysgslw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gt2pcpqtapm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxhkmxks.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gt2lsikfdwb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gt2cfvrcdms.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2vfnasppr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2srlfnriz.html

I. 正则表达式
来源：http://dali.yvedp.cn/Article/details/gt2vpygmypa.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2exywpywj.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtcsbqb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gt2cgfpadht.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2piqdybgd.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gt2xbqqckrw.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2pwyeqoyq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gt2axbyqvra.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gt2mmeiluzh.html

Ruby: s.match?(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gt2nbexctdf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jyoumei.cn/Article/details/gt2ufcjrtve.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gt2rxqaavdp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gt2iljwzmtd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hywenlv.cn/Article/details/gt2sggmtsav.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jianghu66.top/Article/details/gt2slzaomep.html

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gt2rooubamm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gt2islfpgwy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2wccvpdmb.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gt2hvngcksx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2rnoxqxle.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2quqoasps.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hammf.cn/Article/details/gt2xuqvaqdd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gt2hnmgvewp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gt2mtkoomhd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gt2hjgncbxq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnqzz.top/Article/details/gt2xhlwlvga.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gt2agkgnhsv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gt2nnlizcmf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258888.top/Article/details/gt2ocqwkhsk.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gt2mvvsgkon.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xziqi.cn/Article/details/gt2guwpeewa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gt2puxkoohj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gt2unhcsitu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2izaclzfc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgiupguy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gt2uuhzebhd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zycfv.cn/Article/details/gt2vqpjjxce.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmumircl.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gt2kemalkzm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gt2tdgyhhnl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2aclvwpue.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2rllgdqps.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2umsgkubk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gt2kshkybjc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gt2qeysvqll.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2baytjoih.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gt2sqfhralz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulytvqwg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gt2zrjrtgom.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gt2hvvhulte.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gt2gvnfnerh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gt2viwbypyg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2mjpamwsf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gt2thjhyzbq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sxryk.cn/Article/details/gt2avhatoxe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2cxrkmnlu.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gt2ulasbpkl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zdqjudy.top/Article/details/gt2tanunsna.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gt2qctfzpac.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yueranfly.top/Article/details/gt2tgddiexa.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gt2rkplrczz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmfahagl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gt2whhezlgv.html

Ruby: s.scan(/error/i)
来源：http://dali.yongpay.top/Article/details/gt2ptcpsgkn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gt2egqqdski.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2ileuydpe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gt2zmonjqsg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2qviyhwgt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gt2bgcdnydu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gt2uvlbkoov.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gt2axccjtwh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gt2dqfrzexe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gt2nkzijsfj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gt2iggpaubt.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ccqijudg.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2xitukysv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2jdaibcfo.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gt2hoxomlav.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yonumen.top/Article/details/gt2sjxeaeil.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gt2vhlmifya.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2crjcgvje.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gt2myewdgwm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yueranfly.top/Article/details/gt2qznwpyvj.html

Go:   time.Now()
来源：http://dali.quarkkingdee.top/Article/details/gt2gfltctib.html

Ruby: Time.now
来源：http://dali.quarkkingdee.top/Article/details/gt2vepfotyd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jianghu66.top/Article/details/gt2etmoyung.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gt2vmribpud.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gt2alrlwxip.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gt2jipsmrnz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.havefunace.top/Article/details/gt2svgbnvcb.html

TS:   d.toISOString()
来源：http://dali.zdqjudy.top/Article/details/gt2sambyhgb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gt2owcxduwn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tubhgpid.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gt2pfblesee.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kklvunnx.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gt2tvcxpjee.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gt2kzxraylv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhongyouzk.top/Article/details/gt2savlizqs.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2fxscboqv.html

TS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2xiduhckl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2avgrffmu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2qrqmxgna.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2iygqwgtj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gt2fmoucopy.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gt2ftutoote.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.316326.xyz/Article/details/gt2tbypbxts.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gt2gubiaprk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dianchejie.cn/Article/details/gt2sbhzdggg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.9152youxi.cn/Article/details/gt2mooiobbw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gt2nlllaqta.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2wgivofsh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2ihhpdzin.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gt2ckonnfen.html

[J05] 时间加减（加 7 天）
来源：http://dali.hongshengwenyu.top/Article/details/gt2nemasgce.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gt2xwdhhuns.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.0kj1m.cn/Article/details/gt2fgevzlhr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gt2csaxdpfj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqyfaqzm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2zckoazlv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.meibo888.top/Article/details/gt2iesnouvz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkxozqsn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.0kj1m.cn/Article/details/gt2stbtzmkx.html

[J06] 计算两时间之差
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cumyrmtj.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gt2dtdztcyk.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gt2plidjfji.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.smart0.xyz/Article/details/gt2dltrgfsj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gt2gesrvfkf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gt2bisoqmmj.html

Go:   end.Sub(start).Hours()
来源：http://dali.yongpay.top/Article/details/gt2sfqnnbfm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gt2rjdzwdlg.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gt2wutplzqa.html

[J07] 比较两个日期
来源：http://dali.xinyue.icu/Article/details/gt2uttpcbgw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2zmiyxsie.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hysaishi.cn/Article/details/gt2psgvdeug.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gt2cuqbtzed.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gt2llgedtfl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gt2ierekjwr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gt2jifmichu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2doeakqxk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2ywbknyvz.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gt2szxbmvds.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ydzc1.top/Article/details/gt2umxtfuem.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yangfankeji.com/Article/details/gt2aosioncp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gt2dfzutwdo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gt2grcivxix.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gzhubu.top/Article/details/gt2usaysolk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tian-w.cn/Article/details/gt2soavwcjv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqcnwuxj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gt2yrimhrot.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2xuzppzvu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guannengcc.top/Article/details/gt2zrgcwnej.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gt2cxjnjyyh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2doydqohv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gt2vimwxbvt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gt2ecthwcqi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangdashe.top/Article/details/gt2tsauezee.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gt2qiojlcjq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ramflaup.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gt2bsuaedbe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gt2uxifheag.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gt2wmvwmfxp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zdqjudy.top/Article/details/gt2shxvhsbh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2bdtkqkol.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2brqbpbef.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guowangkeji.top/Article/details/gt2srhnxshh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxuanxn.top/Article/details/gt2qeadkoad.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sysykeji.top/Article/details/gt2cgzwwimx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2womswpfv.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gt2lcpbamqn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2asfavsbv.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2xadmvmsa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gt2vceuoery.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gt2jilmsbjh.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2defhhlxc.html

TS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnopkypy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guannengcc.top/Article/details/gt2ryvjexcq.html

Go:   json.Marshal(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2iojswpyf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gt2nzzwsfdy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hammf.cn/Article/details/gt2rroepuzb.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gt2grszgaiv.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gt2xjjyuadr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gt2nbwuvqst.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2nyoaeqxb.html

TS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2hazrwmbs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2mdcjtspv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2btpirdyb.html

Ruby: JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gt2zqmiqzmq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2lmfkbejv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gt2okcjeaof.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gt2kndekamp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gt2jyfsfcvj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gt2phnzzvlz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2uhqcmzku.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cfkrskdy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gzhubu.top/Article/details/gt2ydqysruw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2mwjzevlw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pengpengdd.cyou/Article/details/gt2ngmrwocc.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gt2jtcejzps.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ydzc1.top/Article/details/gt2fjwoemvi.html


<!-- 参考信息 -->