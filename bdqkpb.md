代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.smart0.xyz/Article/details/gtwivnedga.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtqnnkmaqq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gthrrgucnz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gtmftkqfnb.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gtiymepyce.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ehwqpu.com/Article/details/gtfqlgseuu.html

[Q77] 时间加减
来源：http://dali.zhoulong.xyz/Article/details/gtpbfwergy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nwbrower.top/Article/details/gtvqyqacns.html

[Q78] 当前时间
来源：http://dali.sweek.top/Article/details/gtmpouzbqu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gtgpbmwlqn.html

[Q79] 字符串拼接
来源：http://dali.yj20258888.top/Article/details/gtvwwdvtqv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sufxvd.cn/Article/details/gttrqrcdbr.html

[Q80] 字符串截取
来源：http://dali.jiagoushi.top/Article/details/gtslafdoba.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtpkutggro.html

[Q81] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gtxtevgmmj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gtyrqbhqpm.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gttwexdjxu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtfpqglzdo.html

[Q83] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtwvmidfvm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtoilpcstc.html

[Q84] 去除首尾空格
来源：http://dali.jianghu66.top/Article/details/gtsguiuzkj.html

SELECT TRIM(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtjwzbmmdr.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gtrhfjvffo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenjidiqi.icu/Article/details/gtwulwcfyi.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gtnfpmosph.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gtdhmwpfce.html

[Q87] JSON 字段做条件
来源：http://dali.0kj1m.cn/Article/details/gtqrehfwct.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gtyhrzrnpw.html

[Q88] 行转列（条件聚合）
来源：http://dali.gogol.net.cn/Article/details/gtddtiqixf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhiwuduotai.top/Article/details/gtcdnmsrri.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tian-w.cn/Article/details/gtqpghijvu.html

[Q89] 判断表是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdeubokj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ppjwa.cn/Article/details/gthceaoyyx.html

[Q90] 生成序号列
来源：http://dali.aibaodan.cn/Article/details/gtwoxuiyiz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gtgsbcfinz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtbochlzsd.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gtktkxuuog.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtibkxjpzj.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gtgwjxqgce.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gtzibsghbc.html

set -euo pipefail
来源：http://dali.xinyue.icu/Article/details/gtfxmjyurn.html

[R02] 变量赋值与使用
来源：http://dali.yonumen.top/Article/details/gtoouuyevq.html

name="Tom"; echo "$name"
来源：http://dali.daria6918.cn/Article/details/gtocwcssrv.html

[R03] 只读变量
来源：http://dali.hysaishi.cn/Article/details/gtkblbkeui.html

readonly PI=3.14
来源：http://dali.hysaishi.cn/Article/details/gtzrmslpju.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gtypnydqje.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yueranfly.top/Article/details/gtuqxewhzf.html

[R05] 参数默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzfihglr.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gtqsxijcmq.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gtbeadtxce.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gtjjgadbmh.html

[R07] if 判断文件
来源：http://dali.wangshuangyany.cn/Article/details/gtebzyybqu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gttvxcbvdn.html

[R08] 数值比较
来源：http://dali.yj20258888.top/Article/details/gteuoseyhk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpthedlv.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtxotzbati.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhixingplan.top/Article/details/gtgpcjfwaq.html

[R10] 正则匹配
来源：http://dali.chenzaomai.com/Article/details/gtkzlvaqwx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shuidangran.top/Article/details/gtyadltxmq.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gttpaymogx.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gtjydnooww.html

start) echo "启动" ;;
来源：http://dali.fzhhl.top/Article/details/gtukmyidqp.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gtzxkcnpjj.html

*)     echo "未知命令" ;;
来源：http://dali.havefunace.top/Article/details/gtdptaclkb.html

esac
来源：http://dali.c1oappe.top/Article/details/gtshtjtidk.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gtevsynqrc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.andypj.xyz/Article/details/gtuwkosmin.html

[R13] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gthlhyetvb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtmobmwzli.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gtzcsjnrsw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gtbofatddf.html

[R15] while 逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtmbkfaxhv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gtczaldiwx.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gtuqdrkbvg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtlqshxejv.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gtbdfohizl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sysykeji.top/Article/details/gtgjkqrzxd.html

[R18] 遍历数组
来源：http://dali.c1oappe.top/Article/details/gtqfwqlryo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gtbhrsysfg.html

[R19] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtpjebkuau.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gtunizyywr.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gtawacrvus.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yvedp.cn/Article/details/gtaxfowflg.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gtmvpwygav.html

echo "${#s}"
来源：http://dali.tianlin.xyz/Article/details/gtvzcywygy.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtoatukbuv.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gtyhhnmnhv.html

[R23] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtpoxwvghp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gtfjjyezgk.html

[R24] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtraktvgti.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gtvlcgqnzp.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gtmznbqvyx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zycfv.cn/Article/details/gtzvfkadrh.html

[R26] 命令替换
来源：http://dali.zdqjudy.top/Article/details/gtocjangkt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhixingplan.top/Article/details/gtkamcgjuy.html

[R27] 算术展开
来源：http://dali.nanxinkj.top/Article/details/gtedqwzjbz.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gtayelgqxw.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuvjlrow.html

echo "scale=2; 10/3" | bc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfuzusvp.html

[R29] 定义函数
来源：http://dali.zycfv.cn/Article/details/gthkksgamy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yonumen.top/Article/details/gtszpijlsn.html

[R30] 函数返回状态码
来源：http://dali.dianchejie.cn/Article/details/gtkahydaqp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gtrmznynvd.html

[R31] 局部变量
来源：http://dali.mhx1999.top/Article/details/gtqsxosvww.html

f() { local x=1; echo "$x"; }
来源：http://dali.xziqi.cn/Article/details/gtufcjoslh.html

[R32] 参数个数校验
来源：http://dali.yangfankeji.com/Article/details/gtzcehritv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gtlixataau.html

[R33] 捕获错误并提示行号
来源：http://dali.hnqzz.top/Article/details/gtxxytnxtk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gtfjhkhasa.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gtaixpqbfu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtqrzcetzm.html

[R35] 后台执行并等待
来源：http://dali.aibaodan.cn/Article/details/gtdhpqpvyc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jianghu66.top/Article/details/gthflczhhp.html

[R36] 并发执行多个任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbycunyhg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gttrzsfjvo.html

[R37] 把输出赋给变量
来源：http://dali.jyoumei.cn/Article/details/gtzaxfcndp.html

files=$(ls -1)
来源：http://dali.hysaishi.cn/Article/details/gtjdfifvcu.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gtewicnpwh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhengqikj.top/Article/details/gtpxvwksdo.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gtssdaizhv.html

cmd > out.log 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtidsflsda.html

[R40] 追加写日志
来源：http://dali.yonumen.top/Article/details/gtglxtxlec.html

echo "log" >> out.log
来源：http://dali.cucudq.cn/Article/details/gtjrnezysc.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgrdkgvt.html

cmd >/dev/null 2>&1
来源：http://dali.ivvv.top/Article/details/gtlnahekzx.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gtdpzmmzdm.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gtcsrzlstm.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gthqvqbmnn.html

find . -name "*.log" -type f
来源：http://dali.guannengcc.top/Article/details/gthdmeirjz.html

[R44] 按修改时间查找
来源：http://dali.bjfxy.top/Article/details/gtshequoko.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gtgfcofirj.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyfltwfo.html

find . -name "*.tmp" -delete
来源：http://dali.hnqzz.top/Article/details/gtteijebnc.html

[R46] 递归替换文件内容
来源：http://dali.tian-w.cn/Article/details/gtjpxoserc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.vqdsnc.cn/Article/details/gtqqhespkr.html

[R47] sed 单行替换
来源：http://dali.mhx1999.top/Article/details/gtkkfcibwu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtyxgiwwwu.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gteyzmuhum.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtoizoivjd.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gtelaspsjn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ehwqpu.com/Article/details/gtlssbxmtl.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gtgoumskmq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gtgrhshkhe.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gtheqxcrdx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cashguo.top/Article/details/gtydkjwbvf.html

[R52] 统计行数
来源：http://dali.shangyingyoupin.top/Article/details/gtcvkipogl.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gtszxozjrl.html

[R53] 查看文件头与实时尾
来源：http://dali.dashuyun.cn/Article/details/gtropcpqgd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nwbrower.top/Article/details/gtmkgfkceu.html

[R54] 比较两个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtvzlzfvew.html

diff a.txt b.txt
来源：http://dali.smart0.xyz/Article/details/gtzqfhqmlj.html

[R55] 压缩与解压
来源：http://dali.nanxinkj.top/Article/details/gtoccaajne.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gtwndbssfx.html

[R56] 远程拷贝
来源：http://dali.jianghu66.top/Article/details/gtafsvjxzx.html

scp file user@host:/path/
来源：http://dali.aibaodan.cn/Article/details/gtvswjuiyv.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gtbewxapqj.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gtmivynjpy.html

[R58] 下载文件
来源：http://dali.wangshuangyany.cn/Article/details/gtpsrwucaj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gtouwfctum.html

[R59] 发 POST JSON
来源：http://dali.mhx1999.top/Article/details/gtltdoztjp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhixingplan.top/Article/details/gtqnkhgprl.html

[R60] 只看 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtpomfsqui.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgufenzy.top/Article/details/gtultpycve.html

[R61] 磁盘占用
来源：http://dali.cqqwz.cn/Article/details/gtigkutege.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzlnjeac.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gttcbzxfhj.html

du -ah . | sort -rh | head -10
来源：http://dali.yuxming.cn/Article/details/gtzmsbcwge.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gtjpkkyrdf.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsbppbmu.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gtiavktzfj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gttfuisjgm.html

[R65] 查看端口占用
来源：http://dali.ydzc1.top/Article/details/gtpsxdgmfd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xinyue.icu/Article/details/gtlsuinqsc.html

[R66] 定时任务
来源：http://dali.andypj.xyz/Article/details/gtcjctfpnz.html

crontab -e;  crontab -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhsmighi.html

[R67] 生成随机十六进制串
来源：http://dali.chenlongwang.top/Article/details/gthqndwslj.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gtfidjixag.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gtxdpchyxr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gtceaecmxm.html

[R69] 生成随机密码
来源：http://dali.yj202588.top/Article/details/gteplqywoj.html

head -c 16 /dev/urandom | base64
来源：http://dali.aizwys.cn/Article/details/gtpvdzalnn.html

[R70] 时间戳与互转
来源：http://dali.smart0.xyz/Article/details/gteydegigt.html

date +%s;  date -d @1700000000
来源：http://dali.fzhhl.top/Article/details/gtaszqzuzk.html

[R71] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtduasrdhy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtlcwwdxwa.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtjqzhrnpj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gtssiruzab.html

[R73] 分割大日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpgirlbj.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtgaiyjfyh.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdzknsgw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yongpay.top/Article/details/gtgdmwnbyg.html

[R75] 导出环境变量
来源：http://dali.ehwqpu.com/Article/details/gtmikugprw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ydzc1.top/Article/details/gtqqcdagqv.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gtpfogvjpo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gtxmxkvsdw.html

[R77] 读取用户输入
来源：http://dali.cdnleiting.top/Article/details/gtaktjhpnh.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gtojrfpepm.html

[R78] 交互式菜单
来源：http://dali.zycfv.cn/Article/details/gtkdlsdljr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtxmmysgye.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gtislyyvrt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gtkpjokdpl.html

[R80] 查看脚本执行耗时
来源：http://dali.snrcjt.cn/Article/details/gtourawcld.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gtiaapexzm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtaufqfrzc.html

S. C / C++ 专题
来源：http://dali.nanxuanxn.top/Article/details/gtlizhyori.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtwhhpyarf.html

[S01] C：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gthovqijgn.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gtykhnklmu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gtqjhwtmoo.html

[S02] C：变量与格式化输出
来源：http://dali.svipenyu.cn/Article/details/gttljkilyl.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtavdsnobp.html

[S03] C：读入整数
来源：http://dali.aibaodan.cn/Article/details/gtsfvdncby.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gthegipnbe.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gteytjneko.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxrsbxao.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gtzyguzrcg.html

strlen(s)
来源：http://dali.jlsjyb.cn/Article/details/gtsfyuishc.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gtotcmrxmv.html

strcmp(a, b) == 0
来源：http://dali.xziqi.cn/Article/details/gtdhbitawv.html

[S07] C：数组遍历求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdycxnel.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dianchejie.cn/Article/details/gtvuibbxkm.html

[S08] C：动态内存分配与释放
来源：http://dali.haohaochexian.top/Article/details/gtrlitlwbf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jyoumei.cn/Article/details/gtnvboohfp.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmtybmyj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hywenlv.cn/Article/details/gtjdfdmjki.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgebxricm.html

int *p = &a;  *p = 5;
来源：http://dali.redwolf501.top/Article/details/gtibrplmbx.html

[S11] C：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtkakoxjuc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gteuokxqhq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtvivolple.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtzelylipw.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtwdfedkye.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtfhjmvdvx.html

[S13] C：宏定义
来源：http://dali.yanxiufei.cn/Article/details/gtrqpqyimk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.mhx1999.top/Article/details/gtbuaysppz.html

[S14] C：枚举
来源：http://dali.hnxiangtu.top/Article/details/gttnstjgwu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gteqkwxybu.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gtprnvxceg.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gtlpxasukv.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gtvdfitqsk.html

x |= (1 << 3);
来源：http://dali.jiagoushi.top/Article/details/gtlkhhnjrz.html

[S17] C：安全拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwrzgtoo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yongpay.top/Article/details/gttvqjaoay.html

[S18] C：命令行参数
来源：http://dali.hysaishi.cn/Article/details/gtckxlfzbe.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gtrajshqar.html

[S19] C：快速排序
来源：http://dali.zycfv.cn/Article/details/gtawjrzfns.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gteufeszlv.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gtojspkizm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtfzstqqvw.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopeuvayl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gtyxyyqtwx.html

[S22] C：字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gtaufttbvr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258.top/Article/details/gtyywnpnpx.html

[S23] C：随机数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvnuneni.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hywenlv.cn/Article/details/gtklhswqwd.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gtbrswqmyy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gtgzgjozuz.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gtdtzahgfg.html

memcpy(dst, src, n);
来源：http://dali.yvedp.cn/Article/details/gtpsnyssaj.html

[S26] C：内存清零
来源：http://dali.jianghu66.top/Article/details/gtwqadlifh.html

memset(a, 0, sizeof a);
来源：http://dali.xziqi.cn/Article/details/gtbwlrwtii.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gtzpchazwo.html

const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtwxaftfmv.html

[S28] C：静态变量
来源：http://dali.chenzaomai.com/Article/details/gtkbgumiqc.html

static int counter = 0;
来源：http://dali.yvedp.cn/Article/details/gtqnroozjo.html

[S29] C：变参函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunbzkkxp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hfpthk.cn/Article/details/gtaohaxrvm.html

[S30] C：头文件保护
来源：http://dali.yonumen.top/Article/details/gtenbzwybd.html

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtfktfkkrd.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gthrweditm.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gthwjgcvxq.html

[S31] C++：Hello World
来源：http://dali.mhx1999.top/Article/details/gtzkpsbkjl.html

#include <iostream>
来源：http://dali.fengsongda.top/Article/details/gtfksvpydy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.meibo888.top/Article/details/gtbjbxppza.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gtqqjkctvn.html

std::string s = "hi";  s += "!";
来源：http://dali.ybcxt.top/Article/details/gtlldqxjlv.html

[S33] C++：vector 增删
来源：http://dali.zycfv.cn/Article/details/gtkhoibwcy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpwlitvy.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gtqgfpyoey.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gtindhooey.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gtsfzvyjjg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtbvykyzog.html

[S36] C++：unordered_map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpltwmwin.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtivjrymhm.html

[S37] C++：set
来源：http://dali.ivvv.top/Article/details/gtqpdwdapa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gtwwgcvome.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwsmprqi.html

std::sort(v.begin(), v.end());
来源：http://dali.sysykeji.top/Article/details/gtyaqxzxxh.html

[S39] C++：自定义比较器排序
来源：http://dali.tianlin.xyz/Article/details/gtrbxosdqm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gtzwsvjonk.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gtoxqwdnaf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gtqsdljuvm.html

[S41] C++：类与构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtoqtemjvn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafwhmxua.html

[S42] C++：继承与虚函数
来源：http://dali.haohaochexian.top/Article/details/gthoqagzwt.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gtjsuluuxg.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gtjpqztlsb.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgufenzy.top/Article/details/gtfvnysfdo.html

[S44] C++：引用传参
来源：http://dali.bjfxy.top/Article/details/gtbgtxzoul.html

void inc(int &x) { ++x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxkbfyjh.html


<!-- 参考信息 -->