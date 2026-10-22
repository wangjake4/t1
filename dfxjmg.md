代发 wailian999

[Q63] 开启事务
来源：http://dali.tian-w.cn/Article/details/gtsfmvmfed.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fengsongda.top/Article/details/gtxfnamtbp.html

[Q64] 提交事务
来源：http://dali.gzhubu.top/Article/details/gtrmxpqazr.html

COMMIT;
来源：http://dali.zhoulong.xyz/Article/details/gtvpemyxcg.html

[Q65] 回滚事务
来源：http://dali.hywenlv.cn/Article/details/gtvyrtwkms.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gtyflrpfdt.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gtfrpbtcqf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258.top/Article/details/gtbonojjdb.html

[Q67] 设置隔离级别
来源：http://dali.wangshuangyany.cn/Article/details/gtbkuediei.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gtxjdzajag.html

[Q68] 保存点
来源：http://dali.316326.xyz/Article/details/gttulbbtzv.html

SAVEPOINT sp1;
来源：http://dali.zdqjudy.top/Article/details/gtwbfbcdrn.html

ROLLBACK TO sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtjgkvbszl.html

[Q69] 查看执行计划
来源：http://dali.guannengcc.top/Article/details/gtmxmilyjp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gtwlwcrfxs.html

[Q70] 更新统计信息
来源：http://dali.hammf.cn/Article/details/gtqdomhutl.html

ANALYZE TABLE users;
来源：http://dali.zycfv.cn/Article/details/gtkmqxxmjc.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gtmtuashaz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258.top/Article/details/gtfzrtrlde.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gtuvxerhse.html

SHOW INDEX FROM users;
来源：http://dali.birdmap.top/Article/details/gtreigyopk.html

[Q73] 查看表状态
来源：http://dali.jyoumei.cn/Article/details/gtztmwcpmg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gtfbecylyh.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gtvmqemidw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gtqebapkva.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtrsfetqlh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtefvvtfzy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.feifeiyinyue.top/Article/details/gtzsjdrtjq.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gtbwzbujkg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhixingplan.top/Article/details/gtbyoglthu.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gtndtjqymn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guannengcc.top/Article/details/gthfgxvtys.html

[Q78] 当前时间
来源：http://dali.chenlongwang.top/Article/details/gtncipstnc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cashguo.top/Article/details/gtugunmphw.html

[Q79] 字符串拼接
来源：http://dali.tanke756.top/Article/details/gtzsmdfsph.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuetiantiany.cn/Article/details/gtcmzbyell.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gtphkeksdl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gthzpjmiiu.html

[Q81] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtzmtmxxiq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtbvdgwftc.html

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gtmsujnjan.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtturmfypl.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtjskkbxnl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtefcfxbre.html

[Q84] 去除首尾空格
来源：http://dali.hongshengwenyu.top/Article/details/gtdygdiqti.html

SELECT TRIM(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtcbkqptdu.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gtunshpxiw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yvedp.cn/Article/details/gtjjrcchkt.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gtsutprnee.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxoqgeyq.html

[Q87] JSON 字段做条件
来源：http://dali.haohaochexian.top/Article/details/gtiektylju.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hammf.cn/Article/details/gtrlchcapz.html

[Q88] 行转列（条件聚合）
来源：http://dali.gogol.net.cn/Article/details/gtcxsjuiaa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gtwgonptql.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtdlsvcbfu.html

[Q89] 判断表是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdwmwgpv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gtuxlwwntw.html

[Q90] 生成序号列
来源：http://dali.smart0.xyz/Article/details/gtwjtztwfp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gtlfblhbgs.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gthddistua.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gtvwshqkib.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtyotzdhut.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gtkygiwogu.html

#!/usr/bin/env bash
来源：http://dali.haohaochexian.top/Article/details/gtxdaznzsw.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gtanzxmlkg.html

[R02] 变量赋值与使用
来源：http://dali.zhixingplan.top/Article/details/gtpotoaalw.html

name="Tom"; echo "$name"
来源：http://dali.ppjwa.cn/Article/details/gtlvpuwsbf.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gtjxzcuuuv.html

readonly PI=3.14
来源：http://dali.wangdashe.top/Article/details/gtbmtjfcxp.html

[R04] 位置参数
来源：http://dali.yvedp.cn/Article/details/gtmgriacxr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.9152youxi.cn/Article/details/gtggjybvnj.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gtlqqlfdrd.html

name="${1:-default}"
来源：http://dali.316326.xyz/Article/details/gtrlnejewa.html

[R06] 判断命令是否存在
来源：http://dali.yj20258.top/Article/details/gtiwzgnfhq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtaenarylp.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gtqjgqyxma.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258.top/Article/details/gtjjcwcvrh.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gtposlmrfr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtrtiyfzvc.html

[R09] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtitxdpafx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sweek.top/Article/details/gtmibfaifk.html

[R10] 正则匹配
来源：http://dali.ydzc1.top/Article/details/gtfluixvwl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gterdovqbj.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gtcaxnzhwm.html

case "$1" in
来源：http://dali.quarkkingdee.top/Article/details/gttqrumtva.html

start) echo "启动" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtcsemdbid.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gtlzcuyfhf.html

*)     echo "未知命令" ;;
来源：http://dali.dashuyun.cn/Article/details/gtlpdjqgnu.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gtfxmmakiy.html

[R12] for 遍历文件
来源：http://dali.vqdsnc.cn/Article/details/gtkstzzgcr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtzibvwknf.html

[R13] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gtvstnribx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtqaloljoq.html

[R14] C 风格 for
来源：http://dali.wangshuangyany.cn/Article/details/gtqdnusznr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gtjumxneol.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtcvgxjquk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gtmgyhatob.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gtyvukaife.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gtzgnffbdu.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gtkriwmwug.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.havefunace.top/Article/details/gtqjfnxace.html

[R18] 遍历数组
来源：http://dali.havefunace.top/Article/details/gtqmxwtoby.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmwqeimp.html

[R19] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtrfluwohc.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gtptnpqrdd.html

[R20] 关联数组（字典）
来源：http://dali.xuanzx.com/Article/details/gtoshzrayu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xylfe.cn/Article/details/gtivoamhvy.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtozvttcod.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhtosrjj.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtzvkcbzaj.html

echo "${s:0:5}"
来源：http://dali.chenlongwang.top/Article/details/gtdoehanmz.html

[R23] 字符串替换
来源：http://dali.yongpay.top/Article/details/gttilpstqb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gtyjhzlbcm.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtxwmybuvw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gtlopaihin.html

[R25] 去后缀 / 去前缀
来源：http://dali.iojbl.cn/Article/details/gtooeewvgd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gtispliiec.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gtjdjvumpg.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gtzowtsdpp.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gtugeasgny.html

echo $((1 + 2 * 3))
来源：http://dali.shzxlz.cn/Article/details/gtgjxdoezp.html

[R28] 浮点运算
来源：http://dali.tian-w.cn/Article/details/gtnjgngiry.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gtquuikvjq.html

[R29] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gtlmufdxca.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gtlzswnxml.html

[R30] 函数返回状态码
来源：http://dali.xziqi.cn/Article/details/gtybjwuhwb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hywenlv.cn/Article/details/gtchhsbeyo.html

[R31] 局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtekubwgji.html

f() { local x=1; echo "$x"; }
来源：http://dali.cheryme.top/Article/details/gtnsxdavwk.html

[R32] 参数个数校验
来源：http://dali.jqgfzy.top/Article/details/gtfssvsuuu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gtavvkdazg.html

[R33] 捕获错误并提示行号
来源：http://dali.cdnleiting.top/Article/details/gtgeeojkit.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gtrtkawzem.html

[R34] 退出时清理
来源：http://dali.yanxiufei.cn/Article/details/gtguarcaqo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gttsvhkixv.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gtmrkszxab.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gtbjqhbbwx.html

[R36] 并发执行多个任务
来源：http://dali.0kj1m.cn/Article/details/gtgpsxadnl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gtpsvqehbf.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gtrddiebmx.html

files=$(ls -1)
来源：http://dali.jlsjyb.cn/Article/details/gtwtcrvcep.html

[R38] 管道串联
来源：http://dali.hammf.cn/Article/details/gtpdxfhwyl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccxvpefa.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gtqpclrpmw.html

cmd > out.log 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtiqvejwmx.html

[R40] 追加写日志
来源：http://dali.zhixingplan.top/Article/details/gtghscpvmk.html

echo "log" >> out.log
来源：http://dali.guowangkeji.top/Article/details/gtifvcmoiw.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gtyenreijf.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gtghugfnsk.html

[R42] 输入重定向
来源：http://dali.tianlin.xyz/Article/details/gtwsgbiipu.html

wc -l < a.txt
来源：http://dali.ppjwa.cn/Article/details/gtdlcrzeek.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gtzeviwybd.html

find . -name "*.log" -type f
来源：http://dali.bjfxy.top/Article/details/gtdqlfwrti.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjwuwtdu.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gtseqidqsp.html

[R45] 批量删除
来源：http://dali.tanke756.top/Article/details/gtxzodqupj.html

find . -name "*.tmp" -delete
来源：http://dali.fengsongda.top/Article/details/gtkswipgkc.html

[R46] 递归替换文件内容
来源：http://dali.hammf.cn/Article/details/gtyyvhvfcg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tianlin.xyz/Article/details/gtqvzgwgkh.html

[R47] sed 单行替换
来源：http://dali.nwbrower.top/Article/details/gtmywhszrv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtudupotqj.html

[R48] awk 取指定列
来源：http://dali.ehwqpu.com/Article/details/gtzzeyxvof.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhfpqdkg.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gtrgoqkbvd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrnqecwa.html

[R50] awk 求和
来源：http://dali.zycfv.cn/Article/details/gtaducphjc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yvedp.cn/Article/details/gtpixpboin.html

[R51] 排序去重取前几
来源：http://dali.yongpay.top/Article/details/gtxzupfdcj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuanzx.com/Article/details/gtxznwlvvt.html

[R52] 统计行数
来源：http://dali.jqgfzy.top/Article/details/gtbggfwjzd.html

wc -l a.txt
来源：http://dali.gogol.net.cn/Article/details/gtsvwpurls.html

[R53] 查看文件头与实时尾
来源：http://dali.yanxiufei.cn/Article/details/gtevzkwcpy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hysaishi.cn/Article/details/gtgogpvqrz.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gttaauwomt.html

diff a.txt b.txt
来源：http://dali.nanxinkj.top/Article/details/gtinqkvklv.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gtgqvwqtcv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pycfn.com/Article/details/gthgrljdck.html

[R56] 远程拷贝
来源：http://dali.9152youxi.cn/Article/details/gthyskosaf.html

scp file user@host:/path/
来源：http://dali.9152youxi.cn/Article/details/gthecwbhis.html

[R57] 远程执行命令
来源：http://dali.snrcjt.cn/Article/details/gtcaofbklh.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gtnkgtoycd.html

[R58] 下载文件
来源：http://dali.svipenyu.cn/Article/details/gtindqpqbv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pycfn.com/Article/details/gtziqwpofs.html

[R59] 发 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtivcfkxfx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yueranfly.top/Article/details/gttjqaqfwx.html

[R60] 只看 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtwugmbcdw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhongyouzk.top/Article/details/gtwdfhpxsp.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gtpwjsfpia.html

df -h;  du -sh *
来源：http://dali.yj20258888.top/Article/details/gtfnbtzzri.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gtlvebtzcv.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gtfnehbmtx.html

[R63] 内存与进程
来源：http://dali.dashuyun.cn/Article/details/gtldulldpl.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gtaxptnwqe.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gtgiajztpv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxinkj.top/Article/details/gtafeqvjno.html

[R65] 查看端口占用
来源：http://dali.chenzaomai.com/Article/details/gtlivngsfw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gtisrgqadu.html

[R66] 定时任务
来源：http://dali.svipenyu.cn/Article/details/gtzhlfeczf.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gtncuepwma.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gtgksftwqf.html

openssl rand -hex 16
来源：http://dali.feifeiyinyue.top/Article/details/gtbvfmxbzn.html

[R68] 计算文件校验值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiobpbgeg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gtunbsgbko.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gtbomsakpq.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gtarqniiqx.html

[R70] 时间戳与互转
来源：http://dali.quarkkingdee.top/Article/details/gtzuvmwetv.html

date +%s;  date -d @1700000000
来源：http://dali.gaohongyu789.top/Article/details/gttdlnrjqo.html

[R71] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtnxojzlvo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gtgomnfuoz.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gtgswisghs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtdxctiavb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gtiqzyukjm.html

split -l 1000 big.log part_
来源：http://dali.daxiang520.top/Article/details/gtifzlzjlf.html

[R74] 批量重命名
来源：http://dali.jianghu66.top/Article/details/gtmbmeaapz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gticnesbsg.html

[R75] 导出环境变量
来源：http://dali.cheryme.top/Article/details/gtshckohac.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinghuilouyu.cn/Article/details/gthqggyvzg.html

[R76] 使用临时文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuogfhdpi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gtitznkqbz.html

[R77] 读取用户输入
来源：http://dali.zdqjudy.top/Article/details/gtvflrgbrm.html

read -rp "请输入: " ans
来源：http://dali.xuetiantiany.cn/Article/details/gthsgziehd.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gtwioqxoom.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gtpqlatadi.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gtnqdrvtbc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gtzpbzfifu.html

[R80] 查看脚本执行耗时
来源：http://dali.xuanzx.com/Article/details/gtxeevzkyo.html

time ./run.sh
来源：http://dali.9152youxi.cn/Article/details/gtpfcpvskc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvoaarpqd.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gtmegvqfyk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtgptymnwi.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtxtznbuda.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gtlkkzpxop.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtvjdimmnb.html

[S02] C：变量与格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtaxrrdewf.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gtyqbntqsk.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gtyknjdolf.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gtpmtjfwkf.html

[S04] C：字符串复制
来源：http://dali.cdnleiting.top/Article/details/gtbaajbgsk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtwwahplan.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gtssiacyyy.html

strlen(s)
来源：http://dali.smart0.xyz/Article/details/gtslkrvktf.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtchrqgbxj.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gtzaplhgck.html

[S07] C：数组遍历求和
来源：http://dali.ehwqpu.com/Article/details/gtwbbufoll.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shzxlz.cn/Article/details/gtxtnwuzmb.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gtkepufyua.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ybcxt.top/Article/details/gtmalinwwd.html

[S09] C：结构体定义与初始化
来源：http://dali.smart0.xyz/Article/details/gtlzahklru.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gtciifhaaf.html

[S10] C：指针与解引用
来源：http://dali.aibaodan.cn/Article/details/gtbcgzftkl.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gtixayqoks.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtbwcfshph.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.iojbl.cn/Article/details/gtlrsonjqw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtcwcqogml.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtomdmzpkb.html

[S12] C：写文件
来源：http://dali.hnqzz.top/Article/details/gtrygckpqg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtdnovwmlq.html

[S13] C：宏定义
来源：http://dali.tianlin.xyz/Article/details/gthbtqdsui.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gtdzdhmrcc.html

[S14] C：枚举
来源：http://dali.snrcjt.cn/Article/details/gtkouxmyzg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gtmnitomxm.html

[S15] C：类型转换
来源：http://dali.0kj1m.cn/Article/details/gtykyfnmry.html

(double) a / b
来源：http://dali.fengsongda.top/Article/details/gtaxzpsovc.html

[S16] C：位操作置位
来源：http://dali.jinqigufen.top/Article/details/gtqqesdkpy.html

x |= (1 << 3);
来源：http://dali.tanke756.top/Article/details/gtbymsbrqw.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtdqlzvqjk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozijerna.html

[S18] C：命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gtchexbkth.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gtrelvyrtg.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gtggbltbvh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gtfrdfuwav.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gtnyuqeeks.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtmfsyubev.html

[S21] C：字符类别判断
来源：http://dali.jyoumei.cn/Article/details/gtgbttdtpm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvmdaikt.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxevnodgv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gtfoayxrwl.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gtnwoijrum.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthepwtaob.html

[S24] C：获取本地时间
来源：http://dali.havefunace.top/Article/details/gtlxckknfy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gtzhvtjrdj.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gtyauvdyun.html

memcpy(dst, src, n);
来源：http://dali.zhongyouzk.top/Article/details/gtotrkrncp.html

[S26] C：内存清零
来源：http://dali.jlsjyb.cn/Article/details/gtwsehhqnb.html

memset(a, 0, sizeof a);
来源：http://dali.havefunace.top/Article/details/gtftiqgthq.html

[S27] C：定义常量
来源：http://dali.ybcxt.top/Article/details/gtsjnksmdp.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtgwpxhzpj.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gtevcggtbw.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gthlrsqkuh.html

[S29] C：变参函数
来源：http://dali.c1oappe.top/Article/details/gtarcatdcx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gttidhggqq.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gtsgobvtxa.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtnfmcmrgd.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gtkpfecdxc.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gtjuxwhman.html

[S31] C++：Hello World
来源：http://dali.fzhhl.top/Article/details/gtprtigjnt.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gtuhdjcjma.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gtnjujvyvg.html

[S32] C++：字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzmfxwzf.html

std::string s = "hi";  s += "!";
来源：http://dali.hongshengwenyu.top/Article/details/gtbrhnbmzr.html


<!-- 参考信息 -->