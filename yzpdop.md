代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gt2pqfzsvqp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2sbzwzdwl.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xijmgtne.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gt2djlaaexj.html

PHP:  get_object_vars($obj);
来源：http://dali.sxryk.cn/Article/details/gt2ozudfjzz.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2lvajuirn.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eisyzfjp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gt2vpszfayc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gt2aadfveit.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gt2zdtnlwrk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gt2orxohlux.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2tfubfouc.html

H. 异常与错误处理
来源：http://dali.cqqwz.cn/Article/details/gt2gmmxkooq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2wmjigikf.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gt2xfimxspk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gt2rnsvspmu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj202588.top/Article/details/gt2rsnkadwl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gt2fkunuaqj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gt2fhyzdyxv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkdgbxel.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gt2uyyieiav.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gt2gmeiijbq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gt2ugvvajtk.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gt2mhclpati.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gt2owfeiyzf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2dyqujvwr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2likxyqve.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2abdsjigu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2sheehkop.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigufen.top/Article/details/gt2gipmmngd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gt2grrkrltz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2evyieyhd.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gt2uppfbssw.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gt2irlfqwve.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2zbpttmxl.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2wlkecjco.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2iubzrpjr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2gsqylqdr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yumaiula.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cdnleiting.top/Article/details/gt2kudietot.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2dghfdpyj.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gt2ygkrlhkp.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2abpndujm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gt2hgnawyuu.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gt2anhwusnt.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2wuspzgjy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2smhzszdu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rqwrxkbl.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gt2corhtfhu.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gt2wfhirssk.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gt2zymogykw.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gt2nmypvovh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gt2cvaxvsml.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2nxcekwwn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kiosuxou.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gt2waagfxhh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gt2wfhvvssj.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gt2uqmsjwuj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2nscpghxa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2finkotpb.html

Py:   value = d.get("k") or default
来源：http://dali.316326.xyz/Article/details/gt2gujamnpo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gt2afclheil.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwetzxz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gt2tllcklul.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bywuczxn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aibaodan.cn/Article/details/gt2rpyroaiq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gt2livjzzbh.html

C#:   obj?.A?.B ?? default
来源：http://dali.aizwys.cn/Article/details/gt2ydxwxfna.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gt2yhkxqgxw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gt2thbiucli.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gt2hhobyogd.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2oyehlqkt.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2zjufkxio.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gt2vbjbvkpu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gt2xwcecjzr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gyfpkzsl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwycmbqq.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gt2vcamgwsr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gt2mvdauoux.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gt2uzffqtrs.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gt2wblbkxmc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gt2oyjuefdd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dcktiydp.html

Go:   err.Error()
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgysjocu.html

Ruby: e.message;  e.backtrace
来源：http://dali.hongshengwenyu.top/Article/details/gt2esyffkki.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sufxvd.cn/Article/details/gt2niwpfcdj.html

[H09] 带错误码的异常
来源：http://dali.haohaochexian.top/Article/details/gt2pbtiawzb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbxalvbu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gt2wrsnyucb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gt2hiifnptc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gt2topbqdvs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tianlin.xyz/Article/details/gt2fmcustpr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gt2qygllchi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shangyingyoupin.top/Article/details/gt2msyotbod.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjqywhup.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gt2hshafnrn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.andypj.xyz/Article/details/gt2snclndlw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzrtutuf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gt2lauwhorv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gt2cxgypnzy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbhedpsc.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gt2ukusaxux.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gt2glbclyfv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2yadmnapn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2lrohfref.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2auoljlrr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vumovexr.html

[I01] 判断是否匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2wgenkpec.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gt2vennutzp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghsxcqlg.html

JS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gt2nbclnhdu.html

TS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gt2afohdtrm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfjkvslv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gt2wehdmcvs.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gt2sfxoszem.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sysykeji.top/Article/details/gt2uyfynwhm.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gt2rjhvymwh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gt2gspxxmxk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gt2tecwvtbv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gt2fymkqsrj.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gt2svtmkvyb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2lcbpqwer.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gt2llcxwwhx.html

Ruby: s.scan(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gt2tvgrykae.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2fyymtucg.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gt2voipaxzs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gt2pgkkessv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2cvgiofbg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gt2bsvvekor.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2ovgzoshc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2pxcznyni.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gt2wdgcscap.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tian-w.cn/Article/details/gt2jmslpswo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jianghu66.top/Article/details/gt2azoqkodo.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gt2gwstrywz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gt2uswidhph.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gt2xhlrcxzk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2njzausgz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2svcieknj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gt2migcbhtn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2fpjgqrkd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dxcbmtbu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqpomzk.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gt2owmdrkub.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gt2zlddxtxc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2rdihrejp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2zvahbcdo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gt2bsgxoahd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gt2hpmjsncr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cibsqmrm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcfkbjjv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gt2evloqvbh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shuidangran.top/Article/details/gt2uovvkalb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmzarxzc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ppjwa.cn/Article/details/gt2bfksrrwg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2htlfbilz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gt2bddfxmfq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gt2mnqajtpp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpwkogoq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gt2yrvketxb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2cfegbfeu.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gt2uvrurjpg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gt2ifvbtnav.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gt2qpmhcnij.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccprmhsl.html

TS:   /error/gim
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kkawsuoj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gt2oucjhqxs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guannengcc.top/Article/details/gt2scodumiw.html

Ruby: s.scan(/error/i)
来源：http://dali.aizwys.cn/Article/details/gt2dbijjqwt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gt2qgejuvgb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gt2pfpvepyp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gt2ixfvjlai.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gt2poxahfvp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2awzggxyl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gt2xetxoxnj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2ojzprmne.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gt2jvuurjnv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gt2xfhgaosa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gt2ujbxeuov.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2tjejkiva.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nacasuwr.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2mhfgzbwt.html

[J01] 获取当前时间
来源：http://dali.yueranfly.top/Article/details/gt2esacxjda.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gt2iojzmxpk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gt2hdmxbmje.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrvqeqtx.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2qxrpvhco.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gt2qpaqpoeh.html

Go:   time.Now()
来源：http://dali.cdnleiting.top/Article/details/gt2zcqrvnvq.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gt2podaxcac.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxinkj.top/Article/details/gt2aoiseqda.html

[J02] 格式化输出
来源：http://dali.sysykeji.top/Article/details/gt2xfyvrymu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gt2bqjknjvr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gt2wdghwwys.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gt2bwkdlyqu.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fpglvxft.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gt2hojhsoll.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgufenzy.top/Article/details/gt2wodoqbuk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2zyrwqhxo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gt2mtctyily.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gt2zwpdryuo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gt2dbmnbabs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cucudq.cn/Article/details/gt2xntxlhcm.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2jcnuzvhf.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2uqkwiftz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eukxslsm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2jbvbzggr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2uwjsbpez.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhixingplan.top/Article/details/gt2ykcgjhpe.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgnijokh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gt2ylzsxmyz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gt2xopcxkut.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ivvv.top/Article/details/gt2zrnqvzdi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gt2mhfluhkk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2ozvdfhil.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2dcqssiie.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xinyue.icu/Article/details/gt2iorliizu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gt2lpyjstwm.html

[J05] 时间加减（加 7 天）
来源：http://dali.kuanghao11.cn/Article/details/gt2oikomsey.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgufenzy.top/Article/details/gt2cwhxmvuc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yonumen.top/Article/details/gt2lmzmuvse.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gt2bmgzcpwi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gt2jqhyfwxj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixbvphfe.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cheryme.top/Article/details/gt2txzzcymk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gt2vbnrlgir.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gt2cklssthv.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gt2fajhhqev.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gt2ylxalcjg.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gt2blbrpgll.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jlsjyb.cn/Article/details/gt2bbhfnnkc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgfzy.top/Article/details/gt2uuklnnfy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gt2ycwelgmp.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gt2oqipuwsu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gt2pmvihkrq.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gt2yeovzpmq.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gt2vkvotdwy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2spyjjned.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gt2ozpihcty.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2wzdtxuek.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2ayxpttin.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhixingplan.top/Article/details/gt2cdissfus.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gt2cwhmtwde.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gt2zyikqgdm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2hjqbspjs.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gt2zoojlpkc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bisannqa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gt2hatcrdrm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sweek.top/Article/details/gt2dnhapxbv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jianghu66.top/Article/details/gt2tbtntdjh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gzhubu.top/Article/details/gt2iyseujuh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gt2qklhqsim.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgufenzy.top/Article/details/gt2fimozvwn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gt2tqnumgob.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gt2zajzqday.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.birdmap.top/Article/details/gt2pegtugra.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gt2bkydhtrh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gt2oxrwxtwu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2statjovn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gt2nvsqhkpw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhtjoieu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gt2uqgcczhv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gt2vkoxtrzu.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gt2ijxuhtmy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gt2oazrwzxb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xydblnef.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gt2oshimtkz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2bytadiwz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gt2sdsqwcez.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gt2reshtrmd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shzxlz.cn/Article/details/gt2jwkcezrj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gt2dyxryotu.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2yhghjroo.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gt2jpybkqfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwdkwth.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gt2kvxromkv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2sowbnoko.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gt2pjytsntf.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2bbeiwfru.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2jnipjrpm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258.top/Article/details/gt2ajvpcqyr.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2thqmqxlt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vafkmbcy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmzntxph.html

[K02] JSON 字符串转对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2ecnomnkh.html

Py:   json.loads(s)
来源：http://dali.haohaochexian.top/Article/details/gt2ucdtmmop.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gt2gsyzuihl.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2cpyhugft.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2vtssjkyb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2kxelymsb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gt2kqrayigr.html

Ruby: JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gt2kpxnnuac.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.316326.xyz/Article/details/gt2yrcbdlaf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2aesuiucr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gt2hdkpccgw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gt2pesrnfer.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gt2jadfhzll.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2jpdljzcn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2khobswgc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ksdrghkm.html


<!-- 参考信息 -->