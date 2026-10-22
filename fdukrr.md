代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtqxenephd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtuqyeeoix.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigufen.top/Article/details/gtsnullecx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtwesugpzc.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gtarkynbzj.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfsayjiy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtchjwkzaq.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtgeospegw.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gthqbglqrl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtfvnkoofg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtxyufmmda.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gthqltkova.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtqyjuplwn.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gtljnoiebr.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigufen.top/Article/details/gtmlkzoget.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtfhqxderf.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmexqiwdu.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtexgesqle.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtvjmonbjt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ehwqpu.com/Article/details/gtespxazmg.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gtwgppwszr.html

C#:   class MyException : Exception {}
来源：http://dali.shuidangran.top/Article/details/gttnvzrvkv.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gtgettpjin.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gtpxwhelli.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gtrlkhyozx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtqptbxkqf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtxfslqzlw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gtnkcmeedf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daxiang520.top/Article/details/gtbxmvkaqt.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gtxglblkdk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hysaishi.cn/Article/details/gtvfbztbmv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gtgmcaegav.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gtwxitlmrd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtkzrtqaop.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtagnkccrv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtrevxcecv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtppxzakst.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gtzisxshze.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hfpthk.cn/Article/details/gtqumhfkhp.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtyfsqdppe.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gtwdeooxsz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuxming.cn/Article/details/gteqzwuafh.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gtsmgmuuar.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtqblhmbmt.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtetxpodkd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gtbwtfqhyo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xylfe.cn/Article/details/gtlzyislvi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhongyouzk.top/Article/details/gtfzmwjluy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdemtcre.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gtyrigpbso.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ppjwa.cn/Article/details/gtxhqhhvtg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtvtntghes.html

JS:   e.message;  e.stack
来源：http://dali.cashguo.top/Article/details/gthzxsfxam.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gtmdeualir.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shuidangran.top/Article/details/gtgbtbelsv.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gtxgmqgnnw.html

Ruby: e.message;  e.backtrace
来源：http://dali.yvedp.cn/Article/details/gtkavjurzw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgufenzy.top/Article/details/gtjhtzttoz.html

[H09] 带错误码的异常
来源：http://dali.aibaodan.cn/Article/details/gtvkvqadms.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gtwwctoqjm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbltfpry.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gtnogidiex.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhongyouzk.top/Article/details/gtjoabxnuh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ivvv.top/Article/details/gtpietufmr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtcaqjenju.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.birdmap.top/Article/details/gtkcpmtove.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cdnleiting.top/Article/details/gtxrpdfodp.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gtqlbfpdxp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckmattmf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gtyzknryai.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtrfbhjgeb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgecpser.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dianchejie.cn/Article/details/gtqlcrfadp.html

Go:   defer f.Close()
来源：http://dali.hammf.cn/Article/details/gtzhswwkep.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gtfxotritk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtnlyqguhq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqdmaphph.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gtykkvfvbp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtitfapjzk.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtunujkwte.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtqfqftoxc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtvkrbbfxp.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtginvmxwm.html

TS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtvvemurxv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gtztchswkp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.redwolf501.top/Article/details/gtmwpqfnsq.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiigwejnh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sysykeji.top/Article/details/gthvvhpepn.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqoebkhe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtpyxajsrg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtywzmcvya.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hysaishi.cn/Article/details/gtwpbvwzxe.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gtxyxrxlbe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtvyhsyccv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtggfjrjzb.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gtcptlybae.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtsqryxnxy.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gtawpyyopn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtneqjeoch.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtjyhxsnzk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xinyue.icu/Article/details/gtlyxenkst.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.haohaochexian.top/Article/details/gtvqdigyid.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.andypj.xyz/Article/details/gtzzwysrck.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gteyjlquhs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlewwdtlr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gtatjgjtcx.html

[I04] 正则替换
来源：http://dali.9152youxi.cn/Article/details/gtrchpuhai.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqzsahuo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gtovjwfgrl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtsurhqqpq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtrborunzw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gtqroaxkuf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gtqhlhtqqk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.andypj.xyz/Article/details/gtjuvujflt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtuyscwuva.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gtxhsrbwvn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.0kj1m.cn/Article/details/gtemlmryqb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtlibnkufo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtqoembcrx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gthimysldo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gtwdfdaskh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtbinmykwz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtllintxog.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gtcssdubxm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gtemwryzaz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtnrpxxugu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zycfv.cn/Article/details/gtixelolbu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtltrvwgyq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwkhleja.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtvluwcfcn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tian-w.cn/Article/details/gtbuftgkhy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtvmezqzxu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtfdxpqqgr.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxinkj.top/Article/details/gtrfntaoiz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gtxqqhavfa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtgkvfynqy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgxnxjbx.html

TS:   /error/gim
来源：http://dali.cheryme.top/Article/details/gtvlevzzir.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddgbeopu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhongyouzk.top/Article/details/gtmtypaqxt.html

Ruby: s.scan(/error/i)
来源：http://dali.jyoumei.cn/Article/details/gtodxhyiyg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gttggosbui.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tianlin.xyz/Article/details/gtkuhlmmqc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtllmnrsfp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtyomtestn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtiotqtbmc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtvhdvpnns.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gthoniekhv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gtozvthgwp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ybcxt.top/Article/details/gtygoawcwq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gtnkymsdhw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttvvhqqha.html

J. 日期与时间
来源：http://dali.zhengqikj.top/Article/details/gtveepsdux.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfwpoheyh.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gtzddcbwiv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gtyvsrlslh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtogjggvkv.html

JS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtsbivrhcl.html

TS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gtbrgqthbp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gtqweoximd.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gtgbcdpzgd.html

Ruby: Time.now
来源：http://dali.hammf.cn/Article/details/gtzslgodfs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gtbnqdpcbs.html

[J02] 格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjdtraxb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gtxrsmovcb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gtsovokzvq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gtfeadmctp.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gtcligqxla.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gttqteqdiq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gtgftnwliu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtcuoiitxm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gthuoygvup.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gtafkzjxcz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xziqi.cn/Article/details/gtokxyftsj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dianchejie.cn/Article/details/gtmqckwkij.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtjhxcwooh.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtuklqtovz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtmjvvliay.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtqsbfcwvm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtxctmcigv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.iojbl.cn/Article/details/gteadeejmk.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gtnckwnwcg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtplzxjqcl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gtklsfyctz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gtjjqvdqkw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsckmpifl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gtuyavxkii.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtrauvdjxf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gtvnnwzidf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gtyreisfqt.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gtlifcqsvj.html

Py:   now + timedelta(days=7)
来源：http://dali.feifeiyinyue.top/Article/details/gtxcbuiwvm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.snrcjt.cn/Article/details/gtwrvugjua.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtgqidtmwy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtwpvadgwr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtjxsluycx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtdzayedqq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gtmszvmyas.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gtoeuduntx.html

[J06] 计算两时间之差
来源：http://dali.birdmap.top/Article/details/gttnrcuctv.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gtpujxstzx.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gteqqayijc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gtmegtvzwt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gtnppwwyxf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gtqtvtwukw.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqdakgqe.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ydzc1.top/Article/details/gtypvwsqsg.html

C#:   (end - start).TotalSeconds
来源：http://dali.sxryk.cn/Article/details/gtpylurufz.html

[J07] 比较两个日期
来源：http://dali.wangdashe.top/Article/details/gtphydlxqm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtmrdxxfbw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gtdtftmkjo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtamfyyezr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtbugoglpj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sufxvd.cn/Article/details/gttzlmezby.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gtczwsxwgu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gthyrbuwpl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtrnpwdkse.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gtezkwtxdg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.feifeiyinyue.top/Article/details/gtctvpnkrx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gtxvaulaqw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gtuyvxpovh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gtxzokimhx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gtavfxbctx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxinkj.top/Article/details/gtzkahgmcr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gtqvjoaqcg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtatzmqupy.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gtdvkzyeyt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gtntwepknt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gtfozagsbh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gtmvnpkmnt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtoefnlpla.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gtocculfkz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gtaewwzzmy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.andypj.xyz/Article/details/gtmrwfrsvc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gtuyihvyva.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gtftmricbv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gtkfzdvntv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gtefcmtecm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtriuiswaz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtjngleprh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gtkwbwmxye.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hongshengwenyu.top/Article/details/gtxnocudpx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigfzy.top/Article/details/gtsgqmzirm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ppjwa.cn/Article/details/gtzgpltqcf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtmonccrmp.html

K. JSON 与序列化
来源：http://dali.tianlin.xyz/Article/details/gtcquwsmkk.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqeltyeg.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gtzkzzsvbp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtxrkhgsda.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gtnbvigkgb.html

JS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtezhydwoe.html

TS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtkgcfuddr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jlsjyb.cn/Article/details/gtobouhbby.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gtgiqlhogs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gtsgogyjxp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgfzy.top/Article/details/gtwuwggovw.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldbzsemd.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gtxfdolfbg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gtihgsorvd.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtrykrxwum.html

TS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtqlkdnhpu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gtwibsbjib.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtmndyxdll.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtryohiwex.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gtfvdicvhm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxinkj.top/Article/details/gtpjsjkbec.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtoxznglmi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtyasloymd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtgxlgmfyx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gtscdtzsgz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnqzz.top/Article/details/gtcksyqcdj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxuanxn.top/Article/details/gtlzptkjqv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gtdkuloznf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangshuangyany.cn/Article/details/gtsgjezvwb.html

[K04] 读取 JSON 文件
来源：http://dali.havefunace.top/Article/details/gtolcikkna.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gtquxdbrsh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gtrrjomegs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtgvcjebnn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gtcunvyhrd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtehjtfodn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtdlcpmatq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxgjwtcf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtlkbdrtwq.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gtjejsxtot.html

Py:   copy.deepcopy(obj)
来源：http://dali.9152youxi.cn/Article/details/gtfcdrnzvk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gtpfjjkodo.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtrbtitabd.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtugbyogqv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dashuyun.cn/Article/details/gtvpqpaefd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gtzfuwrwli.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cdnleiting.top/Article/details/gtathcacyq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gtnscpaqir.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtnrxiwysp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gtqwftpljz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gtdagnkjzv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtyrfapkpa.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtmrewhmwa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gtbdrrfmzr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtgzgllnbx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtnkhdvapj.html


<!-- 参考信息 -->