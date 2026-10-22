代发 wailian999

[Q80] 字符串截取
来源：http://dali.wangshuangyany.cn/Article/details/gt2omueehej.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2jelvdtjb.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gt2wjukbbxg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2aztwljym.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gt2ttycznva.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2icgursku.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gt2naostyfe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2fswwvisn.html

[Q84] 去除首尾空格
来源：http://dali.hnxiangtu.top/Article/details/gt2kyolfadk.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2jeyfcqly.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gt2rmsikvqr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gotoacloud.top/Article/details/gt2gegosqxl.html

[Q86] 读取 JSON 字段
来源：http://dali.wangshuangyany.cn/Article/details/gt2bdcgvuzz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gt2pngeebtd.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gt2lrdhsoir.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hammf.cn/Article/details/gt2gwndxpgl.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gt2sehsjzdr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytfbungf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2fvkanddz.html

[Q89] 判断表是否存在
来源：http://dali.snrcjt.cn/Article/details/gt2bjixbzqw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.meibo888.top/Article/details/gt2bzvjijzm.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfffxwrf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gt2nwmvgcua.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2impxbtwl.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gt2peptiqui.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2cgfnjqwt.html

[R01] shebang 与严格模式
来源：http://dali.quarkkingdee.top/Article/details/gt2pcsdglxo.html

#!/usr/bin/env bash
来源：http://dali.chenlongwang.top/Article/details/gt2svzfissw.html

set -euo pipefail
来源：http://dali.ydzc1.top/Article/details/gt2jogzqigh.html

[R02] 变量赋值与使用
来源：http://dali.haohaochexian.top/Article/details/gt2xbzjznyn.html

name="Tom"; echo "$name"
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdtrbhax.html

[R03] 只读变量
来源：http://dali.ehwqpu.com/Article/details/gt2abljpoto.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gt2tueswnuq.html

[R04] 位置参数
来源：http://dali.dashuyun.cn/Article/details/gt2jxxgqbjq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xinyue.icu/Article/details/gt2ibbyhlxw.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gt2caytrufe.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gt2fnsmgsts.html

[R06] 判断命令是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofcwihzt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gt2pbcwzvyy.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gt2jxnomttk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.smart0.xyz/Article/details/gt2oxxqquyf.html

[R08] 数值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwodvkbx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2vjjeavor.html

[R09] 字符串比较
来源：http://dali.fengsongda.top/Article/details/gt2szpzexno.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guowangkeji.top/Article/details/gt2orkrscsm.html

[R10] 正则匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2qbqziefj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guowangkeji.top/Article/details/gt2mlhxvekd.html

[R11] case 多分支
来源：http://dali.shuidangran.top/Article/details/gt2dmjkuxbs.html

case "$1" in
来源：http://dali.jlsjyb.cn/Article/details/gt2aehgvbsi.html

start) echo "启动" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gt2werfscqt.html

stop)  echo "停止" ;;
来源：http://dali.yongpay.top/Article/details/gt2oqsbzasf.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ysksaogc.html

esac
来源：http://dali.ybcxt.top/Article/details/gt2hijtfogu.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gt2igcqfzdv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258.top/Article/details/gt2geltoxin.html

[R13] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gt2fxnqhyed.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2lrcpgpnz.html

[R14] C 风格 for
来源：http://dali.sysykeji.top/Article/details/gt2vxirjxem.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2hndxnpif.html

[R15] while 逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2gxtamkgd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxinkj.top/Article/details/gt2bzotppot.html

[R16] until 等待条件
来源：http://dali.dashuyun.cn/Article/details/gt2qwoncwsm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2levfxnnl.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gt2elgpxkfo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.c1oappe.top/Article/details/gt2xqopklti.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmiziojg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.9152youxi.cn/Article/details/gt2yoavynnk.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2bpqkiwgw.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gt2mhtdnjff.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gt2pnkexgdm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gt2zzdoqsxl.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gt2irjpfnoo.html

echo "${#s}"
来源：http://dali.andypj.xyz/Article/details/gt2iixqsvby.html

[R22] 截取子串
来源：http://dali.xylfe.cn/Article/details/gt2bpqytcwp.html

echo "${s:0:5}"
来源：http://dali.aizwys.cn/Article/details/gt2ehleugqt.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzyizgey.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzqslqtt.html

[R24] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gt2xozhxkda.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kieiheqg.html

[R25] 去后缀 / 去前缀
来源：http://dali.mhx1999.top/Article/details/gt2rttfadrc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pycfn.com/Article/details/gt2tbwrbpmc.html

[R26] 命令替换
来源：http://dali.xinyue.icu/Article/details/gt2omjzvdyq.html

now=$(date +%F); echo "$now"
来源：http://dali.ybcxt.top/Article/details/gt2nfxyzbzo.html

[R27] 算术展开
来源：http://dali.zhoulong.xyz/Article/details/gt2dqmlpcyp.html

echo $((1 + 2 * 3))
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvwgnmiz.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbgrapvl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zycfv.cn/Article/details/gt2yushnsng.html

[R29] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gt2wwozuypk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gt2ltjxmmdg.html

[R30] 函数返回状态码
来源：http://dali.yuxming.cn/Article/details/gt2icfhwvjv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gt2twayotql.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gt2wdlrxulo.html

f() { local x=1; echo "$x"; }
来源：http://dali.aibaodan.cn/Article/details/gt2gcgnvtbr.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gt2lofyfkad.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gt2lyhjdkho.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwlklstz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gt2eyrukkkg.html

[R34] 退出时清理
来源：http://dali.hnxiangtu.top/Article/details/gt2vekkwbsl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gt2hwymdohq.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gt2qbxvaebo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.snrcjt.cn/Article/details/gt2rnporjqm.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxtkcwhm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hammf.cn/Article/details/gt2arvwkzyr.html

[R37] 把输出赋给变量
来源：http://dali.ivvv.top/Article/details/gt2irsfwyay.html

files=$(ls -1)
来源：http://dali.guowangkeji.top/Article/details/gt2ffghhumh.html

[R38] 管道串联
来源：http://dali.xuanzx.com/Article/details/gt2zotdaycw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cashguo.top/Article/details/gt2fdhjorqi.html

[R39] 重定向标准输出与错误
来源：http://dali.zdqjudy.top/Article/details/gt2fwjthcdg.html

cmd > out.log 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gt2axdzckyf.html

[R40] 追加写日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmpbqsch.html

echo "log" >> out.log
来源：http://dali.sysykeji.top/Article/details/gt2iihiyzpi.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gt2wqgblnxv.html

cmd >/dev/null 2>&1
来源：http://dali.havefunace.top/Article/details/gt2xtekjmgv.html

[R42] 输入重定向
来源：http://dali.smart0.xyz/Article/details/gt2pfntljoj.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2qvottthe.html

[R43] 按名字查找文件
来源：http://dali.tianlin.xyz/Article/details/gt2lliiszyl.html

find . -name "*.log" -type f
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvjyqctl.html

[R44] 按修改时间查找
来源：http://dali.dianchejie.cn/Article/details/gt2txosjtdo.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gt2oolsxejh.html

[R45] 批量删除
来源：http://dali.jiagoushi.top/Article/details/gt2sgubwqul.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gt2pygmvada.html

[R46] 递归替换文件内容
来源：http://dali.gzhubu.top/Article/details/gt2gvylahsh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gt2xxnrkbja.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gt2fmchlvms.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gt2mrcinhhh.html

[R48] awk 取指定列
来源：http://dali.jlsjyb.cn/Article/details/gt2tbwademq.html

awk '{print $1, $3}' a.txt
来源：http://dali.mhx1999.top/Article/details/gt2xjqzztkx.html

[R49] awk 带条件
来源：http://dali.jqgufenzy.top/Article/details/gt2mbycosch.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.vqdsnc.cn/Article/details/gt2fjgqgjce.html

[R50] awk 求和
来源：http://dali.pengpengdd.cyou/Article/details/gt2splaizxx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2mdvguhbh.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gt2ijcfiayh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.bjfxy.top/Article/details/gt2rmbciggq.html

[R52] 统计行数
来源：http://dali.quarkkingdee.top/Article/details/gt2qpwqcfvg.html

wc -l a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2frlhardz.html

[R53] 查看文件头与实时尾
来源：http://dali.shuidangran.top/Article/details/gt2vaombdst.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jlsjyb.cn/Article/details/gt2sriuzavg.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gt2usedzram.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gt2rczywmew.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gt2ltfabgwf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gt2ieboupbi.html

[R56] 远程拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwpeqfla.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gt2jjltclpv.html

[R57] 远程执行命令
来源：http://dali.xuanzx.com/Article/details/gt2ssxkhthm.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gt2dxwdvwml.html

[R58] 下载文件
来源：http://dali.guannengcc.top/Article/details/gt2fucgktxt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gt2refsjmfz.html

[R59] 发 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2mkwypkrv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daria6918.cn/Article/details/gt2flgakitf.html

[R60] 只看 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gt2xtxczovd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gt2nsshpjgf.html

[R61] 磁盘占用
来源：http://dali.sufxvd.cn/Article/details/gt2qgebkwtj.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gt2yuqpsrnt.html

[R62] 找最占空间的文件
来源：http://dali.jinqigufen.top/Article/details/gt2jpxmaubd.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gt2oebzqjyf.html

[R63] 内存与进程
来源：http://dali.snrcjt.cn/Article/details/gt2ojyuppou.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gt2dcyogyrt.html

[R64] 结束进程
来源：http://dali.zhongyouzk.top/Article/details/gt2ilmprpnn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yvedp.cn/Article/details/gt2thiaugca.html

[R65] 查看端口占用
来源：http://dali.aibaodan.cn/Article/details/gt2ticwtrfu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dashuyun.cn/Article/details/gt2gilemeod.html

[R66] 定时任务
来源：http://dali.sxryk.cn/Article/details/gt2ejrhliug.html

crontab -e;  crontab -l
来源：http://dali.jqgufenzy.top/Article/details/gt2jrkjqqgv.html

[R67] 生成随机十六进制串
来源：http://dali.xuanzx.com/Article/details/gt2rhohjnam.html

openssl rand -hex 16
来源：http://dali.pycfn.com/Article/details/gt2ezwluxek.html

[R68] 计算文件校验值
来源：http://dali.ppjwa.cn/Article/details/gt2ctzdwvnh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zykzixvn.html

[R69] 生成随机密码
来源：http://dali.fengsongda.top/Article/details/gt2dfsmkwqc.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenzaomai.com/Article/details/gt2hyusfybb.html

[R70] 时间戳与互转
来源：http://dali.yangfankeji.com/Article/details/gt2daxrnjzc.html

date +%s;  date -d @1700000000
来源：http://dali.kuanghao11.cn/Article/details/gt2zwdtmfxp.html

[R71] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gt2lpjhosue.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gt2lljavfdw.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gt2zwdygttx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gt2xzohxyfw.html

[R73] 分割大日志
来源：http://dali.redwolf501.top/Article/details/gt2ddycyclp.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gt2cqnaixki.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gt2yhdldkhj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.iojbl.cn/Article/details/gt2mwklpzce.html

[R75] 导出环境变量
来源：http://dali.yj20258.top/Article/details/gt2nnuryqzc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxthhjly.html

[R76] 使用临时文件
来源：http://dali.shuidangran.top/Article/details/gt2vqhorgiq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bwthuzvu.html

[R77] 读取用户输入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rowjzsav.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gt2hpuayiys.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gt2hmbuaibe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hfpthk.cn/Article/details/gt2zyejdtdm.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gt2lqklqpas.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gt2ogotsrsl.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gt2yztezvzs.html

time ./run.sh
来源：http://dali.chenlongwang.top/Article/details/gt2hrcuevxv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2itzfdoxp.html

S. C / C++ 专题
来源：http://dali.aibaodan.cn/Article/details/gt2tibkweou.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2oyohlqnz.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2wqrqfilc.html

#include <stdio.h>
来源：http://dali.gaohongyu789.top/Article/details/gt2kkcjppgw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gt2bzqkqswq.html

[S02] C：变量与格式化输出
来源：http://dali.cheryme.top/Article/details/gt2rlmcbydf.html

int a = 10; printf("%d\n", a);
来源：http://dali.hfpthk.cn/Article/details/gt2eccfadzs.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gt2eoculysq.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gt2dqzwtrnx.html

[S04] C：字符串复制
来源：http://dali.tanke756.top/Article/details/gt2lhpfdhtp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2eryqpefn.html

[S05] C：字符串长度
来源：http://dali.316326.xyz/Article/details/gt2pqvgqjue.html

strlen(s)
来源：http://dali.cheryme.top/Article/details/gt2xcpcygjv.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwdwndfz.html

strcmp(a, b) == 0
来源：http://dali.bjfxy.top/Article/details/gt2omgsbkgk.html

[S07] C：数组遍历求和
来源：http://dali.yangfankeji.com/Article/details/gt2mqdrsrzu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxinkj.top/Article/details/gt2zrfhjfpl.html

[S08] C：动态内存分配与释放
来源：http://dali.daria6918.cn/Article/details/gt2kxjdrekv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258.top/Article/details/gt2lnkofgrn.html

[S09] C：结构体定义与初始化
来源：http://dali.hywenlv.cn/Article/details/gt2jjjzdueg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenzaomai.com/Article/details/gt2hiiqesfi.html

[S10] C：指针与解引用
来源：http://dali.yongpay.top/Article/details/gt2nbrqmtaw.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gt2ntskkgbb.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2jxxhivot.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jlsjyb.cn/Article/details/gt2rwregpmy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.bjfxy.top/Article/details/gt2qbtqnpbw.html

fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gt2bexnutim.html

[S12] C：写文件
来源：http://dali.cashguo.top/Article/details/gt2fwfsyqyb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gt2zttbuood.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gt2yyukejyz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gt2oupubzdf.html

[S14] C：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxjclrqw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nwbrower.top/Article/details/gt2noxwovqp.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2ughohhil.html

(double) a / b
来源：http://dali.yj20258.top/Article/details/gt2osucnxfl.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gt2qnvlvfgc.html

x |= (1 << 3);
来源：http://dali.pycfn.com/Article/details/gt2qhzwicra.html

[S17] C：安全拼接字符串
来源：http://dali.iojbl.cn/Article/details/gt2atmundnu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gt2hyjxluxb.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gt2hxtmatzb.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gt2gswwmvjl.html

[S19] C：快速排序
来源：http://dali.xuanzx.com/Article/details/gt2lsvomkap.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gt2ovagxxhp.html

[S20] C：二分查找
来源：http://dali.svipenyu.cn/Article/details/gt2cwlejzye.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gt2wdzdmtbr.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gt2mzexmagg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxinkj.top/Article/details/gt2mvmbdjsh.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nuhcstzs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nwbrower.top/Article/details/gt2upuqdugy.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gt2mppkeifl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndcbpldv.html

[S24] C：获取本地时间
来源：http://dali.sweek.top/Article/details/gt2gituvsob.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gt2nhaecyxf.html

[S25] C：内存拷贝
来源：http://dali.c1oappe.top/Article/details/gt2uwotfqkd.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gt2hlqgaczi.html

[S26] C：内存清零
来源：http://dali.yj20258.top/Article/details/gt2umxrgugr.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gt2eyfctqgf.html

[S27] C：定义常量
来源：http://dali.chenjidiqi.icu/Article/details/gt2jahcdktu.html

const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gt2mvqobgph.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhmlimxi.html

static int counter = 0;
来源：http://dali.gogol.net.cn/Article/details/gt2bjabbsph.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gt2ddjnbbnq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gt2blkaoqer.html

[S30] C：头文件保护
来源：http://dali.yangfankeji.com/Article/details/gt2rvwtguhc.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gt2dhdiaciu.html

#define X_H
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxaygnqg.html

#endif
来源：http://dali.tianlin.xyz/Article/details/gt2gfgaqisw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zowswaoz.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gt2tffkpjbx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2elcofvtg.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gt2yykbkskl.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gt2apytyxze.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gt2drqkfzbo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2wrrjwibd.html

[S34] C++：遍历 vector
来源：http://dali.zhixingplan.top/Article/details/gt2ibcblwrd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhixingplan.top/Article/details/gt2qtjuycld.html

[S35] C++：map
来源：http://dali.xuetiantiany.cn/Article/details/gt2zrbqtbzf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2vbrvddds.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cwgqgxby.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2hygigjtb.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gt2ukkyyfrh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gt2gauunaya.html

[S38] C++：排序
来源：http://dali.sweek.top/Article/details/gt2sopdubma.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqfsdnu.html

[S39] C++：自定义比较器排序
来源：http://dali.svipenyu.cn/Article/details/gt2mzeayuyt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hywenlv.cn/Article/details/gt2bwfsmyqt.html

[S40] C++：查找元素
来源：http://dali.haohaochexian.top/Article/details/gt2qedudgoc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnqzz.top/Article/details/gt2wvbnjdaa.html

[S41] C++：类与构造函数
来源：http://dali.gogol.net.cn/Article/details/gt2gwvcjvaa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.svipenyu.cn/Article/details/gt2uvjwnjkr.html

[S42] C++：继承与虚函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2mthsjakw.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gt2fwowusaj.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvepkzjz.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gt2whlijkur.html

[S44] C++：引用传参
来源：http://dali.fengsongda.top/Article/details/gt2khceckmh.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gt2pwpdmfny.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gt2izdccuof.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daria6918.cn/Article/details/gt2gkqbddao.html

[S46] C++：函数模板
来源：http://dali.zhongyouzk.top/Article/details/gt2xxopxigh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhengqikj.top/Article/details/gt2stnslllc.html

[S47] C++：结构化绑定遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2ipdorfwb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yueranfly.top/Article/details/gt2wwerpqsn.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2dfbnxbzy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.quarkkingdee.top/Article/details/gt2lruckcnz.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gt2dzcstmpc.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2hcnrnkwe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gt2prylydhn.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkqmlaee.html


<!-- 参考信息 -->