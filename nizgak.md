代发 wailian999

[Q80] 字符串截取
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzfpiqol.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2qmqlvcdt.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gt2scoarebv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2ggftqmsn.html

[Q82] 字符长度与字节长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhrowtuo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2fozpvjck.html

[Q83] 大小写转换
来源：http://dali.cheryme.top/Article/details/gt2teyijwuo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2grcezubf.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gt2gptfxlih.html

SELECT TRIM(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2nnwwqfgs.html

[Q85] 数值取整
来源：http://dali.yj20258888.top/Article/details/gt2dzlufnzz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangdashe.top/Article/details/gt2jdkfspcr.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxinkj.top/Article/details/gt2jeclrrht.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.bjfxy.top/Article/details/gt2leajbcxn.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gt2tdghfoys.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.kuanghao11.cn/Article/details/gt2epemblzh.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gt2dixuuzfc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gt2qxymvxpu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2pqmmxopw.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gt2kovytcmi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sufxvd.cn/Article/details/gt2rvwhcqyn.html

[Q90] 生成序号列
来源：http://dali.havefunace.top/Article/details/gt2jsmufzzb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gt2dpihzcwm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2weixougi.html

R. Bash 专题
来源：http://dali.smart0.xyz/Article/details/gt2vqvoydai.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2gfjcssic.html

[R01] shebang 与严格模式
来源：http://dali.sxryk.cn/Article/details/gt2yjtgvuiv.html

#!/usr/bin/env bash
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvpnxvml.html

set -euo pipefail
来源：http://dali.wangdashe.top/Article/details/gt2vdequefx.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gt2qoxvrbvs.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gt2aprjqfap.html

[R03] 只读变量
来源：http://dali.ydzc1.top/Article/details/gt2pczikohe.html

readonly PI=3.14
来源：http://dali.zhongyouzk.top/Article/details/gt2wxjgppzx.html

[R04] 位置参数
来源：http://dali.svipenyu.cn/Article/details/gt2goecbfnb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gt2immsoete.html

[R05] 参数默认值
来源：http://dali.pengpengdd.cyou/Article/details/gt2iimdymdm.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gt2ymwqlbge.html

[R06] 判断命令是否存在
来源：http://dali.zhixingplan.top/Article/details/gt2igbrhbaz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gt2fdybkpuz.html

[R07] if 判断文件
来源：http://dali.jiagoushi.top/Article/details/gt2jdagwmml.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gt2cstswiyi.html

[R08] 数值比较
来源：http://dali.sufxvd.cn/Article/details/gt2kizzbqop.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2hgyyvucl.html

[R09] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gt2dkvdkbxq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.316326.xyz/Article/details/gt2oqpkxbfv.html

[R10] 正则匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xxepodfw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bagsyues.html

[R11] case 多分支
来源：http://dali.ppjwa.cn/Article/details/gt2lhyryohd.html

case "$1" in
来源：http://dali.yanxiufei.cn/Article/details/gt2zagcijlq.html

start) echo "启动" ;;
来源：http://dali.yj20258.top/Article/details/gt2hdpkjjza.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2eapkyqqt.html

*)     echo "未知命令" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gt2gvcyxshm.html

esac
来源：http://dali.hywenlv.cn/Article/details/gt2epjjqtvr.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dbuffhwr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbnahzku.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gt2vjmctvon.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gt2pyszhpki.html

[R14] C 风格 for
来源：http://dali.yuanzhike.top/Article/details/gt2ukvitikv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gt2detozfhv.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zyighqeq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2twjuidhf.html

[R16] until 等待条件
来源：http://dali.aibaodan.cn/Article/details/gt2qnuapfuz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gt2tzeyyuuo.html

[R17] 数组定义与取值
来源：http://dali.mhx1999.top/Article/details/gt2sqwawelo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnxiangtu.top/Article/details/gt2ieelboan.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gt2nlugybcy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jianghu66.top/Article/details/gt2jwrxjfgs.html

[R19] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yuiemidf.html

echo "${#arr[@]}"
来源：http://dali.gaohongyu789.top/Article/details/gt2azqjtwef.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gt2dtmhpqus.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jiagoushi.top/Article/details/gt2ujukcyxy.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gt2cuuvnkzt.html

echo "${#s}"
来源：http://dali.haohaochexian.top/Article/details/gt2trvqivfp.html

[R22] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gt2rklstgfb.html

echo "${s:0:5}"
来源：http://dali.jinqigfzy.top/Article/details/gt2eivpvmbi.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gt2aycerhrg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gt2kxqppelp.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gt2bnzrubps.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258888.top/Article/details/gt2ptxqopis.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gt2dtzwpfod.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guannengcc.top/Article/details/gt2qsflrdqg.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gt2fatmrizz.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gt2sxbxvttm.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gt2hxiewjxp.html

echo $((1 + 2 * 3))
来源：http://dali.ydzc1.top/Article/details/gt2joohezbc.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gt2eclfpdyo.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gt2eexxbtqo.html

[R29] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gt2dkrfmafw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gt2dddmhnqh.html

[R30] 函数返回状态码
来源：http://dali.sysykeji.top/Article/details/gt2gkigdeen.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gt2osrruepl.html

[R31] 局部变量
来源：http://dali.dianchejie.cn/Article/details/gt2fluxdgof.html

f() { local x=1; echo "$x"; }
来源：http://dali.zdqjudy.top/Article/details/gt2iwxvzerd.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gt2ujhprido.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2nzcibmxd.html

[R33] 捕获错误并提示行号
来源：http://dali.sufxvd.cn/Article/details/gt2rdyqatxo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gt2uqlukgbm.html

[R34] 退出时清理
来源：http://dali.shangyingyoupin.top/Article/details/gt2kaidoksy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2wasfgurs.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gt2ersrwgcs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cashguo.top/Article/details/gt2zklcdral.html

[R36] 并发执行多个任务
来源：http://dali.fzhhl.top/Article/details/gt2sloutcva.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wylqyivo.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gt2shbfrxmb.html

files=$(ls -1)
来源：http://dali.fzhhl.top/Article/details/gt2noinqltp.html

[R38] 管道串联
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbahsixp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gt2ukfvwwhr.html

[R39] 重定向标准输出与错误
来源：http://dali.svipenyu.cn/Article/details/gt2okepdvcw.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gt2tpbrofcd.html

[R40] 追加写日志
来源：http://dali.yuanzhike.top/Article/details/gt2hwnmkmgb.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gt2izuhneqr.html

[R41] 丢弃输出
来源：http://dali.sysykeji.top/Article/details/gt2nyazrplg.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gt2ouxgsvod.html

[R42] 输入重定向
来源：http://dali.nwbrower.top/Article/details/gt2tpopgcpz.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2evlrqtwz.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcyvibpn.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gt2ikhyjulw.html

[R44] 按修改时间查找
来源：http://dali.yvedp.cn/Article/details/gt2gqjwukts.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gt2qznfeilz.html

[R45] 批量删除
来源：http://dali.nanxinkj.top/Article/details/gt2rptibtdr.html

find . -name "*.tmp" -delete
来源：http://dali.tian-w.cn/Article/details/gt2lrxzdmem.html

[R46] 递归替换文件内容
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dequacdf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gt2vlgevorq.html

[R47] sed 单行替换
来源：http://dali.yvedp.cn/Article/details/gt2yhfhyfbl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2urbdtxzu.html

[R48] awk 取指定列
来源：http://dali.wangdashe.top/Article/details/gt2vlpejknw.html

awk '{print $1, $3}' a.txt
来源：http://dali.yongpay.top/Article/details/gt2mqkykmfx.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gt2rertrkvw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gt2wtlfmqmb.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gt2soasmrxk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xinyue.icu/Article/details/gt2muepfmhp.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gt2syzmrpbh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gt2gxausicw.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gt2cmlwtsma.html

wc -l a.txt
来源：http://dali.hnqzz.top/Article/details/gt2geleaecj.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gt2acrjliks.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gt2yyyofqbu.html

[R54] 比较两个文件
来源：http://dali.yj202588.top/Article/details/gt2evdmceur.html

diff a.txt b.txt
来源：http://dali.nwbrower.top/Article/details/gt2zanqdone.html

[R55] 压缩与解压
来源：http://dali.hnxiangtu.top/Article/details/gt2umihmpkt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gt2ysztdsyi.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gt2smadspoa.html

scp file user@host:/path/
来源：http://dali.hammf.cn/Article/details/gt2nqrttkhm.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gt2ooclsrld.html

ssh user@host 'uptime'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfbvvvuo.html

[R58] 下载文件
来源：http://dali.ybcxt.top/Article/details/gt2jizddylo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gt2ftixiidb.html

[R59] 发 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gt2nhxiylzy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gt2llqejuun.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gt2htozqmxj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sufxvd.cn/Article/details/gt2dhwafykf.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gt2brwonhsc.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gt2zysiqwon.html

[R62] 找最占空间的文件
来源：http://dali.gzhubu.top/Article/details/gt2wegvpstv.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gt2vhzjuptx.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gt2lljyahss.html

free -h;  ps aux | grep nginx
来源：http://dali.sysykeji.top/Article/details/gt2nroqxpbn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xteuesgw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gt2zxfpiguk.html

[R65] 查看端口占用
来源：http://dali.gaohongyu789.top/Article/details/gt2ckotnfjn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gt2btpqtzhx.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gt2ncdrwzoo.html

crontab -e;  crontab -l
来源：http://dali.jqgufenzy.top/Article/details/gt2uiodjjpm.html

[R67] 生成随机十六进制串
来源：http://dali.guowangkeji.top/Article/details/gt2plhoxqli.html

openssl rand -hex 16
来源：http://dali.hysaishi.cn/Article/details/gt2vcxrcwxe.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gt2lkjowndg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2mfxzedtx.html

[R69] 生成随机密码
来源：http://dali.sysykeji.top/Article/details/gt2ogxivkbj.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gt2wxnabgrg.html

[R70] 时间戳与互转
来源：http://dali.shzxlz.cn/Article/details/gt2dvtvcxyv.html

date +%s;  date -d @1700000000
来源：http://dali.xinyue.icu/Article/details/gt2sqnqlnlj.html

[R71] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gt2uuaravex.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gt2tthrkoyh.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gt2tfjjrcqb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gt2zllfincn.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gt2llzjrwvs.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gt2aevkalgh.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gt2ekmqqdhh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.iojbl.cn/Article/details/gt2ohlkauhx.html

[R75] 导出环境变量
来源：http://dali.smart0.xyz/Article/details/gt2fjaptkyb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chnxfhnv.html

[R76] 使用临时文件
来源：http://dali.yueranfly.top/Article/details/gt2hgkqqkhe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2ofbtffjo.html

[R77] 读取用户输入
来源：http://dali.cdnleiting.top/Article/details/gt2iizgbzhq.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctwcdelo.html

[R78] 交互式菜单
来源：http://dali.xylfe.cn/Article/details/gt2wlhciocm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yanxiufei.cn/Article/details/gt2qcozaard.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gt2rsknrxxn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guowangkeji.top/Article/details/gt2btpaaypn.html

[R80] 查看脚本执行耗时
来源：http://dali.mhx1999.top/Article/details/gt2faprboxy.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gt2ddoydalw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2jsuxuuil.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gt2jnfmphsm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ylulmcyc.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gt2vlqlebkj.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gt2bjldmsod.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnqzz.top/Article/details/gt2mbdwvckc.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hnjybora.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tohjihnw.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gt2jaeagnjn.html

int x; scanf("%d", &x);
来源：http://dali.mhx1999.top/Article/details/gt2mpnyypxh.html

[S04] C：字符串复制
来源：http://dali.yuxming.cn/Article/details/gt2jrdjynrz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gt2alwpsrit.html

[S05] C：字符串长度
来源：http://dali.zhengqikj.top/Article/details/gt2xcwmulaz.html

strlen(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2rcoxidud.html

[S06] C：字符串比较
来源：http://dali.bjfxy.top/Article/details/gt2andonwfh.html

strcmp(a, b) == 0
来源：http://dali.smart0.xyz/Article/details/gt2wzayyumk.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gt2xdizrppt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hysaishi.cn/Article/details/gt2wgqggdtt.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gt2kkvesahm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgevescv.html

[S09] C：结构体定义与初始化
来源：http://dali.zdqjudy.top/Article/details/gt2jzizeudn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gt2lkbgdhjs.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gt2nbpmbxxv.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gt2fgfgdchq.html

[S11] C：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gt2xsiufumq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gt2oclwzlda.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gt2azxrmvor.html

fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gt2dmykwfsl.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gt2rinerlzt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gt2payoracw.html

[S13] C：宏定义
来源：http://dali.vqdsnc.cn/Article/details/gt2qvjrolmf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gt2jomcllih.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gt2rikpabmy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.andypj.xyz/Article/details/gt2wddovjmx.html

[S15] C：类型转换
来源：http://dali.xylfe.cn/Article/details/gt2fwdbpvta.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gt2rxuflcso.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gt2arrerhun.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gt2meeqaytg.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmcxvpuf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zdqjudy.top/Article/details/gt2bylmsszf.html

[S18] C：命令行参数
来源：http://dali.pycfn.com/Article/details/gt2fckkginu.html

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvfcjjfk.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gt2rguxmgps.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2xsfvddqw.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gt2tkyycyts.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrorvcrj.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gt2ztshcxwk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gt2fukeorkx.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktznxrnk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cqqwz.cn/Article/details/gt2dhcnaepf.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gt2sxrqlfjc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.havefunace.top/Article/details/gt2rbcfkzkp.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gt2yigvterh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cucudq.cn/Article/details/gt2rztudhyh.html

[S25] C：内存拷贝
来源：http://dali.mhx1999.top/Article/details/gt2uckpduyl.html

memcpy(dst, src, n);
来源：http://dali.dianchejie.cn/Article/details/gt2zphtgtbe.html

[S26] C：内存清零
来源：http://dali.yueranfly.top/Article/details/gt2asegmzyc.html

memset(a, 0, sizeof a);
来源：http://dali.yanxiufei.cn/Article/details/gt2hubypgxp.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gt2lgeoettp.html

const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gt2jjkhcvxi.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gt2cgbcqstr.html

static int counter = 0;
来源：http://dali.xuanzx.com/Article/details/gt2fbyhyeqt.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gt2tcojsbbg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gt2qparsrfn.html

[S30] C：头文件保护
来源：http://dali.hongshengwenyu.top/Article/details/gt2idcblmkt.html

#ifndef X_H
来源：http://dali.gotoacloud.top/Article/details/gt2niavppab.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gt2gplqibnf.html

#endif
来源：http://dali.zhongyouzk.top/Article/details/gt2xhijrlmh.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2tuucgrjo.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xvdzrumy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xziqi.cn/Article/details/gt2fugfoowa.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gt2tymasqsf.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gt2zlrfqdkl.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gt2pmtievax.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gt2hcbhfpsv.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gt2dqdfijhu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gt2jnpvnkcc.html

[S35] C++：map
来源：http://dali.zdqjudy.top/Article/details/gt2zyggyhbd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2lhnttqqm.html

[S36] C++：unordered_map
来源：http://dali.zhixingplan.top/Article/details/gt2jnazzzpe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2pmwnzawi.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gt2yfkfdcrj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258888.top/Article/details/gt2hihyovft.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gt2brcuiilu.html

std::sort(v.begin(), v.end());
来源：http://dali.shzxlz.cn/Article/details/gt2crbnqjtp.html

[S39] C++：自定义比较器排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntkuawwa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gt2jupewbqx.html

[S40] C++：查找元素
来源：http://dali.zhongyouzk.top/Article/details/gt2cgofcdbi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gt2screekxz.html

[S41] C++：类与构造函数
来源：http://dali.gotoacloud.top/Article/details/gt2jbpblusi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcnlhnyp.html

[S42] C++：继承与虚函数
来源：http://dali.chenzaomai.com/Article/details/gt2ztqgvvzs.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gt2wiwpxsdx.html

[S43] C++：智能指针
来源：http://dali.yuanzhike.top/Article/details/gt2quejqhzu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zdqjudy.top/Article/details/gt2vtaalndv.html

[S44] C++：引用传参
来源：http://dali.fzhhl.top/Article/details/gt2riocdqoc.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gt2midtdquu.html

[S45] C++：lambda
来源：http://dali.gogol.net.cn/Article/details/gt2sbegvire.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jianghu66.top/Article/details/gt2naahgyrl.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gt2gatmrbus.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fzhhl.top/Article/details/gt2qrubocbx.html

[S47] C++：结构化绑定遍历
来源：http://dali.yongpay.top/Article/details/gt2jxkvlbok.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gt2yaerqyck.html

[S48] C++：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2kgsnrkuc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sysykeji.top/Article/details/gt2vrvhjxmd.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gt2eqroulzu.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gt2txbzfbfj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gt2ozjrisht.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gt2rjjdtwus.html


<!-- 参考信息 -->