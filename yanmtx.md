代发 wailian999

[Q65] 回滚事务
来源：http://dali.guowangkeji.top/Article/details/gtowzlpxqk.html

ROLLBACK;
来源：http://dali.hfpthk.cn/Article/details/gtyrlhcgln.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gtvvfpjptt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gtgcnvakid.html

[Q67] 设置隔离级别
来源：http://dali.yj202588.top/Article/details/gtvnuaenwi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gttlsaabdd.html

[Q68] 保存点
来源：http://dali.ydzc1.top/Article/details/gtmmbqqkpj.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gtfjvqbrqd.html

ROLLBACK TO sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gthojunium.html

[Q69] 查看执行计划
来源：http://dali.ydzc1.top/Article/details/gtupcfusox.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhiwuduotai.top/Article/details/gtqzjperbf.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gtslafevuv.html

ANALYZE TABLE users;
来源：http://dali.chenzaomai.com/Article/details/gtkbacwwvd.html

[Q71] 查看建表语句
来源：http://dali.feifeiyinyue.top/Article/details/gtyrctxwba.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcikrioy.html

[Q72] 查看索引
来源：http://dali.nwbrower.top/Article/details/gtcqpthvsh.html

SHOW INDEX FROM users;
来源：http://dali.yj20258.top/Article/details/gtxsykuelb.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gtxizmocia.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtvhudcvrv.html

[Q74] 强制使用索引
来源：http://dali.nanxinkj.top/Article/details/gtdfkhfxit.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gtwrauloxn.html

[Q75] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtygijfmwp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gthimtpgwq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gtixdzucax.html

[Q76] 按天统计
来源：http://dali.chenzaomai.com/Article/details/gtxyocaong.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthizqqcad.html

[Q77] 时间加减
来源：http://dali.wangdashe.top/Article/details/gtsspcehhi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuetiantiany.cn/Article/details/gtdwilzqzn.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gtvyhwejos.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gotoacloud.top/Article/details/gtftjyszyo.html

[Q79] 字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gtvbhwsdtm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gttnosskfy.html

[Q80] 字符串截取
来源：http://dali.yanxiufei.cn/Article/details/gtxekkdmoh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtsptaaked.html

[Q81] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtpshqnugv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gtprsvyoia.html

[Q82] 字符长度与字节长度
来源：http://dali.havefunace.top/Article/details/gtfiygvjfs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtcptdovmf.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gthmghhwey.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthylyvacj.html

[Q84] 去除首尾空格
来源：http://dali.quarkkingdee.top/Article/details/gtagnwgudj.html

SELECT TRIM(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtfnsqxirs.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gtbtjgklzi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jiagoushi.top/Article/details/gtsbhdeefn.html

[Q86] 读取 JSON 字段
来源：http://dali.jianghu66.top/Article/details/gtypsniljk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shzxlz.cn/Article/details/gtlzzqulxy.html

[Q87] JSON 字段做条件
来源：http://dali.tanke756.top/Article/details/gtoxpuhzqs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuanzx.com/Article/details/gtjbdmvvhn.html

[Q88] 行转列（条件聚合）
来源：http://dali.cashguo.top/Article/details/gtwmraflkm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjnscvsn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtdpkwjqxj.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gttaoalzjd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gtyxyndasf.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofzlgjue.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yanxiufei.cn/Article/details/gtbsgggodl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtsxpopnol.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtjkujrjgo.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqxjttgsm.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gtdbprwaqy.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gtyohjezjz.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gtztkgvxug.html

[R02] 变量赋值与使用
来源：http://dali.jlsjyb.cn/Article/details/gtdmijyqmt.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsracvrr.html

[R03] 只读变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwjjijkp.html

readonly PI=3.14
来源：http://dali.9152youxi.cn/Article/details/gtyfyfkjnf.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gtftksfpgi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yanxiufei.cn/Article/details/gtpujoddlo.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gtoxddybmk.html

name="${1:-default}"
来源：http://dali.guannengcc.top/Article/details/gtradltxfv.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gtjabdxxah.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtfxliliin.html

[R07] if 判断文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxhbsnoy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gtveptoube.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gtwiwmpzck.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.redwolf501.top/Article/details/gtbmmvkzfn.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtznjvdruk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuxming.cn/Article/details/gtfjixaezd.html

[R10] 正则匹配
来源：http://dali.zhixingplan.top/Article/details/gtasayretb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhengqikj.top/Article/details/gtfvxxcqru.html

[R11] case 多分支
来源：http://dali.xylfe.cn/Article/details/gtacjchnjg.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflnfvpag.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gtkvabwivh.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtyozozkgt.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gtuollmoez.html

esac
来源：http://dali.ydzc1.top/Article/details/gtrxhcfstj.html

[R12] for 遍历文件
来源：http://dali.cheryme.top/Article/details/gtltsduzdd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aizwys.cn/Article/details/gtbtuyidvr.html

[R13] for 计数循环
来源：http://dali.wangdashe.top/Article/details/gtddqbdest.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtybiiegvc.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gtttbmfunz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gthaobobtt.html

[R15] while 逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtbafnfsdu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.redwolf501.top/Article/details/gtvmmcurhy.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtozfaccly.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtvaenmqdi.html

[R17] 数组定义与取值
来源：http://dali.xinyue.icu/Article/details/gtvfuvxmbf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yonumen.top/Article/details/gtfanyrrjp.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gtamchfikb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.kuanghao11.cn/Article/details/gtwrztgywc.html

[R19] 数组长度
来源：http://dali.tanke756.top/Article/details/gtplzmsoey.html

echo "${#arr[@]}"
来源：http://dali.mhx1999.top/Article/details/gtktpbiwpv.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gtnpmfrcnn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gtdumwnjdo.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gtlduzufof.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gtpjjrvzjp.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gtjrdsjfmv.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gthvwoeqpw.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtsoimjeqc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gtxrtoskfm.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtzzclmgwn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ppjwa.cn/Article/details/gtakkyloph.html

[R25] 去后缀 / 去前缀
来源：http://dali.ybcxt.top/Article/details/gtdbvrrfqq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yueranfly.top/Article/details/gtgjkzgrnk.html

[R26] 命令替换
来源：http://dali.svipenyu.cn/Article/details/gtfucpvudd.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258888.top/Article/details/gtnvpinmwx.html

[R27] 算术展开
来源：http://dali.daria6918.cn/Article/details/gtbitldbrq.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigufen.top/Article/details/gtdnvfyhub.html

[R28] 浮点运算
来源：http://dali.redwolf501.top/Article/details/gtdfbvncjg.html

echo "scale=2; 10/3" | bc
来源：http://dali.shzxlz.cn/Article/details/gtopyjmpcy.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtdfrcuenw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gtkhpdvjmb.html

[R30] 函数返回状态码
来源：http://dali.yj202588.top/Article/details/gtubsfkgif.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnqzz.top/Article/details/gtabcbwsad.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gtbbczhqas.html

f() { local x=1; echo "$x"; }
来源：http://dali.cheryme.top/Article/details/gtsnwlotfx.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gtqqzpohpo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gteixkmuls.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gtsgniqaiq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hfpthk.cn/Article/details/gtquazbwug.html

[R34] 退出时清理
来源：http://dali.guannengcc.top/Article/details/gtfxeowenn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gtwyhnijcf.html

[R35] 后台执行并等待
来源：http://dali.gzhubu.top/Article/details/gtmbzlolcl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gtlbjqnocy.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gtaeaczllk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtybevpycf.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gthqolixpl.html

files=$(ls -1)
来源：http://dali.hammf.cn/Article/details/gtldtpkdrm.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gtidrrwlug.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenjidiqi.icu/Article/details/gtolltkykg.html

[R39] 重定向标准输出与错误
来源：http://dali.cucudq.cn/Article/details/gtmosvatxw.html

cmd > out.log 2>&1
来源：http://dali.smart0.xyz/Article/details/gtquvefsmr.html

[R40] 追加写日志
来源：http://dali.smart0.xyz/Article/details/gtkycycyat.html

echo "log" >> out.log
来源：http://dali.iojbl.cn/Article/details/gtfohhgstd.html

[R41] 丢弃输出
来源：http://dali.sweek.top/Article/details/gtszdypoyl.html

cmd >/dev/null 2>&1
来源：http://dali.zhengqikj.top/Article/details/gtcuuxukgh.html

[R42] 输入重定向
来源：http://dali.gzhubu.top/Article/details/gtfhlpzpnx.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gtsmkznpnc.html

[R43] 按名字查找文件
来源：http://dali.dashuyun.cn/Article/details/gtahkndkqo.html

find . -name "*.log" -type f
来源：http://dali.iojbl.cn/Article/details/gtsjynfpzs.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gtyytjtmqi.html

find . -mtime -7 -type f
来源：http://dali.zdqjudy.top/Article/details/gtdvpoxcgk.html

[R45] 批量删除
来源：http://dali.316326.xyz/Article/details/gtraizzmdq.html

find . -name "*.tmp" -delete
来源：http://dali.jianghu66.top/Article/details/gtxygbcjbv.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gtpkiaphif.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gtpefabocr.html

[R47] sed 单行替换
来源：http://dali.yanxiufei.cn/Article/details/gtkutlinlw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnqzz.top/Article/details/gtfwwtcrbq.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gtkovgkpnb.html

awk '{print $1, $3}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsnxrnqq.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gtfsmbwdqt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gtyiwivdre.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gtxobrbjvg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtfnafljes.html

[R51] 排序去重取前几
来源：http://dali.yongpay.top/Article/details/gtilcxrvdu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sweek.top/Article/details/gtgcwlyyhq.html

[R52] 统计行数
来源：http://dali.svipenyu.cn/Article/details/gtfgtutuvb.html

wc -l a.txt
来源：http://dali.redwolf501.top/Article/details/gttpmxfiza.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gtlaptodog.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gtwrhmtvav.html

[R54] 比较两个文件
来源：http://dali.daxiang520.top/Article/details/gtlstghnhy.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqolkyojq.html

[R55] 压缩与解压
来源：http://dali.haohaochexian.top/Article/details/gtyfnphvvr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gogol.net.cn/Article/details/gtggzfncdq.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gtdaouitos.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gtvmyyftmc.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gtysqfngzj.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gtcvqksjsk.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gtlyvxaeue.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tanke756.top/Article/details/gtctduvymp.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gthxacyijh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.quarkkingdee.top/Article/details/gtneqjxtmd.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtmsafbnel.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.svipenyu.cn/Article/details/gtenruhqul.html

[R61] 磁盘占用
来源：http://dali.smart0.xyz/Article/details/gtrlzutnrw.html

df -h;  du -sh *
来源：http://dali.fzhhl.top/Article/details/gtglyzwpca.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gtxvelqute.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gtcpxbsfaj.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gtphwhptpv.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gtifmjlbuj.html

[R64] 结束进程
来源：http://dali.jlsjyb.cn/Article/details/gtvvywqofw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gtixbkzfvd.html

[R65] 查看端口占用
来源：http://dali.cdnleiting.top/Article/details/gtpndvcffv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hysaishi.cn/Article/details/gtfmlvwjwa.html

[R66] 定时任务
来源：http://dali.yongpay.top/Article/details/gtxbhbzvna.html

crontab -e;  crontab -l
来源：http://dali.xinyue.icu/Article/details/gtkfhyrblc.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gtudfipncr.html

openssl rand -hex 16
来源：http://dali.yuanzhike.top/Article/details/gtohjgbmug.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjdvnzgq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.snrcjt.cn/Article/details/gtvigktojn.html

[R69] 生成随机密码
来源：http://dali.ehwqpu.com/Article/details/gtrydnxxte.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gtgsijgere.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gtgqtbhrnm.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gttwsebbnp.html

[R71] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gtmxfqcasr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gtoncuxdqx.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gtwhopqxfk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtvjvfnyiu.html

[R73] 分割大日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzddhexnk.html

split -l 1000 big.log part_
来源：http://dali.vqdsnc.cn/Article/details/gtvttefcmr.html

[R74] 批量重命名
来源：http://dali.ivvv.top/Article/details/gturufdvgh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gtpwncrzvz.html

[R75] 导出环境变量
来源：http://dali.yonumen.top/Article/details/gtkwvmjwgj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gtzondahmo.html

[R76] 使用临时文件
来源：http://dali.havefunace.top/Article/details/gtuoqyujyw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtneofctmo.html

[R77] 读取用户输入
来源：http://dali.iojbl.cn/Article/details/gtthulifqp.html

read -rp "请输入: " ans
来源：http://dali.fengsongda.top/Article/details/gththhpbrp.html

[R78] 交互式菜单
来源：http://dali.haohaochexian.top/Article/details/gtxufikpig.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gtbanpkblx.html

[R79] 解析命令行选项
来源：http://dali.jianghu66.top/Article/details/gtrfugnxud.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gtznvovcop.html

[R80] 查看脚本执行耗时
来源：http://dali.shzxlz.cn/Article/details/gtsvjxahow.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gtxyavtmbr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtrxdxmbyz.html

S. C / C++ 专题
来源：http://dali.0kj1m.cn/Article/details/gtcbgyridh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmkaduics.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtahhqhlts.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gtbhbxdjxb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqjgzynb.html

[S02] C：变量与格式化输出
来源：http://dali.yvedp.cn/Article/details/gtndkbguvz.html

int a = 10; printf("%d\n", a);
来源：http://dali.sufxvd.cn/Article/details/gtajolzwmm.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gtfayejjoq.html

int x; scanf("%d", &x);
来源：http://dali.hnqzz.top/Article/details/gtyaguosgr.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtdswcgtat.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtknhwayqd.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtnubotfea.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtjweyuhig.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gtqetmysdd.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gtwunjkdaf.html

[S07] C：数组遍历求和
来源：http://dali.gogol.net.cn/Article/details/gtlvesmaat.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.birdmap.top/Article/details/gtejwjhkgu.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gtzarnwuti.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.316326.xyz/Article/details/gtbmpvpmhx.html

[S09] C：结构体定义与初始化
来源：http://dali.tian-w.cn/Article/details/gtkzfthney.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shangyingyoupin.top/Article/details/gtdntdhqgj.html

[S10] C：指针与解引用
来源：http://dali.dianchejie.cn/Article/details/gtgwatagyp.html

int *p = &a;  *p = 5;
来源：http://dali.nanxuanxn.top/Article/details/gtjxjrogzt.html

[S11] C：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtqyfpsxhj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aibaodan.cn/Article/details/gtatwoxcia.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtsdtwkqct.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtlxijvqcx.html

[S12] C：写文件
来源：http://dali.svipenyu.cn/Article/details/gtcwyuaxgy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtvvpwzmgq.html

[S13] C：宏定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkzbwfsb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ybcxt.top/Article/details/gtduzflohk.html

[S14] C：枚举
来源：http://dali.snrcjt.cn/Article/details/gtjjpookzu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhengqikj.top/Article/details/gtxtqsnwjy.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gtmioutddy.html

(double) a / b
来源：http://dali.wangdashe.top/Article/details/gtvjipjbdk.html

[S16] C：位操作置位
来源：http://dali.jianghu66.top/Article/details/gttctmkynz.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gtfrhtdbbp.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtumiwrgax.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gtguvjhfqt.html

[S18] C：命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtmcbcskmn.html

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gtkswhsebu.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gtcreqsdjl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gtuaddgytp.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gtdgpfpcaw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtmgqfvflt.html

[S21] C：字符类别判断
来源：http://dali.shzxlz.cn/Article/details/gteeimqcto.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xinyue.icu/Article/details/gtnyvnjphr.html

[S22] C：字符串转数字
来源：http://dali.yj20258.top/Article/details/gtjfvchhqw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gtcvwquppt.html

[S23] C：随机数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuiztcrwq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gtswepynti.html

[S24] C：获取本地时间
来源：http://dali.hnxiangtu.top/Article/details/gtsqfrhmve.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnqzz.top/Article/details/gtcuspfxih.html

[S25] C：内存拷贝
来源：http://dali.mhx1999.top/Article/details/gtzoxcloqu.html

memcpy(dst, src, n);
来源：http://dali.mhx1999.top/Article/details/gtomyivpkm.html

[S26] C：内存清零
来源：http://dali.hongshengwenyu.top/Article/details/gthtbqhsds.html

memset(a, 0, sizeof a);
来源：http://dali.wangshuangyany.cn/Article/details/gtcmrrhdmo.html

[S27] C：定义常量
来源：http://dali.iojbl.cn/Article/details/gtuxumthow.html

const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtinhjtaux.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gtlbovicwo.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gtmjneyyuf.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gtvdkwzxcb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gtuxxnjmcz.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gtaymywazf.html

#ifndef X_H
来源：http://dali.hysaishi.cn/Article/details/gtkzbflwrr.html

#define X_H
来源：http://dali.yongpay.top/Article/details/gtmsbprzoo.html

#endif
来源：http://dali.ivvv.top/Article/details/gttesvjene.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtpbmwqjhp.html

#include <iostream>
来源：http://dali.c1oappe.top/Article/details/gttdavmzzi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gtivfnktjc.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gtdgmdpajv.html

std::string s = "hi";  s += "!";
来源：http://dali.gotoacloud.top/Article/details/gtdmpkqstd.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotfhzghc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhixingplan.top/Article/details/gtwibxdjwb.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gtqfnlehfq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.9152youxi.cn/Article/details/gtcngjgyxa.html


<!-- 参考信息 -->