代发 wailian999

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gt2hmzgisxi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofdfcixr.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gt2wgecszzb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2dvurrisj.html

[Q82] 字符长度与字节长度
来源：http://dali.yvedp.cn/Article/details/gt2utxwayvz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2zovilbkb.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gt2akcjnsbv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2obaqmcuw.html

[Q84] 去除首尾空格
来源：http://dali.tanke756.top/Article/details/gt2xizgflwk.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2entsxsnr.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gt2anmrrllt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dianchejie.cn/Article/details/gt2mojyswxs.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gt2nthvuihp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmltlmuj.html

[Q87] JSON 字段做条件
来源：http://dali.0kj1m.cn/Article/details/gt2lzkggpnw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gt2dgpimgaz.html

[Q88] 行转列（条件聚合）
来源：http://dali.hfpthk.cn/Article/details/gt2wskepprm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tanke756.top/Article/details/gt2wppmxare.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2dzhpanbp.html

[Q89] 判断表是否存在
来源：http://dali.yongpay.top/Article/details/gt2secxtrjd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcrctvfk.html

[Q90] 生成序号列
来源：http://dali.cucudq.cn/Article/details/gt2yfhczkql.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hysaishi.cn/Article/details/gt2xufihvis.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2nibljdqv.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gt2sptvitko.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2poxuvsdg.html

[R01] shebang 与严格模式
来源：http://dali.zhixingplan.top/Article/details/gt2wbvlukjf.html

#!/usr/bin/env bash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbnwtqxt.html

set -euo pipefail
来源：http://dali.yvedp.cn/Article/details/gt2bndvqmpr.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gt2qnqcpatk.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgcojvav.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gt2dhlbiopl.html

readonly PI=3.14
来源：http://dali.zdqjudy.top/Article/details/gt2sxtggbtj.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gt2abafqsrw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gt2mqwhkfke.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gt2dxsgoyet.html

name="${1:-default}"
来源：http://dali.tianlin.xyz/Article/details/gt2npgwoxyx.html

[R06] 判断命令是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2owtpcebu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lejsagts.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gt2mlmosqsa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gt2noduxzfp.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gt2ppmaltom.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2nrclemip.html

[R09] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gt2kctdgnmn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fzhhl.top/Article/details/gt2deuqsdke.html

[R10] 正则匹配
来源：http://dali.fzhhl.top/Article/details/gt2nvejfgyi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.smart0.xyz/Article/details/gt2cxxkxqxp.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tplnymqn.html

case "$1" in
来源：http://dali.gotoacloud.top/Article/details/gt2pvslrezw.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gt2hbsqopwo.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2sytssupx.html

*)     echo "未知命令" ;;
来源：http://dali.yonumen.top/Article/details/gt2jyesoleb.html

esac
来源：http://dali.ehwqpu.com/Article/details/gt2szitmrvx.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kgempnsd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2yloknaga.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gt2rrdwycyw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hhqenead.html

[R14] C 风格 for
来源：http://dali.fengsongda.top/Article/details/gt2lajumvwr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjybctjl.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2vuffrged.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guannengcc.top/Article/details/gt2tyxjeuje.html

[R16] until 等待条件
来源：http://dali.jiagoushi.top/Article/details/gt2wfvoyuna.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gt2unrgvuoq.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gt2ugneofgj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.svipenyu.cn/Article/details/gt2domzebuh.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gt2eqkvyeil.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dianchejie.cn/Article/details/gt2kenrsdiu.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gt2ybqseaje.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gt2tjpvswfi.html

[R20] 关联数组（字典）
来源：http://dali.quarkkingdee.top/Article/details/gt2hnlbtvgv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gt2cqjxqlon.html

[R21] 字符串长度
来源：http://dali.shuidangran.top/Article/details/gt2wtmhesfe.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gt2lmbfpyuu.html

[R22] 截取子串
来源：http://dali.c1oappe.top/Article/details/gt2haaqrnbt.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gt2uphirjlz.html

[R23] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gt2ceuapdsb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yongpay.top/Article/details/gt2vznzwvca.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gt2dsocfsbx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jlsjyb.cn/Article/details/gt2bgdwiyaf.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgfzy.top/Article/details/gt2ffndrdtv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnxiangtu.top/Article/details/gt2npouamxm.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gt2zybelmhz.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gt2mkllreiy.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gt2ylluwijw.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gt2kcoeeueq.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gt2shoshwro.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhixingplan.top/Article/details/gt2uqoedrej.html

[R29] 定义函数
来源：http://dali.redwolf501.top/Article/details/gt2qdlsytmk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gt2xlyoagzq.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gt2tmxygudq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gt2kmlyunpi.html

[R31] 局部变量
来源：http://dali.jlsjyb.cn/Article/details/gt2cuagdhvq.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gt2luprohoe.html

[R32] 参数个数校验
来源：http://dali.kuanghao11.cn/Article/details/gt2aznwwiug.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gt2gixturue.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gt2xveapdfc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2inmhrcjr.html

[R34] 退出时清理
来源：http://dali.redwolf501.top/Article/details/gt2whwajcsc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gt2twotdkzp.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gt2ycndcytg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zdqjudy.top/Article/details/gt2worqoclz.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gt2fpukolhh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tianlin.xyz/Article/details/gt2elldnqzs.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gt2hddtudum.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2radvfhob.html

[R38] 管道串联
来源：http://dali.nwbrower.top/Article/details/gt2fgpocxkx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icmpiaoh.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2exczlytp.html

cmd > out.log 2>&1
来源：http://dali.xziqi.cn/Article/details/gt2ycmmvhcc.html

[R40] 追加写日志
来源：http://dali.zhiwuduotai.top/Article/details/gt2cpsmexuk.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gt2afwbqjhp.html

[R41] 丢弃输出
来源：http://dali.snrcjt.cn/Article/details/gt2ijzlvhby.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gt2olpwktmq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ebidezxa.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2funlivyg.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gt2yrwndpbp.html

find . -name "*.log" -type f
来源：http://dali.aizwys.cn/Article/details/gt2ffmpvakw.html

[R44] 按修改时间查找
来源：http://dali.hysaishi.cn/Article/details/gt2fhveosqk.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gt2beekkngd.html

[R45] 批量删除
来源：http://dali.jqgufenzy.top/Article/details/gt2cchridqk.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gt2sdikwcib.html

[R46] 递归替换文件内容
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpvhvliv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guannengcc.top/Article/details/gt2zrlngywg.html

[R47] sed 单行替换
来源：http://dali.havefunace.top/Article/details/gt2thlknxyx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.smart0.xyz/Article/details/gt2xhbomrnp.html

[R48] awk 取指定列
来源：http://dali.shangyingyoupin.top/Article/details/gt2qurggyoe.html

awk '{print $1, $3}' a.txt
来源：http://dali.meibo888.top/Article/details/gt2yavisjoe.html

[R49] awk 带条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mftbrbyt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cdnleiting.top/Article/details/gt2zgdomsdp.html

[R50] awk 求和
来源：http://dali.sysykeji.top/Article/details/gt2gsokernf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gt2sipbztdh.html

[R51] 排序去重取前几
来源：http://dali.redwolf501.top/Article/details/gt2gugprbaa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.316326.xyz/Article/details/gt2bbommcjc.html

[R52] 统计行数
来源：http://dali.yj20258888.top/Article/details/gt2zmuzfmmf.html

wc -l a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2hijtyeon.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gt2peyeelnz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gt2nbydrlcq.html

[R54] 比较两个文件
来源：http://dali.yangfankeji.com/Article/details/gt2fxzjdhzd.html

diff a.txt b.txt
来源：http://dali.yj202588.top/Article/details/gt2xcntibhd.html

[R55] 压缩与解压
来源：http://dali.pengpengdd.cyou/Article/details/gt2wodhsyau.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yangfankeji.com/Article/details/gt2thajxsax.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gt2dlneqawx.html

scp file user@host:/path/
来源：http://dali.tian-w.cn/Article/details/gt2kixpbuuz.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gt2bgejvezu.html

ssh user@host 'uptime'
来源：http://dali.zhoulong.xyz/Article/details/gt2rzdzmltv.html

[R58] 下载文件
来源：http://dali.316326.xyz/Article/details/gt2upjqfalf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ivvv.top/Article/details/gt2tisailei.html

[R59] 发 POST JSON
来源：http://dali.sweek.top/Article/details/gt2sscyggrw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pengpengdd.cyou/Article/details/gt2nuafasyd.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2idkguhfa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gt2yczcctdd.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gt2xjhavgmq.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gt2oijmttwl.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gt2sywswuzp.html

du -ah . | sort -rh | head -10
来源：http://dali.andypj.xyz/Article/details/gt2nqohbldz.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gt2opaaalku.html

free -h;  ps aux | grep nginx
来源：http://dali.chenlongwang.top/Article/details/gt2ixvlmmix.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdiiieql.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigufen.top/Article/details/gt2vsnupdlp.html

[R65] 查看端口占用
来源：http://dali.dashuyun.cn/Article/details/gt2jagileih.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gt2gtkwracq.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gt2ipxkijyb.html

crontab -e;  crontab -l
来源：http://dali.gzhubu.top/Article/details/gt2libekytj.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zikfgxwq.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gt2qzrrjbai.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gt2qgxpzgsp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2cvyvkrhm.html

[R69] 生成随机密码
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxdmsoav.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gt2yoxqhslz.html

[R70] 时间戳与互转
来源：http://dali.zhixingplan.top/Article/details/gt2ayfweytp.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gt2jnlxumtk.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gt2vdiywpfd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jiagoushi.top/Article/details/gt2nbytufjk.html

[R72] 等待端口就绪
来源：http://dali.yuxming.cn/Article/details/gt2ohymewmc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gt2emwskoev.html

[R73] 分割大日志
来源：http://dali.nwbrower.top/Article/details/gt2cbclpblp.html

split -l 1000 big.log part_
来源：http://dali.havefunace.top/Article/details/gt2uvmfrthx.html

[R74] 批量重命名
来源：http://dali.yangfankeji.com/Article/details/gt2tkxjotbh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gt2mwgfznzb.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gt2gcsypueh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gt2aynlpnyu.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gt2dcudjawh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gt2qfshjjgt.html

[R77] 读取用户输入
来源：http://dali.zhongyouzk.top/Article/details/gt2cpwjwpnz.html

read -rp "请输入: " ans
来源：http://dali.jqgfzy.top/Article/details/gt2jvroangx.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gt2pzceukzt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzmremkf.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gt2umwkbkni.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenzaomai.com/Article/details/gt2ryxaxlkb.html

[R80] 查看脚本执行耗时
来源：http://dali.shuidangran.top/Article/details/gt2iesnycjn.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gt2bvkbndqb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2fnkqbyun.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qpevcwgy.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2zcdjnbrb.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2gwquazmm.html

#include <stdio.h>
来源：http://dali.fzhhl.top/Article/details/gt2qzshsqzp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fzhhl.top/Article/details/gt2vymufxvo.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gt2fltitfzj.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gt2snrnahnb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeilvwg.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gt2admdtjkg.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2unwfjaop.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gt2cknesrjz.html

[S05] C：字符串长度
来源：http://dali.chenlongwang.top/Article/details/gt2anyujopw.html

strlen(s)
来源：http://dali.yj20258888.top/Article/details/gt2suduxybs.html

[S06] C：字符串比较
来源：http://dali.tianlin.xyz/Article/details/gt2seclgkka.html

strcmp(a, b) == 0
来源：http://dali.meibo888.top/Article/details/gt2nptnozfy.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gt2jpfcejtr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeyyabs.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gt2yyatknpf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dggmrvfq.html

[S09] C：结构体定义与初始化
来源：http://dali.guowangkeji.top/Article/details/gt2fukddwnr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gt2zkvcpian.html

[S10] C：指针与解引用
来源：http://dali.gzhubu.top/Article/details/gt2mgslqqhq.html

int *p = &a;  *p = 5;
来源：http://dali.meibo888.top/Article/details/gt2pzmzmloe.html

[S11] C：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oyeaehgr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gt2bpmgdvsd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gt2wdyxfbgx.html

fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gcpilxhi.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2xvkuaesh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gt2tsdvcepe.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gt2ldbwervx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gt2apzcqchk.html

[S14] C：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gt2psxxcsvf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gt2yqrudatx.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gt2xkciuyyh.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gt2whozaavx.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gt2ctwhhaaj.html

x |= (1 << 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bsqwzrvg.html

[S17] C：安全拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2jjqmizfk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuanzhike.top/Article/details/gt2gizmwptn.html

[S18] C：命令行参数
来源：http://dali.snrcjt.cn/Article/details/gt2pzhllgoy.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gt2vazgaron.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gt2jhnadsyq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gt2orjydzme.html

[S20] C：二分查找
来源：http://dali.sysykeji.top/Article/details/gt2ydoyndns.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmlndczt.html

[S21] C：字符类别判断
来源：http://dali.zhengqikj.top/Article/details/gt2olhpsrzc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtoijymi.html

[S22] C：字符串转数字
来源：http://dali.yonumen.top/Article/details/gt2wamfpomn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jyoumei.cn/Article/details/gt2jdhybqxw.html

[S23] C：随机数
来源：http://dali.316326.xyz/Article/details/gt2mfqdsamk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfyxdeob.html

[S24] C：获取本地时间
来源：http://dali.zhengqikj.top/Article/details/gt2nqbcniet.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gt2gjxccdlj.html

[S25] C：内存拷贝
来源：http://dali.xinyue.icu/Article/details/gt2odudwbmf.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gt2zvputdjr.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uplnhclc.html

memset(a, 0, sizeof a);
来源：http://dali.chenzaomai.com/Article/details/gt2aqffzxld.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gt2cydwwzev.html

const double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2jqddcwjz.html

[S28] C：静态变量
来源：http://dali.quarkkingdee.top/Article/details/gt2upqbizcf.html

static int counter = 0;
来源：http://dali.sxryk.cn/Article/details/gt2jcypbbax.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gt2yzmpangh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsxlxro.html

[S30] C：头文件保护
来源：http://dali.svipenyu.cn/Article/details/gt2trrswobz.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gt2aakfyfwo.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gt2ybxnbzrg.html

#endif
来源：http://dali.guowangkeji.top/Article/details/gt2cdyosvmt.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2ipxpnrma.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gt2hecszwcd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2eutknqtv.html

[S32] C++：字符串
来源：http://dali.sweek.top/Article/details/gt2ovobroib.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gt2mljwlxgq.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gt2brtywjuu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gotoacloud.top/Article/details/gt2lmxzwtyk.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gt2ksoagmvg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gt2zuqxxgrk.html

[S35] C++：map
来源：http://dali.ivvv.top/Article/details/gt2wohvnilm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2tlyekfwv.html

[S36] C++：unordered_map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spnqyzcb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2nnmpehtg.html

[S37] C++：set
来源：http://dali.yj20258888.top/Article/details/gt2nilyfqyo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hfpthk.cn/Article/details/gt2odkbrqyu.html

[S38] C++：排序
来源：http://dali.zhengqikj.top/Article/details/gt2okurphdq.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gt2qgnrarzd.html

[S39] C++：自定义比较器排序
来源：http://dali.hammf.cn/Article/details/gt2jdyvmplb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gt2xwqqvffh.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gt2hwobritp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gt2cdrkfxiy.html

[S41] C++：类与构造函数
来源：http://dali.c1oappe.top/Article/details/gt2oajklgid.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gt2zpxcwikb.html

[S42] C++：继承与虚函数
来源：http://dali.9152youxi.cn/Article/details/gt2gfeekmaf.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gt2oiqdeyhb.html

[S43] C++：智能指针
来源：http://dali.daxiang520.top/Article/details/gt2rgclhtpq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvemkili.html

[S44] C++：引用传参
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtadyjsq.html

void inc(int &x) { ++x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lpkqcexz.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvouugya.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gt2rmeviwow.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gt2wtpovlnh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gt2ffctmgcg.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gt2geunnpvk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jianghu66.top/Article/details/gt2zfemjyqa.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2snaecfmj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gt2ncswwmha.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gt2befqbsxj.html

[S49] C++：写文件
来源：http://dali.birdmap.top/Article/details/gt2bfujohwc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gt2sjznvzsd.html

[S50] C++：格式化数字
来源：http://dali.c1oappe.top/Article/details/gt2gvzxpjyl.html


<!-- 参考信息 -->