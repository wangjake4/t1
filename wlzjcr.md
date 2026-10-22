代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.9152youxi.cn/Article/details/gtqtxirhry.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gtfrqkirea.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sufxvd.cn/Article/details/gttfavcazd.html

[Q70] 更新统计信息
来源：http://dali.jianghu66.top/Article/details/gtxplfghom.html

ANALYZE TABLE users;
来源：http://dali.cashguo.top/Article/details/gtmtxeaxok.html

[Q71] 查看建表语句
来源：http://dali.tanke756.top/Article/details/gtkdwecati.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sxryk.cn/Article/details/gtxgwcdeps.html

[Q72] 查看索引
来源：http://dali.yj20258888.top/Article/details/gtwztebxlc.html

SHOW INDEX FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtsgdqmlph.html

[Q73] 查看表状态
来源：http://dali.gaohongyu789.top/Article/details/gtvhdmqowy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.haohaochexian.top/Article/details/gtpfvrbtlp.html

[Q74] 强制使用索引
来源：http://dali.gogol.net.cn/Article/details/gthuqyzlbh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shangyingyoupin.top/Article/details/gtojupyexv.html

[Q75] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtawxmkvta.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtedvjgooe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuetiantiany.cn/Article/details/gtcgwxakaq.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gtnccseujw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gtwqlqjyqe.html

[Q77] 时间加减
来源：http://dali.zhixingplan.top/Article/details/gtattbeage.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gtfoqwcqlk.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtwaliggoh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupehrkry.html

[Q79] 字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gtptsrpbwi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jianghu66.top/Article/details/gtncmgvane.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gtqdicdblc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cheryme.top/Article/details/gtygwehhtc.html

[Q81] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtsaqoymsr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtesdlrdel.html

[Q82] 字符长度与字节长度
来源：http://dali.xinyue.icu/Article/details/gtshupmlef.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtrsqtqkxs.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtubpejdbn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gteuduwlgw.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtjwjvltig.html

SELECT TRIM(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtmkbpbqbs.html

[Q85] 数值取整
来源：http://dali.jlsjyb.cn/Article/details/gtljslpbwb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nwbrower.top/Article/details/gtylyyzdvn.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gtutmgvmon.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cashguo.top/Article/details/gtlksxlscc.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gtmapulmce.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuetiantiany.cn/Article/details/gtuafdclfu.html

[Q88] 行转列（条件聚合）
来源：http://dali.ehwqpu.com/Article/details/gtkhtuhtax.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ivvv.top/Article/details/gtqoemxtfy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtaxwdrzov.html

[Q89] 判断表是否存在
来源：http://dali.hammf.cn/Article/details/gtxiasodsu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.iojbl.cn/Article/details/gtwpgnkeqs.html

[Q90] 生成序号列
来源：http://dali.jlsjyb.cn/Article/details/gteumhkyno.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgufenzy.top/Article/details/gtbmbpflpz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalccaext.html

R. Bash 专题
来源：http://dali.feifeiyinyue.top/Article/details/gttswwpwxm.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtbwjvwaur.html

[R01] shebang 与严格模式
来源：http://dali.xylfe.cn/Article/details/gtrmybdukd.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gtuymsbjoy.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvrbcodk.html

[R02] 变量赋值与使用
来源：http://dali.sweek.top/Article/details/gtdakzpyai.html

name="Tom"; echo "$name"
来源：http://dali.yongpay.top/Article/details/gttgexccdn.html

[R03] 只读变量
来源：http://dali.shuidangran.top/Article/details/gtegmextov.html

readonly PI=3.14
来源：http://dali.jinqigufen.top/Article/details/gtptxrxlrv.html

[R04] 位置参数
来源：http://dali.svipenyu.cn/Article/details/gtnoiqumta.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.iojbl.cn/Article/details/gthzqqeqmi.html

[R05] 参数默认值
来源：http://dali.xylfe.cn/Article/details/gtlkxfqbiv.html

name="${1:-default}"
来源：http://dali.zhengqikj.top/Article/details/gtpgojegum.html

[R06] 判断命令是否存在
来源：http://dali.nwbrower.top/Article/details/gtgkpvwqix.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtvjklfbda.html

[R07] if 判断文件
来源：http://dali.aizwys.cn/Article/details/gtmyvstcdp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gtaayctakx.html

[R08] 数值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzkinrvb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gtneofxbkt.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtfvmdfwld.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gtvdhtijlv.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtioxtmrxt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shuidangran.top/Article/details/gtpvhuasoz.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gtrzzdyoss.html

case "$1" in
来源：http://dali.jlsjyb.cn/Article/details/gteswtysyo.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtgdmrluma.html

stop)  echo "停止" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtrqfrjbqp.html

*)     echo "未知命令" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpyiweej.html

esac
来源：http://dali.hnxiangtu.top/Article/details/gtxptpogrw.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gtojlelaep.html

for f in *.txt; do echo "$f"; done
来源：http://dali.316326.xyz/Article/details/gtotqkzbzr.html

[R13] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gtduxziepr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtbqfwcwdl.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gtwebqeqsk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gtrzvxyfpx.html

[R15] while 逐行读文件
来源：http://dali.ivvv.top/Article/details/gtnrsbtodt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.havefunace.top/Article/details/gtbfwrybef.html

[R16] until 等待条件
来源：http://dali.yuanzhike.top/Article/details/gtcpiiadjx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtaamzprag.html

[R17] 数组定义与取值
来源：http://dali.xinyue.icu/Article/details/gtsrcjjlnc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangdashe.top/Article/details/gtuuaylpwh.html

[R18] 遍历数组
来源：http://dali.c1oappe.top/Article/details/gtnjcsuwjk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.smart0.xyz/Article/details/gtdfnufaan.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtdyywlbnk.html

echo "${#arr[@]}"
来源：http://dali.yj20258888.top/Article/details/gtkkiwdfni.html

[R20] 关联数组（字典）
来源：http://dali.pengpengdd.cyou/Article/details/gtwpmpyjst.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jiagoushi.top/Article/details/gthoaaaipd.html

[R21] 字符串长度
来源：http://dali.sysykeji.top/Article/details/gttylqrgpp.html

echo "${#s}"
来源：http://dali.yuanzhike.top/Article/details/gtctpapapa.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gthfllhrsr.html

echo "${s:0:5}"
来源：http://dali.xziqi.cn/Article/details/gtewwxojjs.html

[R23] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtfexfklij.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gtdrcnzdoz.html

[R24] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gthbozjalx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gtidqrypfa.html

[R25] 去后缀 / 去前缀
来源：http://dali.fzhhl.top/Article/details/gttgkeffdx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gtxxkcrpgl.html

[R26] 命令替换
来源：http://dali.hysaishi.cn/Article/details/gtueewbnko.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gtmxlzumfs.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gttughkvrl.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gtplnnfxat.html

[R28] 浮点运算
来源：http://dali.316326.xyz/Article/details/gtuzdrczys.html

echo "scale=2; 10/3" | bc
来源：http://dali.gaohongyu789.top/Article/details/gtulbixoga.html

[R29] 定义函数
来源：http://dali.daxiang520.top/Article/details/gttchcjnbb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.svipenyu.cn/Article/details/gtigzeoimp.html

[R30] 函数返回状态码
来源：http://dali.gogol.net.cn/Article/details/gtkwaeogae.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gtqemdukrx.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwzvigab.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gtnhpgmznz.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gtsjssovvn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtjeewvhdw.html

[R33] 捕获错误并提示行号
来源：http://dali.aibaodan.cn/Article/details/gtldgangos.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.haohaochexian.top/Article/details/gtgjwrkndk.html

[R34] 退出时清理
来源：http://dali.iojbl.cn/Article/details/gtfoxunkhs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtsnxtiemf.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtfhkhyztj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtajgmym.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gtqqiedtes.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gtvbggsvau.html

[R37] 把输出赋给变量
来源：http://dali.jinqigufen.top/Article/details/gtlfzyspcp.html

files=$(ls -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvytjqmb.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gtoxggikgr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gtpygflkur.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gtvgvovstd.html

cmd > out.log 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gtrrpgdtoy.html

[R40] 追加写日志
来源：http://dali.xziqi.cn/Article/details/gtdqrwbypv.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gtbdxusvjw.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gtnoawjrnv.html

cmd >/dev/null 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfkakqce.html

[R42] 输入重定向
来源：http://dali.tian-w.cn/Article/details/gtxghpzunf.html

wc -l < a.txt
来源：http://dali.ehwqpu.com/Article/details/gtjtodheba.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtmdzkbahx.html

find . -name "*.log" -type f
来源：http://dali.tian-w.cn/Article/details/gtreklefvf.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gtwdzdjkdx.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gtfnriruhu.html

[R45] 批量删除
来源：http://dali.jinqigufen.top/Article/details/gtnngejovn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gtguxeeaxq.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gtbdcrqmlb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gtlrzphiaj.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gtrvpuwebt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.iojbl.cn/Article/details/gtexinkkoo.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gtiwqbatiw.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtytdwcxhk.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gtvdamnhko.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gtuexvyqny.html

[R50] awk 求和
来源：http://dali.redwolf501.top/Article/details/gtodngchgn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fzhhl.top/Article/details/gtbgjyvgfc.html

[R51] 排序去重取前几
来源：http://dali.cashguo.top/Article/details/gtzcnnwkdd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gthhijeubs.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gtthxlrsxk.html

wc -l a.txt
来源：http://dali.chenzaomai.com/Article/details/gtobvhjqyu.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gtsvfdkhdw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gtojztyuth.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gtzhlszthc.html

diff a.txt b.txt
来源：http://dali.yj20258.top/Article/details/gtaeucackb.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gtxxsikxce.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gtxzcuhzcx.html

[R56] 远程拷贝
来源：http://dali.smart0.xyz/Article/details/gtabajmbgx.html

scp file user@host:/path/
来源：http://dali.haohaochexian.top/Article/details/gtdobuvllz.html

[R57] 远程执行命令
来源：http://dali.chenzaomai.com/Article/details/gtcinoeaqj.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gtwqixxeuz.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gtsooewzmk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gtzhpuuffv.html

[R59] 发 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtvchwjglp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbpsxfoh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtkjknlvoj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gtvdarqfkf.html

[R61] 磁盘占用
来源：http://dali.jianghu66.top/Article/details/gtirsjdkql.html

df -h;  du -sh *
来源：http://dali.tanke756.top/Article/details/gtyfdmtyyo.html

[R62] 找最占空间的文件
来源：http://dali.zycfv.cn/Article/details/gtxmpxgund.html

du -ah . | sort -rh | head -10
来源：http://dali.birdmap.top/Article/details/gtzlrbxhwa.html

[R63] 内存与进程
来源：http://dali.bjfxy.top/Article/details/gtjtphmtdm.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gtwyvworgv.html

[R64] 结束进程
来源：http://dali.wangshuangyany.cn/Article/details/gtxibckqre.html

kill -9 $(pgrep -f app.py)
来源：http://dali.quarkkingdee.top/Article/details/gtqlcfroht.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gtgeqpofkl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.smart0.xyz/Article/details/gtddhmzapi.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gtxlpeeddv.html

crontab -e;  crontab -l
来源：http://dali.daxiang520.top/Article/details/gttedzwxyb.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gtsemwvogn.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gtsjolpnnw.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gtamzvzmpj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gtlmcmiued.html

[R69] 生成随机密码
来源：http://dali.yj202588.top/Article/details/gtwwlueozx.html

head -c 16 /dev/urandom | base64
来源：http://dali.ehwqpu.com/Article/details/gtsaudwake.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gtajgektgz.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gtqwjqhwan.html

[R71] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtbyrnhccp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gtvfnsbhse.html

[R72] 等待端口就绪
来源：http://dali.hfpthk.cn/Article/details/gtsgyhzrak.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtgxtviqsu.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gthrszxunf.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gtdmesbwwn.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnheurls.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gtbiwdgwfh.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gtieevrzat.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gtainsyvms.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gtelurzhmo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gttsvwhvpd.html

[R77] 读取用户输入
来源：http://dali.kuanghao11.cn/Article/details/gtfgkvcfbo.html

read -rp "请输入: " ans
来源：http://dali.jyoumei.cn/Article/details/gthhwixblg.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gtuuavdhfp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aizwys.cn/Article/details/gttlgkojez.html

[R79] 解析命令行选项
来源：http://dali.yj202588.top/Article/details/gtsvmjlbjx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gtoyglvzlu.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gtveruhupn.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gtcpvxepfx.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtszdctxys.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gtcbqhurdm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrxdzngwb.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtebcshacs.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gtbimzeczv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gtziqdlzoo.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gteuigokwx.html

int a = 10; printf("%d\n", a);
来源：http://dali.gzhubu.top/Article/details/gtpcgwijfd.html

[S03] C：读入整数
来源：http://dali.0kj1m.cn/Article/details/gttcjvvmeu.html

int x; scanf("%d", &x);
来源：http://dali.jinqigfzy.top/Article/details/gtesbtennc.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtgczfhgsl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gtbyczsmiz.html

[S05] C：字符串长度
来源：http://dali.cucudq.cn/Article/details/gtrcjzzcai.html

strlen(s)
来源：http://dali.snrcjt.cn/Article/details/gtucottdad.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlorjypt.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gtjzwvayrj.html

[S07] C：数组遍历求和
来源：http://dali.bjfxy.top/Article/details/gtumopgztn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gtfxlcnmso.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gtrdwvuccn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.smart0.xyz/Article/details/gtrvtmyejw.html

[S09] C：结构体定义与初始化
来源：http://dali.tian-w.cn/Article/details/gtnmgpfxsw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258888.top/Article/details/gtttzhhzbj.html

[S10] C：指针与解引用
来源：http://dali.nwbrower.top/Article/details/gttoybwqsz.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gtloeiuhca.html

[S11] C：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtxkugibeg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigfzy.top/Article/details/gtyuselrkm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yvedp.cn/Article/details/gtvqslbaxu.html

fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtidaqusuf.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtfcqlpaex.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtdzgixalo.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gtllbggpgf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ybcxt.top/Article/details/gtcodmhkho.html

[S14] C：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gthrziwquf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgufenzy.top/Article/details/gtqgmpjpli.html

[S15] C：类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcakhvqug.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gtewzgopwr.html

[S16] C：位操作置位
来源：http://dali.aizwys.cn/Article/details/gtrgqhoold.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gtguuvzshx.html

[S17] C：安全拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtttyegjzn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gtgnzdxpgc.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gtllrumgsv.html

int main(int argc, char **argv)
来源：http://dali.ppjwa.cn/Article/details/gttxhjbhrk.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gtvfikylxw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gteoxwucbp.html

[S20] C：二分查找
来源：http://dali.yangfankeji.com/Article/details/gtabsjpkdi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtsaaxsizl.html

[S21] C：字符类别判断
来源：http://dali.yuxming.cn/Article/details/gtxbyvuopg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tianlin.xyz/Article/details/gtkkajfevu.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gtqqdjyjqz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gtqvqtjzxp.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gtkonzlvre.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvztovdxw.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gtohketylw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.c1oappe.top/Article/details/gtaghtzatl.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtozxotqjg.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gtqouycayg.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gtwpabdeph.html

memset(a, 0, sizeof a);
来源：http://dali.gzhubu.top/Article/details/gtyehxyjqt.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gtyjpowynr.html

const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtczwxfzeg.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gtiqutlbtx.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrdxqpzb.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gtvwtuvkgj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gtqrnrmqmq.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gtdzpnpnqs.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gtbvqfsvux.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gtoznlrmps.html

#endif
来源：http://dali.cucudq.cn/Article/details/gtziwmpxwg.html

[S31] C++：Hello World
来源：http://dali.hammf.cn/Article/details/gtrgvftfka.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gtmxexmscv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvacejge.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gtdvdadaeo.html

std::string s = "hi";  s += "!";
来源：http://dali.xinyue.icu/Article/details/gtfbhvupdz.html

[S33] C++：vector 增删
来源：http://dali.kuanghao11.cn/Article/details/gtpbmmgyrw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sxryk.cn/Article/details/gtgsyvktrq.html

[S34] C++：遍历 vector
来源：http://dali.yj202588.top/Article/details/gtprlvkznh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfyafvukt.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtvsepzjgm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtmfvkjqsd.html

[S36] C++：unordered_map
来源：http://dali.zdqjudy.top/Article/details/gtkfpeqljm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtlgssfikj.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtbsaasnnf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gttiraktai.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gtuhzvbtsf.html

std::sort(v.begin(), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtextewsdr.html


<!-- 参考信息 -->