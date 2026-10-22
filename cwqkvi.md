代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.c1oappe.top/Article/details/gtlzrjjzgy.html

[Q69] 查看执行计划
来源：http://dali.sufxvd.cn/Article/details/gtdsemlgcp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yongpay.top/Article/details/gtonojpqas.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gtixjngjzo.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gtdfbctlkq.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gtudkhcvgw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zdqjudy.top/Article/details/gtxkeaszqb.html

[Q72] 查看索引
来源：http://dali.hnqzz.top/Article/details/gtlpgievyi.html

SHOW INDEX FROM users;
来源：http://dali.pycfn.com/Article/details/gtjfkwjebu.html

[Q73] 查看表状态
来源：http://dali.mhx1999.top/Article/details/gtucoohndk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgfzy.top/Article/details/gtvrnxzwlj.html

[Q74] 强制使用索引
来源：http://dali.hongshengwenyu.top/Article/details/gtaxbywcdm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.iojbl.cn/Article/details/gtgoqkejoh.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gtrprabpzc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258.top/Article/details/gtedvwcldy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gtbhwdhely.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gtggsnhaob.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gthpgbiofj.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gtkldsimnz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sufxvd.cn/Article/details/gtclcgvqun.html

[Q78] 当前时间
来源：http://dali.yuxming.cn/Article/details/gteqmgtely.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yueranfly.top/Article/details/gtoqhloujc.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gtvtqmtmre.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.havefunace.top/Article/details/gtsykcgszf.html

[Q80] 字符串截取
来源：http://dali.pengpengdd.cyou/Article/details/gtmiwfcvek.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtcmerivnz.html

[Q81] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gtihcovfda.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gtwpjlcvip.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gtfghdwela.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtxnzsfnkp.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtrdmtkqyt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtdhdpldpv.html

[Q84] 去除首尾空格
来源：http://dali.daxiang520.top/Article/details/gtugrsgufi.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtacuauval.html

[Q85] 数值取整
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfhrhabx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pycfn.com/Article/details/gtupkbbqlu.html

[Q86] 读取 JSON 字段
来源：http://dali.cheryme.top/Article/details/gtdsfvoycs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.snrcjt.cn/Article/details/gthlxrwgaj.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigfzy.top/Article/details/gtzcwmgwui.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gtbulcfwdt.html

[Q88] 行转列（条件聚合）
来源：http://dali.iojbl.cn/Article/details/gtshjreyzr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangshuangyany.cn/Article/details/gtqrxuxyue.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sufxvd.cn/Article/details/gttbdauluc.html

[Q89] 判断表是否存在
来源：http://dali.cucudq.cn/Article/details/gtgckdtohd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.vqdsnc.cn/Article/details/gtcvmvyamd.html

[Q90] 生成序号列
来源：http://dali.316326.xyz/Article/details/gtxhxmebgg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gtakxzygkz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtsvkbcqkd.html

R. Bash 专题
来源：http://dali.bjfxy.top/Article/details/gtobduasrj.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtehsinmnt.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gtpmfjmdlp.html

#!/usr/bin/env bash
来源：http://dali.gaohongyu789.top/Article/details/gtcfdnagfc.html

set -euo pipefail
来源：http://dali.hfpthk.cn/Article/details/gtpcffctip.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gtchypgizu.html

name="Tom"; echo "$name"
来源：http://dali.svipenyu.cn/Article/details/gtvwvgtqtj.html

[R03] 只读变量
来源：http://dali.jiagoushi.top/Article/details/gtcavbqfor.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gtsgejabin.html

[R04] 位置参数
来源：http://dali.cdnleiting.top/Article/details/gtssqwmucs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gtulvzqeuw.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtuatxwqfk.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gtzpsufrts.html

[R06] 判断命令是否存在
来源：http://dali.xziqi.cn/Article/details/gtcxnyvzjd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gttvqkkthl.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtvphhmmfx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtujkooanb.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gtnjvjclko.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtasinrywq.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gtinlyavmo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtaxmfprdi.html

[R10] 正则匹配
来源：http://dali.zdqjudy.top/Article/details/gtbzdauykb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gotoacloud.top/Article/details/gtvvodkbpb.html

[R11] case 多分支
来源：http://dali.shzxlz.cn/Article/details/gttiwdftfm.html

case "$1" in
来源：http://dali.pycfn.com/Article/details/gtqdgonazi.html

start) echo "启动" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtsufgmxki.html

stop)  echo "停止" ;;
来源：http://dali.hammf.cn/Article/details/gtnaoderqw.html

*)     echo "未知命令" ;;
来源：http://dali.wangdashe.top/Article/details/gtpdmmepgb.html

esac
来源：http://dali.xziqi.cn/Article/details/gteijaowtk.html

[R12] for 遍历文件
来源：http://dali.hfpthk.cn/Article/details/gtccvepvyc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.kuanghao11.cn/Article/details/gtsbyskogh.html

[R13] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gtomaygyyx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtgbsqoerw.html

[R14] C 风格 for
来源：http://dali.pycfn.com/Article/details/gtwfhaqmbj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtnbaqqomc.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtgfbizoil.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gtgelvxfzo.html

[R16] until 等待条件
来源：http://dali.fengsongda.top/Article/details/gtanfugiiz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtqeptnxjt.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gttvjzhezy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.svipenyu.cn/Article/details/gtirlkymjx.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gtxlmhpsra.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gtlqrwbaxs.html

[R19] 数组长度
来源：http://dali.316326.xyz/Article/details/gtnhedpizd.html

echo "${#arr[@]}"
来源：http://dali.quarkkingdee.top/Article/details/gttfzngxmh.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gtbuizsjwb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gtscchmgjt.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gtmaaglyqa.html

echo "${#s}"
来源：http://dali.jqgfzy.top/Article/details/gtmmroodmr.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtmjzlrvbp.html

echo "${s:0:5}"
来源：http://dali.kuanghao11.cn/Article/details/gtufzvevcn.html

[R23] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtawrgejbh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gtnhpmsihw.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnmaaffr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gtfvxrbdor.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gtxiguolup.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gtinnubxxr.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbtlzzld.html

now=$(date +%F); echo "$now"
来源：http://dali.zhixingplan.top/Article/details/gthfvdnafu.html

[R27] 算术展开
来源：http://dali.sweek.top/Article/details/gttnrsicpd.html

echo $((1 + 2 * 3))
来源：http://dali.feifeiyinyue.top/Article/details/gtlthbunzr.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gtwhmskrvz.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gtwfzgssyy.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtjvigsugu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehrrhgvs.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gtiacyqloi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guannengcc.top/Article/details/gtfhzwwhfw.html

[R31] 局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyozvsdwy.html

f() { local x=1; echo "$x"; }
来源：http://dali.ivvv.top/Article/details/gtzlgadepj.html

[R32] 参数个数校验
来源：http://dali.nanxuanxn.top/Article/details/gtfmgaiiat.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtvwsodsrv.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gtxlwfcmdv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gtaxbsppfh.html

[R34] 退出时清理
来源：http://dali.dianchejie.cn/Article/details/gtiaxvulgi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtixpngtrn.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gtlyoakrjd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zdqjudy.top/Article/details/gtszfvsmhs.html

[R36] 并发执行多个任务
来源：http://dali.meibo888.top/Article/details/gtwhawyiak.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aibaodan.cn/Article/details/gtvkjazshk.html

[R37] 把输出赋给变量
来源：http://dali.yongpay.top/Article/details/gtlhwankar.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gtxkysgddi.html

[R38] 管道串联
来源：http://dali.yueranfly.top/Article/details/gtptczxhod.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jyoumei.cn/Article/details/gtmkwkscnd.html

[R39] 重定向标准输出与错误
来源：http://dali.shangyingyoupin.top/Article/details/gtzhaxwmwu.html

cmd > out.log 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmeurnxns.html

[R40] 追加写日志
来源：http://dali.hongshengwenyu.top/Article/details/gtidpmeybe.html

echo "log" >> out.log
来源：http://dali.zdqjudy.top/Article/details/gtbneuwdlm.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gtwjkoosiw.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gtknbwvkgz.html

[R42] 输入重定向
来源：http://dali.guannengcc.top/Article/details/gtofgfulbt.html

wc -l < a.txt
来源：http://dali.yonumen.top/Article/details/gtnldbaoca.html

[R43] 按名字查找文件
来源：http://dali.daxiang520.top/Article/details/gtlmjrpjxk.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gtouytcthj.html

[R44] 按修改时间查找
来源：http://dali.zhiwuduotai.top/Article/details/gtqnwufcxl.html

find . -mtime -7 -type f
来源：http://dali.yongpay.top/Article/details/gtqlygzzwh.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gtmwaxwteo.html

find . -name "*.tmp" -delete
来源：http://dali.hywenlv.cn/Article/details/gtmzytzfim.html

[R46] 递归替换文件内容
来源：http://dali.havefunace.top/Article/details/gtfocidrii.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgfzy.top/Article/details/gtlnnjmjbn.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gtfulsgfaw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtswmcmbis.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gtwibpdlxp.html

awk '{print $1, $3}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtvqpziecu.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gtkfzhyoap.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gtnuqbvodz.html

[R50] awk 求和
来源：http://dali.havefunace.top/Article/details/gtjlcxhrqo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtttvbviyu.html

[R51] 排序去重取前几
来源：http://dali.chenzaomai.com/Article/details/gtryahnxmk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guowangkeji.top/Article/details/gtzyccbwvd.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gtnndxuxwl.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtwhwaxuyx.html

[R53] 查看文件头与实时尾
来源：http://dali.ppjwa.cn/Article/details/gtinqipsnu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gthlkecsoj.html

[R54] 比较两个文件
来源：http://dali.wangshuangyany.cn/Article/details/gtwjyvmsrk.html

diff a.txt b.txt
来源：http://dali.zycfv.cn/Article/details/gtnzpfteeq.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gtkkrgxgxl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.bjfxy.top/Article/details/gtbowrbmzj.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gtlxrxopwy.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gtkpemsqbp.html

[R57] 远程执行命令
来源：http://dali.yj20258.top/Article/details/gthxmrhcpp.html

ssh user@host 'uptime'
来源：http://dali.yj202588.top/Article/details/gtrebocyhh.html

[R58] 下载文件
来源：http://dali.daxiang520.top/Article/details/gtewnwxmhi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gtnwejkgkg.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtbuykvzkq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgejhrqca.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtmbgpljlq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shzxlz.cn/Article/details/gtkvhcqcgm.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gtggsfxwyq.html

df -h;  du -sh *
来源：http://dali.sufxvd.cn/Article/details/gthoxgyokv.html

[R62] 找最占空间的文件
来源：http://dali.xuetiantiany.cn/Article/details/gtyrkwxcjz.html

du -ah . | sort -rh | head -10
来源：http://dali.tian-w.cn/Article/details/gtvtboyddv.html

[R63] 内存与进程
来源：http://dali.yueranfly.top/Article/details/gtgszonpvz.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gtmavjjsfe.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gtlthrcvko.html

kill -9 $(pgrep -f app.py)
来源：http://dali.quarkkingdee.top/Article/details/gthjwbiecj.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gtaegovgls.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fengsongda.top/Article/details/gtysatcocw.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gtqlkjhshd.html

crontab -e;  crontab -l
来源：http://dali.andypj.xyz/Article/details/gthxqqggtn.html

[R67] 生成随机十六进制串
来源：http://dali.sxryk.cn/Article/details/gttiinfwfo.html

openssl rand -hex 16
来源：http://dali.jinqigfzy.top/Article/details/gtldkjduud.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gtltaaqtdx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtyhjqzora.html

[R69] 生成随机密码
来源：http://dali.ydzc1.top/Article/details/gtzvvnbbtz.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gtbgvrpdlv.html

[R70] 时间戳与互转
来源：http://dali.zhixingplan.top/Article/details/gtbvqkwoxh.html

date +%s;  date -d @1700000000
来源：http://dali.hywenlv.cn/Article/details/gtraranazd.html

[R71] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gttdzwlvkt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuxming.cn/Article/details/gtenifdotj.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gtyufwpttu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gtxnfatshv.html

[R73] 分割大日志
来源：http://dali.ybcxt.top/Article/details/gtbxegstfq.html

split -l 1000 big.log part_
来源：http://dali.hywenlv.cn/Article/details/gtynoivhdk.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gtcbbfvzys.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtxouhnath.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gtvrbybhqs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuanzhike.top/Article/details/gtzhzybiap.html

[R76] 使用临时文件
来源：http://dali.aibaodan.cn/Article/details/gthbkhavuq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlvzdumy.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gtrfnxajoa.html

read -rp "请输入: " ans
来源：http://dali.yongpay.top/Article/details/gtfrpfzqun.html

[R78] 交互式菜单
来源：http://dali.ivvv.top/Article/details/gtmptoxcbr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daxiang520.top/Article/details/gtbicusygj.html

[R79] 解析命令行选项
来源：http://dali.nanxuanxn.top/Article/details/gtxjvwrsan.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jiagoushi.top/Article/details/gtlmchuibn.html

[R80] 查看脚本执行耗时
来源：http://dali.chenlongwang.top/Article/details/gtkfbiilux.html

time ./run.sh
来源：http://dali.yj20258888.top/Article/details/gtfrezwhkz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtelewpraf.html

S. C / C++ 专题
来源：http://dali.gotoacloud.top/Article/details/gtxsnjrkwy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtihmsxils.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gtqlayhwdh.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gtopimtwti.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gtjvdoueba.html

[S02] C：变量与格式化输出
来源：http://dali.xylfe.cn/Article/details/gtsvvxiwkx.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gtxhcnietw.html

[S03] C：读入整数
来源：http://dali.daxiang520.top/Article/details/gteifbfwkv.html

int x; scanf("%d", &x);
来源：http://dali.redwolf501.top/Article/details/gtwhcziixf.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gtcgrmrtyd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cheryme.top/Article/details/gtoxwxwbsk.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggrumuwt.html

strlen(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxnwblky.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gtsddjxboa.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gtqkjswmwr.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gtdtpdcouf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tian-w.cn/Article/details/gtzncfecks.html

[S08] C：动态内存分配与释放
来源：http://dali.nwbrower.top/Article/details/gtjkagvgxc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gtlowplsjy.html

[S09] C：结构体定义与初始化
来源：http://dali.shzxlz.cn/Article/details/gtfcjgonny.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgufenzy.top/Article/details/gtywgkkpbf.html

[S10] C：指针与解引用
来源：http://dali.jqgufenzy.top/Article/details/gtmxtzkwcr.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gtwcwlibfu.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gthxuagmzi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gtdbzrlpda.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtijlxtrlw.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gtaubsbssv.html

[S12] C：写文件
来源：http://dali.ydzc1.top/Article/details/gtndmzitpp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtqdzvthwf.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gtftbguxwj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gtgfsfpwff.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gttmhtkstd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daxiang520.top/Article/details/gtyjiedsqp.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtchrcxpdf.html

(double) a / b
来源：http://dali.zhongyouzk.top/Article/details/gtjptzatdg.html

[S16] C：位操作置位
来源：http://dali.pycfn.com/Article/details/gtyuyiqgvi.html

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gtjvrislhq.html

[S17] C：安全拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtrjlzqpmg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dashuyun.cn/Article/details/gttqkrtnev.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtgpibco.html

int main(int argc, char **argv)
来源：http://dali.yuxming.cn/Article/details/gtgqyvqztj.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gtcfhxxhfu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtwpopkpuw.html

[S20] C：二分查找
来源：http://dali.xuanzx.com/Article/details/gtgwfderal.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtfzthlxti.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gtjpirwmbt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.birdmap.top/Article/details/gtyfemzrbt.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gtztgnzenv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj202588.top/Article/details/gtwsgjmruw.html

[S23] C：随机数
来源：http://dali.snrcjt.cn/Article/details/gthglqthov.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gtafyhvfsf.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gthimtutgt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tian-w.cn/Article/details/gteekbvqdm.html

[S25] C：内存拷贝
来源：http://dali.snrcjt.cn/Article/details/gtwrhqlpew.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gtdqrgcznc.html

[S26] C：内存清零
来源：http://dali.sxryk.cn/Article/details/gtyrdxrbgj.html

memset(a, 0, sizeof a);
来源：http://dali.cdnleiting.top/Article/details/gtoedcfwcw.html

[S27] C：定义常量
来源：http://dali.jiagoushi.top/Article/details/gtbxkeigfw.html

const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtracthkpk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gtqkorulmn.html

static int counter = 0;
来源：http://dali.zycfv.cn/Article/details/gtnnctzqir.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gtqpmbtlvi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtolsserlb.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gtpwhixtte.html

#ifndef X_H
来源：http://dali.yongpay.top/Article/details/gtwtqhexjp.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gtocmypbjt.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gtacshhqax.html

[S31] C++：Hello World
来源：http://dali.nwbrower.top/Article/details/gtiljbwvld.html

#include <iostream>
来源：http://dali.gogol.net.cn/Article/details/gtgmkmawbc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gtlcikfzwo.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gtfyledoas.html

std::string s = "hi";  s += "!";
来源：http://dali.wangshuangyany.cn/Article/details/gthnmbjsph.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gtucertydv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gthzlkxgkm.html

[S34] C++：遍历 vector
来源：http://dali.meibo888.top/Article/details/gtktaocwfi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aizwys.cn/Article/details/gtuhiywlak.html

[S35] C++：map
来源：http://dali.jinghuilouyu.cn/Article/details/gthtqglvyz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gthwmxpywu.html

[S36] C++：unordered_map
来源：http://dali.chenzaomai.com/Article/details/gttkpwiszq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtbjgzhvbp.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gtbvueeotb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xziqi.cn/Article/details/gtoylmjwzf.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gtbizgzsyi.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gtbvbwcnyi.html


<!-- 参考信息 -->