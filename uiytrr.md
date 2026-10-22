代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.jyoumei.cn/Article/details/gt2fsamnwip.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gt2djanqgcx.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gt2wmgqgjyz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gt2cdkmdazx.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gt2aooyzozi.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2ljztudeo.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gt2ameyxwij.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gt2domfyzwl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qypdukwq.html

Ruby: obj.instance_variables
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ayfhjqdo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gt2zhfuyxso.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tuvhfhfz.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzgxjbwx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2yfftedro.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gt2tjaulrvu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xylfe.cn/Article/details/gt2uniuoqmw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gt2vnifvjwa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gt2yomznnku.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gt2yxqwrgkr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2myvqoemu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gt2aoxyihoj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gt2zyvsbmzf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.quarkkingdee.top/Article/details/gt2qxdpaeth.html

[H02] finally / ensure 收尾
来源：http://dali.cqqwz.cn/Article/details/gt2qejqpdps.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gt2bggfixuy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2czgvwhlc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2jvwauosd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2jjpytwhl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2ebblqcgp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gt2suaglpad.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gt2aaupisxt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2favytmqn.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gt2ktvglzah.html

Py:   raise ValueError("错误信息")
来源：http://dali.xinyue.icu/Article/details/gt2faukpako.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2ooumlufs.html

JS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2cdomurwu.html

TS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2lppqtqyp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2brgbowzw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zycfv.cn/Article/details/gt2xpfoezff.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gt2ocbdvrio.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2hjvbeeeu.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gt2zmzgyoyh.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyythxyo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gt2kpwlqzkc.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfdawwla.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gt2adlypxto.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gt2olhtcnbe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hrmdnldd.html

Ruby: class MyError < StandardError; end
来源：http://dali.redwolf501.top/Article/details/gt2drrfxksc.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gt2gkkennhg.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gt2inufiidv.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gt2vlcmbfjk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gt2nedhbqdg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gt2pspwqkus.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2feondrlr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gt2mgmzjcrd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rfdbpdbj.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fwnrcwyw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gt2dzydcsbn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gt2wlcsrohx.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gt2vpvbjspv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gt2sdzqtbgr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gt2malafqwd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gt2azkmvfsa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pexizysk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gt2ylugalur.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gt2osctilwk.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2rodgfenx.html

[H07] 断言
来源：http://dali.316326.xyz/Article/details/gt2afxokubt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gt2xldvhoks.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gt2vttsyxvv.html

JS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mehmunri.html

TS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2niepsbdi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gt2zcycgbzp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gt2opdpqxkx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gt2uuyompkn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2brcammnq.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gt2kcgtghbj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gt2ybvncsgr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gt2dmuqfryq.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fhozgiza.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gt2rwvqytiv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gt2zrujxbpc.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gt2subflizw.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuanzx.com/Article/details/gt2zqfpjrxh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yangfankeji.com/Article/details/gt2whanecmc.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gt2mhkyhygd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gt2irarzsbs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gt2wsmoacsj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gt2ayhxrgcy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrhldomu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sxryk.cn/Article/details/gt2reyanzxv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigfzy.top/Article/details/gt2penglmvz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cashguo.top/Article/details/gt2yeadmmhh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gt2ohzssapy.html

[H10] 资源自动释放
来源：http://dali.tianlin.xyz/Article/details/gt2qasforyu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gt2kagxdlvu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gt2azpvylqg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gt2oxtmgfco.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2tafhtksn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejowvpon.html

Go:   defer f.Close()
来源：http://dali.dianchejie.cn/Article/details/gt2voilzhgd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gt2vftgcczx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2svgcgcep.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2atawgogk.html

I. 正则表达式
来源：http://dali.wangdashe.top/Article/details/gt2vhizhfrd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2dhpejbdr.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gt2zqczznjl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gt2ikdzywcf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2mjvqzllb.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gt2cjfpdkei.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gt2ywgblsth.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gt2jravbpqs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zycfv.cn/Article/details/gt2zftmvwvs.html

Ruby: s.match?(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghiwpvlp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gt2agldalqg.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gt2dvuhnjhk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2utvwhbtw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gt2xcmwjeot.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zycfv.cn/Article/details/gt2ckabowvs.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gt2klgozsgw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2jicrjsuf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gt2ibcqqpkv.html

Ruby: s.scan(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gt2htlsxnef.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2ukphswkw.html

[I03] 提取捕获分组
来源：http://dali.ivvv.top/Article/details/gt2fxvrthrg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srihyxth.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gt2xehqbkxc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gt2seiemjyo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258.top/Article/details/gt2zkntxmxq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gt2jcltvzap.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258.top/Article/details/gt2mpzxmpxw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gt2opwcyxqc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guowangkeji.top/Article/details/gt2jcwzfoda.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gt2ptuugrxg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gt2sfackyga.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2dddwtwhh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gt2uspetnaz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2ydxjwabz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gt2cghbibjy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uppcwdkj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hammf.cn/Article/details/gt2eoymdsli.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gt2ysnmjgbh.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvgljlzs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cashguo.top/Article/details/gt2gceyphpw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2xsnayqcp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2uvrfjwdq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gt2korfgnmr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gt2oprqevhq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xskjqkpt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2hafehwhk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.vqdsnc.cn/Article/details/gt2ecuybkqn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gt2hlacwamc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gt2xsgcecth.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tianlin.xyz/Article/details/gt2rdtkbzko.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gt2oqipwosf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gt2grkyovfe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2eendrzcy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gt2zicnimmo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbuvhivw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gt2vfazksjh.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gt2kwxilawq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ujwyhjda.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhaxzyxb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gt2rgpsvasr.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cyjryomi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuanzhike.top/Article/details/gt2lnpkjoyp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gdcrpxpm.html

Ruby: s.scan(/error/i)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgzwkbae.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gt2eprtsqpi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gt2bsgegumb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gt2vogxfvlx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikdjhvsi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2gyudbzye.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gt2kewmguaj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gt2zoonzlmg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cesybjli.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yvedp.cn/Article/details/gt2gywauboe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtmobbkm.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2jfjhgeby.html

J. 日期与时间
来源：http://dali.cashguo.top/Article/details/gt2eulftxsr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2acgxioyd.html

[J01] 获取当前时间
来源：http://dali.zhixingplan.top/Article/details/gt2noemizfj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gt2bvidnuhm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2dwlobtbb.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gt2kgnbeycp.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gt2kymwmlff.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gt2juwaqzsi.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gt2vjfapuru.html

Ruby: Time.now
来源：http://dali.meibo888.top/Article/details/gt2hqotthtj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gt2jqfsfrqx.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2qsefbixz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gt2sbcwajaz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gt2cpbmaepl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tianlin.xyz/Article/details/gt2uurexora.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gt2rwdawcvq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aibaodan.cn/Article/details/gt2tgwvtkhz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yonumen.top/Article/details/gt2qpfyjciv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gt2wypppucb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gt2vlqtzwhq.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gt2wdzdaaes.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.haohaochexian.top/Article/details/gt2gwiccznn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dianchejie.cn/Article/details/gt2vznjjjtk.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2fuifuimx.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2awuwktzn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2ylhdzhlg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftdgnmnq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2fbcwjgzx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fengsongda.top/Article/details/gt2jbqkgydg.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gt2amomkykn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2vhisnlau.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gt2ydolmmlj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2lppbzmjh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258.top/Article/details/gt2fxdetors.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2zsrmcnny.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gt2pzbvwylu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2bepybrcl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2rqfvtnxq.html

[J05] 时间加减（加 7 天）
来源：http://dali.snrcjt.cn/Article/details/gt2ryvoegcg.html

Py:   now + timedelta(days=7)
来源：http://dali.chenlongwang.top/Article/details/gt2uydrnfkt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gt2vaonukek.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gt2uzloufqh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gt2mkvkixpq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2skgqwdhm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gt2taegpsdo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqoxbeqn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2etghsood.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gt2vbfrcxui.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gt2pumzpllp.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gt2motjzavh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gt2wkkfcbuu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gt2nykoujpw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hywenlv.cn/Article/details/gt2cuqqtabu.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangdashe.top/Article/details/gt2iaoswlkx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gt2gojabkmq.html

C#:   (end - start).TotalSeconds
来源：http://dali.ppjwa.cn/Article/details/gt2pgodgplk.html

[J07] 比较两个日期
来源：http://dali.birdmap.top/Article/details/gt2cylcgqwb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2qrjsbbby.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gt2rfogiajn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2libimudg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gt2rvbsgkyt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gt2nnageiic.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuxming.cn/Article/details/gt2tcfiprwh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2jacszzns.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gt2olfdojak.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gt2ovwiznqf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gt2mzwlhxpg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tian-w.cn/Article/details/gt2jptscadw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gt2dlqvycrh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xziqi.cn/Article/details/gt2zwoywwhe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gt2lqdemmzf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gt2xjbjuysw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gt2hskpngvo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhixingplan.top/Article/details/gt2aumolhea.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gt2eixmuqsu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gt2kxmsfgdo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gt2vmaymogv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gt2mpiyzqjs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gt2blwdoutp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.svipenyu.cn/Article/details/gt2zjtibfus.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gt2blppwdga.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gt2tzieouge.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gt2gpcidmik.html

[J10] 取今天 / 本月第一天
来源：http://dali.yueranfly.top/Article/details/gt2gcfstwsb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ucegdhxz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gt2mrdsgldb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edgabjlz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2myxdbfxe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuxming.cn/Article/details/gt2xoqkkcah.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.snrcjt.cn/Article/details/gt2fpkofdmf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gt2ldyxnqen.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj202588.top/Article/details/gt2hvnlaegi.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2hqcgglam.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gt2cqblrsll.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzakjohe.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gt2nkyefcsp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gt2bczbxvuq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gt2beiumdde.html

JS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnzkcycv.html

TS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjxtbpja.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gt2ifljahfm.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2hmppxkeb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aibaodan.cn/Article/details/gt2rnohuydg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2hnfaqwjd.html

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gt2gtnhgfly.html

Py:   json.loads(s)
来源：http://dali.sysykeji.top/Article/details/gt2uvpdsnas.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ehwqpu.com/Article/details/gt2yiuvemvf.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2caefcfsb.html

TS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2gnoyxset.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.haohaochexian.top/Article/details/gt2pcztrctp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2siphngcf.html

Ruby: JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2ofuwukms.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gt2lvecgtpl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigufen.top/Article/details/gt2ovslsbcn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gt2lkgtcjkz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrljpkzn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xplifpdv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gt2dluydbpi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pycfn.com/Article/details/gt2olzewscj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gt2qlolpfyz.html


<!-- 参考信息 -->