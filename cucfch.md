代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2bpqntskl.html

[Q73] 查看表状态
来源：http://dali.kuanghao11.cn/Article/details/gt2hoeonphn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gt2axapkzyb.html

[Q74] 强制使用索引
来源：http://dali.jlsjyb.cn/Article/details/gt2xwtwjirg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.feifeiyinyue.top/Article/details/gt2aaazfbnk.html

[Q75] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gt2wjvjwuha.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2dtcjyqgl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zycfv.cn/Article/details/gt2jarjnkpo.html

[Q76] 按天统计
来源：http://dali.dianchejie.cn/Article/details/gt2ebugjnil.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zdqjudy.top/Article/details/gt2swgiichy.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gt2hljlaqoc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gt2esjsbash.html

[Q78] 当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lawlqgrj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gt2qiskuzer.html

[Q79] 字符串拼接
来源：http://dali.jianghu66.top/Article/details/gt2erjmhxgq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.redwolf501.top/Article/details/gt2kplfjesp.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbioinkm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2opoyagps.html

[Q81] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gt2oqvsszeb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2syfcpete.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gt2apcuzhpd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2zrjdbjqa.html

[Q83] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gt2vuvyokdr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2hkgmkdaa.html

[Q84] 去除首尾空格
来源：http://dali.chenzaomai.com/Article/details/gt2fkgnfdcd.html

SELECT TRIM(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2qqzgolft.html

[Q85] 数值取整
来源：http://dali.zhongyouzk.top/Article/details/gt2youwtbwu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xinyue.icu/Article/details/gt2njowxzxg.html

[Q86] 读取 JSON 字段
来源：http://dali.cashguo.top/Article/details/gt2ampibwqw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzqmdvep.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gt2vfiwfhdw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.havefunace.top/Article/details/gt2qgtrkiuh.html

[Q88] 行转列（条件聚合）
来源：http://dali.yvedp.cn/Article/details/gt2wjlawwol.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gt2zjonjdwg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2ufamimjf.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2dfzimlcu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hfpthk.cn/Article/details/gt2wzwiqkax.html

[Q90] 生成序号列
来源：http://dali.yonumen.top/Article/details/gt2kygrlant.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2awwqtcwm.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ucwjknyg.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vfsohqmv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2qewcjexd.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gt2fogkhipt.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gt2jtcwrkkt.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gt2lkmxzklm.html

[R02] 变量赋值与使用
来源：http://dali.quarkkingdee.top/Article/details/gt2xvjslcha.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gt2mkljwjzn.html

[R03] 只读变量
来源：http://dali.aibaodan.cn/Article/details/gt2oqgzolcv.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gt2lpwbxmus.html

[R04] 位置参数
来源：http://dali.cashguo.top/Article/details/gt2fotxmzje.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxinkj.top/Article/details/gt2rwsyzqjx.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gt2xgbktnch.html

name="${1:-default}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldohzzys.html

[R06] 判断命令是否存在
来源：http://dali.yj20258888.top/Article/details/gt2qklqxwtt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gt2svldknbg.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gt2tazrprwc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjivfsdi.html

[R08] 数值比较
来源：http://dali.yonumen.top/Article/details/gt2yphlxcdv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2xznqrrrl.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2hlcnetmg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2scdoxllp.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gt2vtzpweqr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2kmyyprja.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gt2daswxthf.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gt2sivegwvb.html

start) echo "启动" ;;
来源：http://dali.yj20258888.top/Article/details/gt2xheytmfj.html

stop)  echo "停止" ;;
来源：http://dali.nanxuanxn.top/Article/details/gt2sjzzyehl.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jussfldp.html

esac
来源：http://dali.jqgfzy.top/Article/details/gt2guucozgu.html

[R12] for 遍历文件
来源：http://dali.mhx1999.top/Article/details/gt2ooougvev.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ppiuupbx.html

[R13] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gt2eiwizxtn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gt2uujczocu.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gt2augznmhv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2zmylaepo.html

[R15] while 逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2ryfjktxb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2tyhsqrjs.html

[R16] until 等待条件
来源：http://dali.hnqzz.top/Article/details/gt2hnejwcwz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gt2jofoynfd.html

[R17] 数组定义与取值
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjezucis.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybydgwmm.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjyoayja.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2hzymjmba.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gt2xxqzlvrg.html

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gt2cedgiqfe.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gt2hddshszg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxuanxn.top/Article/details/gt2jclbyusk.html

[R21] 字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gt2uoeqonrc.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dndgbtqr.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gt2vyfwkhed.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2koogmfsw.html

[R23] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gt2uhudchox.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gt2jnsziock.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2nqszkwjt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gt2bmesvslq.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gt2khfjxmfk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2htvqtxed.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gt2nzckohxh.html

now=$(date +%F); echo "$now"
来源：http://dali.cqqwz.cn/Article/details/gt2jwfmwioe.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gt2clnrbbqy.html

echo $((1 + 2 * 3))
来源：http://dali.sxryk.cn/Article/details/gt2uierwblb.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gt2ggwltijq.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgailubk.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gt2mvngbzte.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gt2behvzneh.html

[R30] 函数返回状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvhvcjsk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gt2hvkhjxzr.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gt2swccmilr.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gt2aanrqwwa.html

[R32] 参数个数校验
来源：http://dali.yanxiufei.cn/Article/details/gt2dwcftqth.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gt2vcgzzccg.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gt2dxxhmcmh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.meibo888.top/Article/details/gt2zlxguvoi.html

[R34] 退出时清理
来源：http://dali.nanxinkj.top/Article/details/gt2kvsrtfhb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gt2bqpovexm.html

[R35] 后台执行并等待
来源：http://dali.zdqjudy.top/Article/details/gt2lhbsyeqp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sysykeji.top/Article/details/gt2mbegzxai.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gt2ghqwthnp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gt2rfxxkbpv.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gt2rrbwnwgp.html

files=$(ls -1)
来源：http://dali.hfpthk.cn/Article/details/gt2apkgodjx.html

[R38] 管道串联
来源：http://dali.jqgfzy.top/Article/details/gt2ljkbajoy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhengqikj.top/Article/details/gt2ygpqwkgq.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gt2nzgzsxgn.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gt2mvgzslxm.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gt2zrklbkob.html

echo "log" >> out.log
来源：http://dali.redwolf501.top/Article/details/gt2oewfyftt.html

[R41] 丢弃输出
来源：http://dali.quarkkingdee.top/Article/details/gt2ahevllyc.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gt2dtnrafst.html

[R42] 输入重定向
来源：http://dali.chenzaomai.com/Article/details/gt2wsslidlo.html

wc -l < a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2npakftcg.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gt2rptiftai.html

find . -name "*.log" -type f
来源：http://dali.zycfv.cn/Article/details/gt2pwngorzb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2urzguzod.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gt2fosyggwr.html

[R45] 批量删除
来源：http://dali.havefunace.top/Article/details/gt2vmjoigbe.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gt2fyvsjvyj.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gt2vkexnazi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gt2maifkury.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gt2irtibhdr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daria6918.cn/Article/details/gt2quubyubn.html

[R48] awk 取指定列
来源：http://dali.vqdsnc.cn/Article/details/gt2fuzhwyhz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxbisywb.html

[R49] awk 带条件
来源：http://dali.chenzaomai.com/Article/details/gt2wvprabxo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpjejcgy.html

[R50] awk 求和
来源：http://dali.jlsjyb.cn/Article/details/gt2intnldrf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2bidvniff.html

[R51] 排序去重取前几
来源：http://dali.chenzaomai.com/Article/details/gt2xjpsmdsi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aizwys.cn/Article/details/gt2pomnwbfp.html

[R52] 统计行数
来源：http://dali.fzhhl.top/Article/details/gt2xpaogvbb.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2ctsbkvet.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gt2uefgpgmi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xylfe.cn/Article/details/gt2pnfckqma.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gt2oqzekmyl.html

diff a.txt b.txt
来源：http://dali.fengsongda.top/Article/details/gt2ntrfdkew.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gt2ebnhtbch.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gt2zvvbwimo.html

[R56] 远程拷贝
来源：http://dali.sweek.top/Article/details/gt2stqogvah.html

scp file user@host:/path/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwwejlpa.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gt2vftmgqhf.html

ssh user@host 'uptime'
来源：http://dali.zhengqikj.top/Article/details/gt2kmqgpeym.html

[R58] 下载文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2rkecmgni.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gt2yeifxhbe.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2kngondpn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tanke756.top/Article/details/gt2zsdunxan.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gt2ssrdzfeu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gt2winonmjg.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gt2rjcfnvqa.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gt2qsgfydwm.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gt2ozgmyezd.html

du -ah . | sort -rh | head -10
来源：http://dali.sufxvd.cn/Article/details/gt2ahzqczsj.html

[R63] 内存与进程
来源：http://dali.gzhubu.top/Article/details/gt2seirrhgd.html

free -h;  ps aux | grep nginx
来源：http://dali.vqdsnc.cn/Article/details/gt2yqvxnhmj.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gt2gcnsdqkx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.vqdsnc.cn/Article/details/gt2pjzsjnyg.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gt2ymxaeccp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenzaomai.com/Article/details/gt2vbrtqbxv.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gt2nrmoggil.html

crontab -e;  crontab -l
来源：http://dali.hywenlv.cn/Article/details/gt2uchubsmm.html

[R67] 生成随机十六进制串
来源：http://dali.nanxinkj.top/Article/details/gt2wwpgchxy.html

openssl rand -hex 16
来源：http://dali.hysaishi.cn/Article/details/gt2cufgjkjw.html

[R68] 计算文件校验值
来源：http://dali.shuidangran.top/Article/details/gt2ltrgginl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2btryfrzh.html

[R69] 生成随机密码
来源：http://dali.yonumen.top/Article/details/gt2aavycthr.html

head -c 16 /dev/urandom | base64
来源：http://dali.tanke756.top/Article/details/gt2xaxuwbms.html

[R70] 时间戳与互转
来源：http://dali.bjfxy.top/Article/details/gt2egocukzh.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gt2nyqjowei.html

[R71] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2wyzzgoqu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aibaodan.cn/Article/details/gt2khevrdka.html

[R72] 等待端口就绪
来源：http://dali.zycfv.cn/Article/details/gt2djdsdkhi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gt2dlnogzqr.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gt2ldbupplb.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhjwfprj.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gt2wwjjgzry.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.c1oappe.top/Article/details/gt2dhtstvyl.html

[R75] 导出环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2lycdsjmk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gt2nzubfbkz.html

[R76] 使用临时文件
来源：http://dali.yuanzhike.top/Article/details/gt2skirwrsm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gt2zetoiuju.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gt2oevjcrka.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gt2fswnjsyd.html

[R78] 交互式菜单
来源：http://dali.ydzc1.top/Article/details/gt2wwfzqeun.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sijbnnas.html

[R79] 解析命令行选项
来源：http://dali.smart0.xyz/Article/details/gt2sxkigslz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jiagoushi.top/Article/details/gt2gboioabd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2joqbkwzy.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gt2doxbnuhg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2fnhtgzrr.html

S. C / C++ 专题
来源：http://dali.hysaishi.cn/Article/details/gt2vgdcaumc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2wsehnseo.html

[S01] C：Hello World
来源：http://dali.havefunace.top/Article/details/gt2cekweyho.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gt2fxmejwyw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ydzc1.top/Article/details/gt2khtfdixo.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rukwjeek.html

int a = 10; printf("%d\n", a);
来源：http://dali.fengsongda.top/Article/details/gt2vebmekhn.html

[S03] C：读入整数
来源：http://dali.birdmap.top/Article/details/gt2lvksqfkd.html

int x; scanf("%d", &x);
来源：http://dali.iojbl.cn/Article/details/gt2iutuucsi.html

[S04] C：字符串复制
来源：http://dali.sweek.top/Article/details/gt2rnvycmhz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gt2blvioghp.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2qpnuaaen.html

strlen(s)
来源：http://dali.andypj.xyz/Article/details/gt2kumykqfw.html

[S06] C：字符串比较
来源：http://dali.hnqzz.top/Article/details/gt2otlvybpo.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gt2otortutn.html

[S07] C：数组遍历求和
来源：http://dali.svipenyu.cn/Article/details/gt2vgeuyxuv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gt2uildwqax.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gt2wlrjhivg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gt2zzmduojv.html

[S09] C：结构体定义与初始化
来源：http://dali.gotoacloud.top/Article/details/gt2xhtgdwdj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gt2fomehmub.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gt2eyriaatj.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gt2peddfset.html

[S11] C：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2bjnkkeka.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gt2zzzpkmgx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gt2qfkfhrpu.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gt2oyygjtes.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gt2vooggryl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gt2xayjoxvz.html

[S13] C：宏定义
来源：http://dali.gogol.net.cn/Article/details/gt2ygzopsga.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gt2vibahlmr.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2rkicqjey.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fengsongda.top/Article/details/gt2myrhnyjl.html

[S15] C：类型转换
来源：http://dali.vqdsnc.cn/Article/details/gt2gcblmzmc.html

(double) a / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqrlulnj.html

[S16] C：位操作置位
来源：http://dali.sxryk.cn/Article/details/gt2etgcbskr.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2plvqmbpv.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gt2fqicqkbp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fzhhl.top/Article/details/gt2edmfitwi.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2qkccwady.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gt2oilkcdpz.html

[S19] C：快速排序
来源：http://dali.yanxiufei.cn/Article/details/gt2kqpmypag.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gt2rdnjgsth.html

[S20] C：二分查找
来源：http://dali.zdqjudy.top/Article/details/gt2rnodycek.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gt2eidqmbss.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gt2bohtjvwd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sufxvd.cn/Article/details/gt2eferhybc.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gt2sysbacaq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gt2lhsdebon.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gt2lwnyoute.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuetiantiany.cn/Article/details/gt2zcxnlkxa.html

[S24] C：获取本地时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eotkwqyq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.mhx1999.top/Article/details/gt2lpfgrjjg.html

[S25] C：内存拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gt2chotyozu.html

memcpy(dst, src, n);
来源：http://dali.daria6918.cn/Article/details/gt2qxizprtb.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gt2pmlrgayc.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gt2dmbpqgvq.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gt2shsnmjds.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2lrxwednp.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gt2hgqonyaq.html

static int counter = 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxejijjb.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npubakoa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aibaodan.cn/Article/details/gt2hhsglaxj.html

[S30] C：头文件保护
来源：http://dali.svipenyu.cn/Article/details/gt2kdinnrtq.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gt2ibryirpm.html

#define X_H
来源：http://dali.daxiang520.top/Article/details/gt2ogwsvsol.html

#endif
来源：http://dali.chenjidiqi.icu/Article/details/gt2czwjmddh.html

[S31] C++：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2wkhlamon.html

#include <iostream>
来源：http://dali.fengsongda.top/Article/details/gt2jbhnusgl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tian-w.cn/Article/details/gt2mmtytmdz.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iarwyqxl.html

std::string s = "hi";  s += "!";
来源：http://dali.cdnleiting.top/Article/details/gt2lumeyapf.html

[S33] C++：vector 增删
来源：http://dali.shangyingyoupin.top/Article/details/gt2aeslajdy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gt2ujkgvamx.html

[S34] C++：遍历 vector
来源：http://dali.tianlin.xyz/Article/details/gt2fqygnlxb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhixingplan.top/Article/details/gt2mlmiiync.html

[S35] C++：map
来源：http://dali.zycfv.cn/Article/details/gt2snyklzzf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfdnrivu.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gt2zutduujn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2yycweqyx.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gt2lziixtri.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2olceaoug.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gt2ouxffytt.html

std::sort(v.begin(), v.end());
来源：http://dali.hnqzz.top/Article/details/gt2wpskdeba.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izcadapd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yongpay.top/Article/details/gt2zwuuaeoy.html

[S40] C++：查找元素
来源：http://dali.svipenyu.cn/Article/details/gt2kmdsdmvc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fzyeuqaq.html

[S41] C++：类与构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2fnmabydb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aibaodan.cn/Article/details/gt2zhfcslbp.html

[S42] C++：继承与虚函数
来源：http://dali.cqqwz.cn/Article/details/gt2kvzcpbrz.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gt2eiduotwh.html


<!-- 参考信息 -->