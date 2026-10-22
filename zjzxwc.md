代发 wailian999

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gtiisifjzj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxinkj.top/Article/details/gteddpywjr.html

[Q64] 提交事务
来源：http://dali.sufxvd.cn/Article/details/gtnvzeopfr.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gtyqbwcewa.html

[Q65] 回滚事务
来源：http://dali.sufxvd.cn/Article/details/gthlgfmvnu.html

ROLLBACK;
来源：http://dali.zhiwuduotai.top/Article/details/gtvmmljxnl.html

[Q66] 行锁查询
来源：http://dali.redwolf501.top/Article/details/gtzodvqeyy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gttvhqhcso.html

[Q67] 设置隔离级别
来源：http://dali.wangshuangyany.cn/Article/details/gtveessmuc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jyoumei.cn/Article/details/gtvycevhbb.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gtevwvmhhd.html

SAVEPOINT sp1;
来源：http://dali.ppjwa.cn/Article/details/gtfoyklrro.html

ROLLBACK TO sp1;
来源：http://dali.hywenlv.cn/Article/details/gtnonvvawc.html

[Q69] 查看执行计划
来源：http://dali.gotoacloud.top/Article/details/gtmebunmqe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gtiainosmh.html

[Q70] 更新统计信息
来源：http://dali.zycfv.cn/Article/details/gtrfvucmgi.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gtompfhmnt.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gtyirhhmlb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gtzqzeozeh.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gtjkiercve.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gtmfzljqgn.html

[Q73] 查看表状态
来源：http://dali.xinyue.icu/Article/details/gtyarzpxqf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.andypj.xyz/Article/details/gtuvmgvobt.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gtyxvpuqir.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ybcxt.top/Article/details/gtisfapgmu.html

[Q75] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtjdvwlyid.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtxcmsnjpi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cucudq.cn/Article/details/gtwdpqukfb.html

[Q76] 按天统计
来源：http://dali.jyoumei.cn/Article/details/gtxucdfxep.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ydzc1.top/Article/details/gtsyrcxkld.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gtcqlfztqo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gtnrgasqjy.html

[Q78] 当前时间
来源：http://dali.guowangkeji.top/Article/details/gtsdrahmvj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gtyafoxmjq.html

[Q79] 字符串拼接
来源：http://dali.smart0.xyz/Article/details/gtxtayjtgg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsvlqqir.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gtzcpzygma.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtktbbzoxf.html

[Q81] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gtfsfdnnwx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tanke756.top/Article/details/gtgnsdrecm.html

[Q82] 字符长度与字节长度
来源：http://dali.kuanghao11.cn/Article/details/gtugtzxqdg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxqsadoe.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdhpgici.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtfrwfibhk.html

[Q84] 去除首尾空格
来源：http://dali.iojbl.cn/Article/details/gtxhpeajtp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtusnhrddu.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gtylhmkwxk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gtbfwsxslu.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gtyxeysjhu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shuidangran.top/Article/details/gtqjpneipn.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gtkcgxluey.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigfzy.top/Article/details/gtxqgvejfx.html

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gtwkfzssfv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gtzdfbzkfc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gtuhbvmfns.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gtzhitnxkt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gtrxwaqrmv.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gticdwlaxd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuxokddx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtoezxxvjy.html

R. Bash 专题
来源：http://dali.birdmap.top/Article/details/gtnxluozlw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtxabtxsnt.html

[R01] shebang 与严格模式
来源：http://dali.jinghuilouyu.cn/Article/details/gtuaonlobv.html

#!/usr/bin/env bash
来源：http://dali.cdnleiting.top/Article/details/gtzhemtupv.html

set -euo pipefail
来源：http://dali.sysykeji.top/Article/details/gtyvnjqboc.html

[R02] 变量赋值与使用
来源：http://dali.nanxinkj.top/Article/details/gtjdnaxmoy.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gtoyewltqy.html

[R03] 只读变量
来源：http://dali.sxryk.cn/Article/details/gtpfvekcog.html

readonly PI=3.14
来源：http://dali.yangfankeji.com/Article/details/gtglzupvwi.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gttoyxhuaz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gtcglpghjy.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gtohbvvdif.html

name="${1:-default}"
来源：http://dali.yonumen.top/Article/details/gtqhgqpcpl.html

[R06] 判断命令是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgxlsjce.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtifhqqqeq.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gtawxkocvg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gteovzhtsg.html

[R08] 数值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpagvkya.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.9152youxi.cn/Article/details/gtrnaprotu.html

[R09] 字符串比较
来源：http://dali.c1oappe.top/Article/details/gtnheykzsi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gtuuqiydfn.html

[R10] 正则匹配
来源：http://dali.zhengqikj.top/Article/details/gtdiryxqsj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hfpthk.cn/Article/details/gtkssxxeuk.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gtbdqvwemn.html

case "$1" in
来源：http://dali.haohaochexian.top/Article/details/gthjagxzvu.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gtistyeimg.html

stop)  echo "停止" ;;
来源：http://dali.zhengqikj.top/Article/details/gtvepuorpl.html

*)     echo "未知命令" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtmhafrxqk.html

esac
来源：http://dali.c1oappe.top/Article/details/gtedunlhhn.html

[R12] for 遍历文件
来源：http://dali.fengsongda.top/Article/details/gtlxflfztt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shzxlz.cn/Article/details/gtxkmjxfkt.html

[R13] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gtpdxrnckb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtoivbnppt.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gtyytxwxkp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtcffzdbsp.html

[R15] while 逐行读文件
来源：http://dali.yuxming.cn/Article/details/gthdlwmxig.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gaohongyu789.top/Article/details/gtmpvxhhhl.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gtvkvtgovt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtbmmdpani.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gtmrauwqun.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jianghu66.top/Article/details/gtxjcikvtv.html

[R18] 遍历数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirckkabw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gtlaupthqe.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtjjwujwqs.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtiydkwrow.html

[R20] 关联数组（字典）
来源：http://dali.aizwys.cn/Article/details/gtyepeqtfv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gtddkhlyza.html

[R21] 字符串长度
来源：http://dali.yongpay.top/Article/details/gtvkgwjkix.html

echo "${#s}"
来源：http://dali.cqqwz.cn/Article/details/gtfxewfolt.html

[R22] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtufbdodsj.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnszwgpxs.html

[R23] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtodtrvcip.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gtgtvybbjk.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtjctjqcjd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shangyingyoupin.top/Article/details/gttrcebkez.html

[R25] 去后缀 / 去前缀
来源：http://dali.hammf.cn/Article/details/gtuivmoplv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuanzx.com/Article/details/gtbdtjndsu.html

[R26] 命令替换
来源：http://dali.zhixingplan.top/Article/details/gtthelsggh.html

now=$(date +%F); echo "$now"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjjxymta.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gtccyumvkw.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gtsymxzyjp.html

[R28] 浮点运算
来源：http://dali.pycfn.com/Article/details/gtdtvizpjq.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtqmivpxej.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gtqwyppmcx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aibaodan.cn/Article/details/gtsqzcxbzl.html

[R30] 函数返回状态码
来源：http://dali.tianlin.xyz/Article/details/gtfsoejiqe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.quarkkingdee.top/Article/details/gtbljqhnqm.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gteslkqbzy.html

f() { local x=1; echo "$x"; }
来源：http://dali.haohaochexian.top/Article/details/gtggngewyl.html

[R32] 参数个数校验
来源：http://dali.0kj1m.cn/Article/details/gterdumthf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtclmuvqpn.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gtmjsnlbij.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gtzopslwqj.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gtpvaaumiw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtiyyemqoz.html

[R35] 后台执行并等待
来源：http://dali.cheryme.top/Article/details/gtmcqffvgt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yongpay.top/Article/details/gtmakwgxwn.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gtasprgswv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigfzy.top/Article/details/gtqxjhvgmc.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gtajatyvye.html

files=$(ls -1)
来源：http://dali.fengsongda.top/Article/details/gtbkfpiqvi.html

[R38] 管道串联
来源：http://dali.xuanzx.com/Article/details/gtnhtydlxz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuanzx.com/Article/details/gtgmcuebkq.html

[R39] 重定向标准输出与错误
来源：http://dali.xuetiantiany.cn/Article/details/gtjakgmedj.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gtvxvohubw.html

[R40] 追加写日志
来源：http://dali.hnxiangtu.top/Article/details/gtyyeqynam.html

echo "log" >> out.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpaegfpae.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gtgedpndjf.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gtsplphmwz.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gtegezmoen.html

wc -l < a.txt
来源：http://dali.xylfe.cn/Article/details/gthlpdsqxs.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gtkqleaqqc.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gtuojnhhvp.html

[R44] 按修改时间查找
来源：http://dali.316326.xyz/Article/details/gthtwrjkjv.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gtveqcksfd.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gtlifnjnhg.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gtqfuvimkk.html

[R46] 递归替换文件内容
来源：http://dali.jianghu66.top/Article/details/gtucwhsqas.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigfzy.top/Article/details/gtrmqhyksp.html

[R47] sed 单行替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtgthlaqmo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258888.top/Article/details/gtjhxdhkcr.html

[R48] awk 取指定列
来源：http://dali.birdmap.top/Article/details/gtwvynatmt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwthxlkjo.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gtmjxgvefp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xinyue.icu/Article/details/gtildsphjm.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gtyljcbrne.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtqxumrbso.html

[R51] 排序去重取前几
来源：http://dali.aibaodan.cn/Article/details/gtdegljhng.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gtjkhttvjr.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gtmpggpfup.html

wc -l a.txt
来源：http://dali.meibo888.top/Article/details/gtrpctzyia.html

[R53] 查看文件头与实时尾
来源：http://dali.yongpay.top/Article/details/gtnuubqsrz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gtcoersrgo.html

[R54] 比较两个文件
来源：http://dali.xinyue.icu/Article/details/gtnslpboyr.html

diff a.txt b.txt
来源：http://dali.yj202588.top/Article/details/gtjbeqhgws.html

[R55] 压缩与解压
来源：http://dali.kuanghao11.cn/Article/details/gtlppxgrgd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.birdmap.top/Article/details/gtbkzfisji.html

[R56] 远程拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtwiysifro.html

scp file user@host:/path/
来源：http://dali.tianlin.xyz/Article/details/gtibyhcpnb.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gtsbbtcgxj.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gtdbhtuzqg.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gtwkfcbaun.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hfpthk.cn/Article/details/gtongztllv.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtxufdlixk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yonumen.top/Article/details/gtsmzeuikw.html

[R60] 只看 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtedtrxsbh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gtfvfkyeze.html

[R61] 磁盘占用
来源：http://dali.chenlongwang.top/Article/details/gtglqkxugx.html

df -h;  du -sh *
来源：http://dali.gzhubu.top/Article/details/gtzvimnpog.html

[R62] 找最占空间的文件
来源：http://dali.havefunace.top/Article/details/gtgxdvxcpu.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gtbkozamqn.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gtyfcsddhh.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gtpflpdhgt.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gtivpxtctd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gtgylutlyb.html

[R65] 查看端口占用
来源：http://dali.yj20258888.top/Article/details/gtggboxruu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gteexsdcvt.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gtcmwvqmcj.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gtmsgdvxfm.html

[R67] 生成随机十六进制串
来源：http://dali.hywenlv.cn/Article/details/gtyuswyapj.html

openssl rand -hex 16
来源：http://dali.ehwqpu.com/Article/details/gtmpihfwck.html

[R68] 计算文件校验值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdqtqjmt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtusjywwrw.html

[R69] 生成随机密码
来源：http://dali.jqgufenzy.top/Article/details/gttxvknkua.html

head -c 16 /dev/urandom | base64
来源：http://dali.haohaochexian.top/Article/details/gtwbihixid.html

[R70] 时间戳与互转
来源：http://dali.cheryme.top/Article/details/gthkulyags.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gttgafxtfl.html

[R71] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtuzqglyvr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gtwiroxouu.html

[R72] 等待端口就绪
来源：http://dali.jqgfzy.top/Article/details/gtnuusjzlu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtffyokmqh.html

[R73] 分割大日志
来源：http://dali.cashguo.top/Article/details/gtnxlydoxx.html

split -l 1000 big.log part_
来源：http://dali.jqgfzy.top/Article/details/gtsjdjohww.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtjhkxkbuo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtpgvkatup.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gtmhpxmtaq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.feifeiyinyue.top/Article/details/gtttjxnsyi.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gtdqurwnad.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gtjewysdvo.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gtnsmyalny.html

read -rp "请输入: " ans
来源：http://dali.feifeiyinyue.top/Article/details/gtrdxbedhr.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gtzyrzyoru.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gtodposxen.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gtccudztiv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangdashe.top/Article/details/gtdbhlelax.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gtftmixian.html

time ./run.sh
来源：http://dali.shanyushiyangtech.top/Article/details/gtynhvoaah.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtiixioirb.html

S. C / C++ 专题
来源：http://dali.zhongyouzk.top/Article/details/gtxeizqexe.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnlebxhhw.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gthggytrxu.html

#include <stdio.h>
来源：http://dali.cucudq.cn/Article/details/gtmllwdgto.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hysaishi.cn/Article/details/gtaobieobu.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdklirvy.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gtnmqmhohe.html

[S03] C：读入整数
来源：http://dali.yj20258.top/Article/details/gtdxkbsxtf.html

int x; scanf("%d", &x);
来源：http://dali.xinyue.icu/Article/details/gtftcwknpn.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizupwzad.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.bjfxy.top/Article/details/gtxypkwzxd.html

[S05] C：字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtrvehosbz.html

strlen(s)
来源：http://dali.daria6918.cn/Article/details/gtpikuveto.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gtlutunwdo.html

strcmp(a, b) == 0
来源：http://dali.quarkkingdee.top/Article/details/gtozyywack.html

[S07] C：数组遍历求和
来源：http://dali.jqgfzy.top/Article/details/gtobqtphhn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.316326.xyz/Article/details/gtqdwnvfsz.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxinkj.top/Article/details/gtzfdvbnrj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gtxuxagggk.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtunbdyrsc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gtpddwwbtg.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gthxybikob.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gtjxiadxfc.html

[S11] C：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtrgavkgyn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gtucwaixgm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gtewjaxahu.html

fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtkckhyjmu.html

[S12] C：写文件
来源：http://dali.xylfe.cn/Article/details/gttteernmm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtgckksxgh.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gtbwuwexup.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gtmjtgimis.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gtbodgjtjm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangshuangyany.cn/Article/details/gtsugicixa.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gtzvuckwbt.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gtnjzkiutw.html

[S16] C：位操作置位
来源：http://dali.gogol.net.cn/Article/details/gtbwuwfgnq.html

x |= (1 << 3);
来源：http://dali.yj20258888.top/Article/details/gtrizhclhv.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjnptric.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sysykeji.top/Article/details/gtajshhixi.html

[S18] C：命令行参数
来源：http://dali.hfpthk.cn/Article/details/gthwbbsaoq.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gtnclqttmn.html

[S19] C：快速排序
来源：http://dali.redwolf501.top/Article/details/gtwlpihdna.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtjgpapwsk.html

[S20] C：二分查找
来源：http://dali.9152youxi.cn/Article/details/gtxhioijnq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtnkccvtsx.html

[S21] C：字符类别判断
来源：http://dali.yvedp.cn/Article/details/gtfylwdrty.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gtbbjuqgek.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gttqkkcvsi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.havefunace.top/Article/details/gtroqhtpnz.html

[S23] C：随机数
来源：http://dali.hywenlv.cn/Article/details/gtaqyegxtm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxuanxn.top/Article/details/gtelayvtuj.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gtqttunfdh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuetiantiany.cn/Article/details/gtcknjilvs.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gtlifppmww.html

memcpy(dst, src, n);
来源：http://dali.yueranfly.top/Article/details/gtgbcfifym.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gtvgjjqyka.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gthezittpe.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gtmkikxnyl.html

const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtieyfifvt.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gtulmuaxzt.html

static int counter = 0;
来源：http://dali.bjfxy.top/Article/details/gtoywsnbzb.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gthafuvtpg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shzxlz.cn/Article/details/gtxsygiyhi.html

[S30] C：头文件保护
来源：http://dali.kuanghao11.cn/Article/details/gtcgnxsvya.html

#ifndef X_H
来源：http://dali.zycfv.cn/Article/details/gtkbjnxpcp.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gtnshmpnfo.html

#endif
来源：http://dali.ybcxt.top/Article/details/gtkqiaksws.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtvxlgmcil.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gtvastriiw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gthcmnbdgj.html

[S32] C++：字符串
来源：http://dali.svipenyu.cn/Article/details/gtfcfhfkzz.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gtdnwjnkbs.html


<!-- 参考信息 -->