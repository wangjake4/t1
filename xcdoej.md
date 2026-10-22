代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gt2lslrvmgf.html

[Q69] 查看执行计划
来源：http://dali.wangshuangyany.cn/Article/details/gt2togmpxfs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.0kj1m.cn/Article/details/gt2dyaanrsg.html

[Q70] 更新统计信息
来源：http://dali.cucudq.cn/Article/details/gt2yymqhbwu.html

ANALYZE TABLE users;
来源：http://dali.fengsongda.top/Article/details/gt2pipajulf.html

[Q71] 查看建表语句
来源：http://dali.xylfe.cn/Article/details/gt2lpqjcpxh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhixingplan.top/Article/details/gt2swjajslj.html

[Q72] 查看索引
来源：http://dali.tian-w.cn/Article/details/gt2cysbkhys.html

SHOW INDEX FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2fbvfszme.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gt2lvnxlrjg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gt2slhmnbdy.html

[Q74] 强制使用索引
来源：http://dali.chenlongwang.top/Article/details/gt2aaaoveka.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwnkwyul.html

[Q75] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2tzyeehna.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2kflvgnzj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jianghu66.top/Article/details/gt2usfqpvjv.html

[Q76] 按天统计
来源：http://dali.birdmap.top/Article/details/gt2xmyqflbh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gt2efafwqwo.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gt2danhnqms.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dricgare.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gt2moudoyor.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ybcxt.top/Article/details/gt2bhdhorua.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gt2ntxzffcv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cdnleiting.top/Article/details/gt2dflzrbin.html

[Q80] 字符串截取
来源：http://dali.meibo888.top/Article/details/gt2domgrnhg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2yubkkxlg.html

[Q81] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gt2cbukfzig.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2olfgenxr.html

[Q82] 字符长度与字节长度
来源：http://dali.nwbrower.top/Article/details/gt2euaiovvw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixgwqtum.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gt2yfqfskqc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2rgwunymn.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gt2ojfnhzfs.html

SELECT TRIM(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hefneawz.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gt2gqdoyqmv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gt2falqjseu.html

[Q86] 读取 JSON 字段
来源：http://dali.shuidangran.top/Article/details/gt2gvioksgu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gt2yahzyqbr.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gt2kbaruzyd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gt2joxsauzn.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gt2nohgwiwc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxhwrfdw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2mtikvkmp.html

[Q89] 判断表是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2gmgvmtlb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ivvv.top/Article/details/gt2vbfclfql.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gt2reirdzfb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigfzy.top/Article/details/gt2vgfgatlg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ciwbgcbg.html

R. Bash 专题
来源：http://dali.tanke756.top/Article/details/gt2oshiknff.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2oyzzqybt.html

[R01] shebang 与严格模式
来源：http://dali.wangdashe.top/Article/details/gt2hpfhbcxv.html

#!/usr/bin/env bash
来源：http://dali.jyoumei.cn/Article/details/gt2zjvhplnn.html

set -euo pipefail
来源：http://dali.birdmap.top/Article/details/gt2okjdnaej.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gt2odubzavl.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gt2qvcflclu.html

[R03] 只读变量
来源：http://dali.jinqigufen.top/Article/details/gt2kvpgvsxt.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gt2kjjyblpr.html

[R04] 位置参数
来源：http://dali.ybcxt.top/Article/details/gt2lgwmypgl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xinyue.icu/Article/details/gt2iftffhbq.html

[R05] 参数默认值
来源：http://dali.daxiang520.top/Article/details/gt2itmsrqcr.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gt2qtcosnia.html

[R06] 判断命令是否存在
来源：http://dali.guannengcc.top/Article/details/gt2kecwohpb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gt2paezyzep.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwurdcyq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2fhlysvom.html

[R08] 数值比较
来源：http://dali.birdmap.top/Article/details/gt2yxcaibld.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgtoydrl.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gt2xnljbuoj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gt2rqxeesyl.html

[R10] 正则匹配
来源：http://dali.sufxvd.cn/Article/details/gt2drzboudu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gt2zpjuxagf.html

[R11] case 多分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2necmymfe.html

case "$1" in
来源：http://dali.ppjwa.cn/Article/details/gt2uviamrlz.html

start) echo "启动" ;;
来源：http://dali.ivvv.top/Article/details/gt2llpnzacr.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gt2fpsvirjv.html

*)     echo "未知命令" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jzstvxgy.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kojczdhq.html

[R12] for 遍历文件
来源：http://dali.yueranfly.top/Article/details/gt2acbsblmc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2vlpitkrh.html

[R13] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2ladwranc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gt2phitbeml.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gt2twplhrbf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2swctimko.html

[R15] while 逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2zmecqijw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gt2madhxycc.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gt2mazaewvw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2hmumptut.html

[R17] 数组定义与取值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nanuifzc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wavtutje.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gt2etbbirew.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2jurwkzqe.html

[R19] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gt2sugestbu.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gt2npgbxdap.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gt2hvveorfa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guannengcc.top/Article/details/gt2uhfolwcx.html

[R21] 字符串长度
来源：http://dali.tianlin.xyz/Article/details/gt2kkwajqau.html

echo "${#s}"
来源：http://dali.sweek.top/Article/details/gt2chdlvqxm.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gt2ikihamff.html

echo "${s:0:5}"
来源：http://dali.zycfv.cn/Article/details/gt2bzejziem.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gt2jvocyymr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gt2zyjxxvhb.html

[R24] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gt2cpqlqryv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gt2eqwheneh.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258.top/Article/details/gt2xpysmijv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gt2zrikbgng.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gt2amlgwfwn.html

now=$(date +%F); echo "$now"
来源：http://dali.c1oappe.top/Article/details/gt2aptbbenz.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gt2fqboijwi.html

echo $((1 + 2 * 3))
来源：http://dali.pycfn.com/Article/details/gt2vanotljw.html

[R28] 浮点运算
来源：http://dali.quarkkingdee.top/Article/details/gt2ygtonrfz.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258.top/Article/details/gt2esdqwdic.html

[R29] 定义函数
来源：http://dali.yonumen.top/Article/details/gt2hppgflxx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gt2lvdmkknb.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gt2ixdxjqdf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jyoumei.cn/Article/details/gt2uuhidqrs.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gt2kwdvrmka.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gt2ekpxikhd.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gt2xjgyszpw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gt2joomrriz.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gt2subnqdjv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.iojbl.cn/Article/details/gt2clcfrqtv.html

[R34] 退出时清理
来源：http://dali.pycfn.com/Article/details/gt2vlxmcvej.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gt2emmzpbet.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gt2qvjbuckw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cucudq.cn/Article/details/gt2gnmuhnsi.html

[R36] 并发执行多个任务
来源：http://dali.smart0.xyz/Article/details/gt2hxecstiv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.svipenyu.cn/Article/details/gt2admogace.html

[R37] 把输出赋给变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jygpwkxp.html

files=$(ls -1)
来源：http://dali.guowangkeji.top/Article/details/gt2fsvqwsjl.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gt2bgbikjxa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pycfn.com/Article/details/gt2obsmomwl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2buabmxfj.html

cmd > out.log 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eajlgsac.html

[R40] 追加写日志
来源：http://dali.yj202588.top/Article/details/gt2xlvixkjb.html

echo "log" >> out.log
来源：http://dali.zdqjudy.top/Article/details/gt2lgoldzos.html

[R41] 丢弃输出
来源：http://dali.chenlongwang.top/Article/details/gt2eabwqpus.html

cmd >/dev/null 2>&1
来源：http://dali.meibo888.top/Article/details/gt2dusmxwxx.html

[R42] 输入重定向
来源：http://dali.ybcxt.top/Article/details/gt2excicwkp.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gt2zglouxcu.html

[R43] 按名字查找文件
来源：http://dali.jlsjyb.cn/Article/details/gt2bpfemmmx.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gt2cwdqwnhi.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gt2wfldljdx.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gt2gsccmxwy.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnwyhofv.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdqkkgci.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gt2otodarpc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ivvv.top/Article/details/gt2awhztper.html

[R47] sed 单行替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2govaktwq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258888.top/Article/details/gt2asvqmvxh.html

[R48] awk 取指定列
来源：http://dali.yuxming.cn/Article/details/gt2pirqdify.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2svzukohd.html

[R49] awk 带条件
来源：http://dali.gotoacloud.top/Article/details/gt2aiogftcs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxinkj.top/Article/details/gt2eejiioie.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gt2lvbkegdd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2pnqqxlmw.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gt2xbybbqjk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gt2aaonjuis.html

[R52] 统计行数
来源：http://dali.aizwys.cn/Article/details/gt2inqycfwl.html

wc -l a.txt
来源：http://dali.xylfe.cn/Article/details/gt2tcywnuzh.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gt2buzgajpj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hfpthk.cn/Article/details/gt2sudjxahr.html

[R54] 比较两个文件
来源：http://dali.xinyue.icu/Article/details/gt2vzmjriyv.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gt2mhefyvyw.html

[R55] 压缩与解压
来源：http://dali.ybcxt.top/Article/details/gt2wsrqnvwd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gt2uckbshwp.html

[R56] 远程拷贝
来源：http://dali.iojbl.cn/Article/details/gt2fwdrkyod.html

scp file user@host:/path/
来源：http://dali.daxiang520.top/Article/details/gt2msjrjgzd.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gt2rsyrmhyb.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmtkmpbo.html

[R58] 下载文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2quqttqqu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuanzx.com/Article/details/gt2aklksmkw.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gziepodi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jlsjyb.cn/Article/details/gt2uukczfkb.html

[R60] 只看 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gt2dlwyxxzi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gt2ipirfjhl.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2unncuzru.html

df -h;  du -sh *
来源：http://dali.guowangkeji.top/Article/details/gt2wnocddhi.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsvpkwud.html

du -ah . | sort -rh | head -10
来源：http://dali.svipenyu.cn/Article/details/gt2xaoxlrdw.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gt2skpbgxsy.html

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gt2ahzmfygh.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gt2xtpldqiv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gt2bwswcsjf.html

[R65] 查看端口占用
来源：http://dali.pycfn.com/Article/details/gt2nzyejigk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ydzc1.top/Article/details/gt2secdwpgo.html

[R66] 定时任务
来源：http://dali.kuanghao11.cn/Article/details/gt2epoqazpl.html

crontab -e;  crontab -l
来源：http://dali.dashuyun.cn/Article/details/gt2zygfrasz.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gt2uladizfq.html

openssl rand -hex 16
来源：http://dali.c1oappe.top/Article/details/gt2tpjddagb.html

[R68] 计算文件校验值
来源：http://dali.jinqigfzy.top/Article/details/gt2strptdfe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2xssvhpnv.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kznvfoww.html

head -c 16 /dev/urandom | base64
来源：http://dali.hongshengwenyu.top/Article/details/gt2lphfdgym.html

[R70] 时间戳与互转
来源：http://dali.wangdashe.top/Article/details/gt2vqldllzk.html

date +%s;  date -d @1700000000
来源：http://dali.tanke756.top/Article/details/gt2awylrmhy.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gt2yfgiqbqs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnqzz.top/Article/details/gt2wbezbwwi.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qavycjzm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gt2zfduerqq.html

[R73] 分割大日志
来源：http://dali.yuxming.cn/Article/details/gt2rukwmnby.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gt2xocbnfwv.html

[R74] 批量重命名
来源：http://dali.sweek.top/Article/details/gt2qomrutca.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenzaomai.com/Article/details/gt2sysxwndl.html

[R75] 导出环境变量
来源：http://dali.jqgufenzy.top/Article/details/gt2khhfmmyh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hammf.cn/Article/details/gt2cjykcuqq.html

[R76] 使用临时文件
来源：http://dali.nanxinkj.top/Article/details/gt2ufusagfg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gt2wchnnhfq.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gt2txiwgjou.html

read -rp "请输入: " ans
来源：http://dali.yueranfly.top/Article/details/gt2ispiywcw.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gt2tomdxepz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gt2gdscnecj.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2cdlnglpt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jlsjyb.cn/Article/details/gt2cctqgxuo.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gt2oncljhuv.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gt2nfwjqfid.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2vidtprag.html

S. C / C++ 专题
来源：http://dali.0kj1m.cn/Article/details/gt2bmokiwxq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2tssuvtkm.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gt2fymjdkku.html

#include <stdio.h>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hybbkhqs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gt2szddtczm.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gt2szdqhrme.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gt2pjzrshdo.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gt2tmrusdld.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gt2oicwttjz.html

[S04] C：字符串复制
来源：http://dali.zhengqikj.top/Article/details/gt2pinmondk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2mqrxdidk.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gt2txvcptoz.html

strlen(s)
来源：http://dali.iojbl.cn/Article/details/gt2rpkcuwaq.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gt2mwdjinqn.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gt2coprcigv.html

[S07] C：数组遍历求和
来源：http://dali.yj20258888.top/Article/details/gt2jzeqfouz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj202588.top/Article/details/gt2ukocwuzq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gt2qauelbap.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gt2yqrjjmsu.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxinkj.top/Article/details/gt2dipwkvkj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnxiangtu.top/Article/details/gt2ardajeym.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gt2mpbycdsz.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gt2hurddpjc.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qdpqfzpj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gt2czfgpekl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfsgvrcy.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2wlfobaat.html

[S12] C：写文件
来源：http://dali.gotoacloud.top/Article/details/gt2eodsomup.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhckxtqm.html

[S13] C：宏定义
来源：http://dali.sufxvd.cn/Article/details/gt2vpkufrte.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gt2kddtiync.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gt2fhfcbzoh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gt2arlipajr.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gt2ownfvvtv.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gt2rusfapph.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gt2lhgfxwtl.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gt2louttvif.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gt2dmdhslbw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gt2rpmvkluw.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gt2tcnbnusf.html

int main(int argc, char **argv)
来源：http://dali.yj20258888.top/Article/details/gt2oylgzssc.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gt2okvtrhha.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2pqjshhbg.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gt2utmogelz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2dxqxwqpv.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gt2taapmyvw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlapvumh.html

[S22] C：字符串转数字
来源：http://dali.tanke756.top/Article/details/gt2mumnxvlh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pycfn.com/Article/details/gt2aayscyyr.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gt2voppphab.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gt2okotumnn.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gt2uymxuixh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shuidangran.top/Article/details/gt2qiclmlfy.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2kkwtuzjf.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gt2umlftcum.html

[S26] C：内存清零
来源：http://dali.hywenlv.cn/Article/details/gt2esufhgqb.html

memset(a, 0, sizeof a);
来源：http://dali.fengsongda.top/Article/details/gt2ibhohzlb.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gt2suorhwnp.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2fvfwdnxl.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gt2zizpjxav.html

static int counter = 0;
来源：http://dali.hammf.cn/Article/details/gt2vytkeuzv.html

[S29] C：变参函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkstsshl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.iojbl.cn/Article/details/gt2cmglbrlg.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gt2luomjhfa.html

#ifndef X_H
来源：http://dali.yj20258888.top/Article/details/gt2caiesbce.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gt2zlukzfyk.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gt2eacfhgex.html

[S31] C++：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2thmfexjd.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gt2cmmsjiyt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xinyue.icu/Article/details/gt2npymxabp.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2guyeyawl.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gt2uytovvvg.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gt2pgmbgygt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gt2jvmuvqml.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2syvjhhye.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gt2xizneloy.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gt2hmpfkivn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2dlomjfqk.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkmgpiwn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2oubiwnxl.html

[S37] C++：set
来源：http://dali.sysykeji.top/Article/details/gt2vwabgqsk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.mhx1999.top/Article/details/gt2uaalgfoh.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gt2gqwxvmvj.html

std::sort(v.begin(), v.end());
来源：http://dali.ppjwa.cn/Article/details/gt2fcuehdhq.html


<!-- 参考信息 -->