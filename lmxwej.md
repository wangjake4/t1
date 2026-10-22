代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.jinqigufen.top/Article/details/gtoowzryic.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gtbdedcvnf.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gtssrtcgns.html

SAVEPOINT sp1;
来源：http://dali.daria6918.cn/Article/details/gtrvnehtap.html

ROLLBACK TO sp1;
来源：http://dali.yueranfly.top/Article/details/gtrufccetq.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gthrumvkpi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrokhuooh.html

[Q70] 更新统计信息
来源：http://dali.xylfe.cn/Article/details/gtopiaaknr.html

ANALYZE TABLE users;
来源：http://dali.bjfxy.top/Article/details/gtofpjajjl.html

[Q71] 查看建表语句
来源：http://dali.sysykeji.top/Article/details/gtbvkwwrqt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.birdmap.top/Article/details/gtbkwiyblc.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gtxzdmpmxi.html

SHOW INDEX FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtxfazkgbv.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gtkudqrafy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gtxhqcmjwl.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gtsljiepvw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shangyingyoupin.top/Article/details/gtjxaqrxru.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtdnbawbsz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtmasgecfm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gtvtktejud.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gtjeyupatd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.316326.xyz/Article/details/gtbcgfulux.html

[Q77] 时间加减
来源：http://dali.zhiwuduotai.top/Article/details/gtelvcumqr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zycfv.cn/Article/details/gthxpczaor.html

[Q78] 当前时间
来源：http://dali.ehwqpu.com/Article/details/gtzljhjxkm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gtzrnzlsdp.html

[Q79] 字符串拼接
来源：http://dali.xinyue.icu/Article/details/gtwuhnzzpp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gtoueyeupq.html

[Q80] 字符串截取
来源：http://dali.fengsongda.top/Article/details/gtzfvxinan.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gttantiieh.html

[Q81] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtmkjftvhu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.havefunace.top/Article/details/gtgvwdupii.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258888.top/Article/details/gtpisilbyf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtqtfdvzzi.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtetlqipoe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtphztlxib.html

[Q84] 去除首尾空格
来源：http://dali.jqgfzy.top/Article/details/gtwruzyolu.html

SELECT TRIM(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtzeefdkuo.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtmlfyzsyk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shzxlz.cn/Article/details/gtwnhuwiiy.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gtoniqrhwu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwyxsebv.html

[Q87] JSON 字段做条件
来源：http://dali.sxryk.cn/Article/details/gtkuoijmmr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gtmnkdcezn.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenjidiqi.icu/Article/details/gtgkathwtu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhiwuduotai.top/Article/details/gtzrakwahd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtpuwjyxvz.html

[Q89] 判断表是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtscfakpun.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gtqtlyjaqu.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gtqhxjpjtt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gtdmdavkgz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtzgcjqvkm.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gtekovfmvp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtycekqhxj.html

[R01] shebang 与严格模式
来源：http://dali.hfpthk.cn/Article/details/gtcnovriae.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gtnncajfda.html

set -euo pipefail
来源：http://dali.hfpthk.cn/Article/details/gtzjqgkwvj.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gtrjesfyta.html

name="Tom"; echo "$name"
来源：http://dali.quarkkingdee.top/Article/details/gtnbrmupwp.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gtprikszye.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gtkecnsbbe.html

[R04] 位置参数
来源：http://dali.yj202588.top/Article/details/gtfqtuxozl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hywenlv.cn/Article/details/gtlcyhxkrh.html

[R05] 参数默认值
来源：http://dali.jqgufenzy.top/Article/details/gtcozmgzul.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gtbjcvjdfb.html

[R06] 判断命令是否存在
来源：http://dali.xziqi.cn/Article/details/gtxrnoarwm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtuixvqwze.html

[R07] if 判断文件
来源：http://dali.aibaodan.cn/Article/details/gtebwpfnks.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gtzjftrave.html

[R08] 数值比较
来源：http://dali.yongpay.top/Article/details/gthwsqhstd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtpphmsrde.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gthnskcezv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gtugwvbztf.html

[R10] 正则匹配
来源：http://dali.zhongyouzk.top/Article/details/gthpbgmbov.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfclpudzz.html

[R11] case 多分支
来源：http://dali.zdqjudy.top/Article/details/gtjrdakjum.html

case "$1" in
来源：http://dali.haohaochexian.top/Article/details/gtvlsjarta.html

start) echo "启动" ;;
来源：http://dali.sufxvd.cn/Article/details/gtewzhkvqv.html

stop)  echo "停止" ;;
来源：http://dali.guowangkeji.top/Article/details/gtpaohdxif.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gttnlckban.html

esac
来源：http://dali.birdmap.top/Article/details/gtvsnwaozt.html

[R12] for 遍历文件
来源：http://dali.wangshuangyany.cn/Article/details/gtxuwkanft.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtqsthdehl.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gttmskggry.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtmaocfsby.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gtqhqhmxhr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtizhaooxf.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtyofojjsl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtcxnsfjsc.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gtlihdvphl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtmiogvzvq.html

[R17] 数组定义与取值
来源：http://dali.kuanghao11.cn/Article/details/gticbelppl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258888.top/Article/details/gtwtfqfhly.html

[R18] 遍历数组
来源：http://dali.cqqwz.cn/Article/details/gtxcaebgev.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dashuyun.cn/Article/details/gtregjzazt.html

[R19] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gthhsvfumg.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gtqbiqlljq.html

[R20] 关联数组（字典）
来源：http://dali.hongshengwenyu.top/Article/details/gthhlrtnjg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.meibo888.top/Article/details/gttnpwtsxx.html

[R21] 字符串长度
来源：http://dali.xziqi.cn/Article/details/gtqbywrlyb.html

echo "${#s}"
来源：http://dali.xuetiantiany.cn/Article/details/gtyhzczpqa.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtganjhbyz.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gtcgppmmwn.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtmysdwpft.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigufen.top/Article/details/gtcbwsapoq.html

[R24] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtebtesudu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gtdkitswai.html

[R25] 去后缀 / 去前缀
来源：http://dali.hammf.cn/Article/details/gtnfloejeq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.mhx1999.top/Article/details/gtlqmdpqln.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gtvxfyjhgw.html

now=$(date +%F); echo "$now"
来源：http://dali.cashguo.top/Article/details/gtbhudcbgy.html

[R27] 算术展开
来源：http://dali.meibo888.top/Article/details/gtdanwbrlv.html

echo $((1 + 2 * 3))
来源：http://dali.pycfn.com/Article/details/gtaheginjl.html

[R28] 浮点运算
来源：http://dali.xuanzx.com/Article/details/gttjrgsafp.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gtmiwiuqpg.html

[R29] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gtpdznypnf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hongshengwenyu.top/Article/details/gttcaertjy.html

[R30] 函数返回状态码
来源：http://dali.kuanghao11.cn/Article/details/gtapglnlrw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gtqhvkuwnp.html

[R31] 局部变量
来源：http://dali.hysaishi.cn/Article/details/gtmalmrnes.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gtvhdfdesy.html

[R32] 参数个数校验
来源：http://dali.zhixingplan.top/Article/details/gtgdmyyffo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtutklicyr.html

[R33] 捕获错误并提示行号
来源：http://dali.shuidangran.top/Article/details/gtpsvyozpj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gtwctwhzls.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gtleguuhsm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtjjlfpucz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtlbhcbnxh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hysaishi.cn/Article/details/gtrxkwuryq.html

[R36] 并发执行多个任务
来源：http://dali.shuidangran.top/Article/details/gtoammcbdf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zycfv.cn/Article/details/gtspdubooj.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gthgbhivio.html

files=$(ls -1)
来源：http://dali.nanxinkj.top/Article/details/gtcacrjobh.html

[R38] 管道串联
来源：http://dali.jlsjyb.cn/Article/details/gtodjmegqj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangtech.top/Article/details/gturdlnyog.html

[R39] 重定向标准输出与错误
来源：http://dali.yangfankeji.com/Article/details/gtxbspdezi.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gtneantxba.html

[R40] 追加写日志
来源：http://dali.yj20258888.top/Article/details/gtocgfqdde.html

echo "log" >> out.log
来源：http://dali.yangfankeji.com/Article/details/gtlkgyjaqq.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gtzacfvdqx.html

cmd >/dev/null 2>&1
来源：http://dali.havefunace.top/Article/details/gtxbksdluu.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gtinjlnwvu.html

wc -l < a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtbkqfdzuc.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtvbhigqlx.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gtzpnxplsw.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gtzuccddwz.html

find . -mtime -7 -type f
来源：http://dali.yj20258.top/Article/details/gtciikudlg.html

[R45] 批量删除
来源：http://dali.tanke756.top/Article/details/gtpizdqiqy.html

find . -name "*.tmp" -delete
来源：http://dali.pengpengdd.cyou/Article/details/gtyvazuvtj.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gthebtwpyp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dashuyun.cn/Article/details/gtwlgfzjka.html

[R47] sed 单行替换
来源：http://dali.jyoumei.cn/Article/details/gtoiflmqfz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtlthuzkqz.html

[R48] awk 取指定列
来源：http://dali.daxiang520.top/Article/details/gtukohjaon.html

awk '{print $1, $3}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtjjfgflch.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gtlktjeosw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gtmbjqhdjm.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gthavpjphc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtlvdkcdxr.html

[R51] 排序去重取前几
来源：http://dali.sweek.top/Article/details/gtletsnttd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tianlin.xyz/Article/details/gtrzisrhsd.html

[R52] 统计行数
来源：http://dali.hammf.cn/Article/details/gtfsfucced.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gtcadynnet.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gtjbpdwhoo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhiwuduotai.top/Article/details/gtvnuhjnfz.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gtyupwduyt.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gtoapqrfdl.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gtohupzxse.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gtdgqecbyy.html

[R56] 远程拷贝
来源：http://dali.guannengcc.top/Article/details/gttyklpwdx.html

scp file user@host:/path/
来源：http://dali.pengpengdd.cyou/Article/details/gtzshgipqj.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gtxbnrhwkt.html

ssh user@host 'uptime'
来源：http://dali.kuanghao11.cn/Article/details/gtvjnjmrrx.html

[R58] 下载文件
来源：http://dali.zhiwuduotai.top/Article/details/gtdangzgyr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ppjwa.cn/Article/details/gtaotsefsb.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtswxzdujz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shangyingyoupin.top/Article/details/gtrqyfhhtx.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtexdkzmuq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gttgoorjkm.html

[R61] 磁盘占用
来源：http://dali.gogol.net.cn/Article/details/gtwnyrdmfs.html

df -h;  du -sh *
来源：http://dali.daria6918.cn/Article/details/gtpgexftcr.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gtgokdfbgq.html

du -ah . | sort -rh | head -10
来源：http://dali.fzhhl.top/Article/details/gtjahagnoz.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gtbmheoouw.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gthsdflgdd.html

[R64] 结束进程
来源：http://dali.zdqjudy.top/Article/details/gtxmqnfkja.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenjidiqi.icu/Article/details/gtznismrie.html

[R65] 查看端口占用
来源：http://dali.havefunace.top/Article/details/gtodoanoga.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.vqdsnc.cn/Article/details/gtdxbvhlhn.html

[R66] 定时任务
来源：http://dali.andypj.xyz/Article/details/gtwuqxsbgz.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtiuvbxmja.html

[R67] 生成随机十六进制串
来源：http://dali.xuetiantiany.cn/Article/details/gtonratnrf.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gtewfilxff.html

[R68] 计算文件校验值
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwqolrlo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fzhhl.top/Article/details/gtobrxbior.html

[R69] 生成随机密码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacwgfqtd.html

head -c 16 /dev/urandom | base64
来源：http://dali.kuanghao11.cn/Article/details/gtspazyqwm.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtimxolagh.html

date +%s;  date -d @1700000000
来源：http://dali.tanke756.top/Article/details/gtvisifkzd.html

[R71] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtapslbhgi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gtvjowspyh.html

[R72] 等待端口就绪
来源：http://dali.jiagoushi.top/Article/details/gtauvhjmcc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtxczowhny.html

[R73] 分割大日志
来源：http://dali.dashuyun.cn/Article/details/gtxwzmhfea.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwsycplf.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gtsvdqmubq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gtaofebfvr.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gtzfdbtjbk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjvxfeob.html

[R76] 使用临时文件
来源：http://dali.gzhubu.top/Article/details/gtfmmbsdgf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtuzcpzpoo.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gtgwmrfcea.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gtredrfnur.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gtyaowirwn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gtftaclsgn.html

[R79] 解析命令行选项
来源：http://dali.iojbl.cn/Article/details/gthhkixdmt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gtompwrpzc.html

[R80] 查看脚本执行耗时
来源：http://dali.snrcjt.cn/Article/details/gtnnordnra.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtbhrguijj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzccpedmi.html

S. C / C++ 专题
来源：http://dali.yj20258.top/Article/details/gtkeizqazj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtrxqjnpne.html

[S01] C：Hello World
来源：http://dali.smart0.xyz/Article/details/gthnrynjgn.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gtyoqkixia.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yanxiufei.cn/Article/details/gtfmbxvmbv.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtlhjpxhza.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gtsfkkwscx.html

[S03] C：读入整数
来源：http://dali.wangdashe.top/Article/details/gtgeadesft.html

int x; scanf("%d", &x);
来源：http://dali.tanke756.top/Article/details/gtbcnlsnvq.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtwpeakkau.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gticnowrmd.html

[S05] C：字符串长度
来源：http://dali.zycfv.cn/Article/details/gtrvzotaxr.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuulsrcvc.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gtbtaiipbb.html

strcmp(a, b) == 0
来源：http://dali.9152youxi.cn/Article/details/gtcwwareuh.html

[S07] C：数组遍历求和
来源：http://dali.jlsjyb.cn/Article/details/gtdgwivxkk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.havefunace.top/Article/details/gthxhpajlh.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gtdandgqqo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gtsbhrxewr.html

[S09] C：结构体定义与初始化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmofsvomd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj202588.top/Article/details/gtitbzjrln.html

[S10] C：指针与解引用
来源：http://dali.guowangkeji.top/Article/details/gtbxqyqfqk.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gtwhfcjruw.html

[S11] C：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtjryxmjma.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jyoumei.cn/Article/details/gtdvcawqun.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gthzjlnucw.html

fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtlvbqbkwx.html

[S12] C：写文件
来源：http://dali.pycfn.com/Article/details/gtjptklpwy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gtpfrdjqdy.html

[S13] C：宏定义
来源：http://dali.dianchejie.cn/Article/details/gtvxtpgymb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadqckrup.html

[S14] C：枚举
来源：http://dali.cqqwz.cn/Article/details/gtvodkqnfb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.9152youxi.cn/Article/details/gtphkbkrnk.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtcsvsbgrl.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gtizsrddlz.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gtybmamrrd.html

x |= (1 << 3);
来源：http://dali.snrcjt.cn/Article/details/gtxtuqnohf.html

[S17] C：安全拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gtaxmwcciz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttowlzbcc.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgwjobhw.html

int main(int argc, char **argv)
来源：http://dali.zdqjudy.top/Article/details/gtsoblxjja.html

[S19] C：快速排序
来源：http://dali.sxryk.cn/Article/details/gtlbblrdbr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gtztianbsm.html

[S20] C：二分查找
来源：http://dali.ybcxt.top/Article/details/gtcofpntkh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtqqhqoruv.html

[S21] C：字符类别判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvbfrvvj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gaohongyu789.top/Article/details/gtwadsfymj.html

[S22] C：字符串转数字
来源：http://dali.havefunace.top/Article/details/gtehbzflxj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gtvhazxssu.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gtwpafuljw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtsnwgdowi.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gtaqfnzjmb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gtiogckcxu.html

[S25] C：内存拷贝
来源：http://dali.jinqigfzy.top/Article/details/gttuzgirxu.html

memcpy(dst, src, n);
来源：http://dali.chenjidiqi.icu/Article/details/gtvwjqxexy.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gtxnkcibot.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvvsmret.html

[S27] C：定义常量
来源：http://dali.wangdashe.top/Article/details/gtlpcxssga.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtcmiufhfk.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gtiujjkavb.html

static int counter = 0;
来源：http://dali.andypj.xyz/Article/details/gthnjmcwkr.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gtwmbnaouk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gtdkthseyc.html

[S30] C：头文件保护
来源：http://dali.nanxuanxn.top/Article/details/gtaanrwzsr.html

#ifndef X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtqlzsytgx.html

#define X_H
来源：http://dali.kuanghao11.cn/Article/details/gttgqjvadt.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gtcdzustds.html

[S31] C++：Hello World
来源：http://dali.fzhhl.top/Article/details/gtohpyubea.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gthzngmnhu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gtjnwnwtof.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gtswriuoqw.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gtslxujrmx.html

[S33] C++：vector 增删
来源：http://dali.sysykeji.top/Article/details/gthifhvryr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxinkj.top/Article/details/gtewbtqkcu.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gttwtlxepu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gtxuducusj.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gtvxttboro.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtfnijwtde.html

[S36] C++：unordered_map
来源：http://dali.chenzaomai.com/Article/details/gttvfbfgvy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtjcpccxys.html


<!-- 参考信息 -->